# Meses de prueba

Los meses con los que probamos cada recurso del portal de [tracs.es](https://tracs.es) antes de publicarlo. La prueba completa está explicada en la página *Cómo probamos cada recurso* de tracs.es.

Todo es ficticio: **Ejemplo Servicios SL** no existe, y los clientes y proveedores de los ficheros son inventados o se usan solo como nombres de ejemplo.

Cada carpeta es un mes de un proceso y tiene:

- los ficheros que recibe Claude, tal como los exportaría un programa de contabilidad español;
- `solucion.md`, con los casos preparados y cuánto suma cada uno. **Claude no la ve durante la prueba.**

| Proceso | Mes | Casos preparados |
|---|---|---|
| [Conciliación bancaria](conciliacion-bancaria/) | [octubre 2026](conciliacion-bancaria/2026-10/) | 7 |
| | [noviembre 2026](conciliacion-bancaria/2026-11/) | 12 |
| [Comentario de variaciones](comentario-de-variaciones/) | [octubre 2026](comentario-de-variaciones/2026-10/) | 7 |
| | [diciembre 2026](comentario-de-variaciones/2026-12/) | 10 |
| [Periodificaciones](periodificaciones/) | [octubre 2026](periodificaciones/2026-10/) | 3 |
| | [noviembre 2026](periodificaciones/2026-11/) | 3 |

## Cómo repetir una prueba

Dale a tu agente el recurso, los ficheros de un mes (sin `solucion.md`) y una petición como la haría quien cierra el mes, por ejemplo: *«Concilia el banco de noviembre con la 572»*. Después compara su respuesta con `solucion.md`, caso por caso, y comprueba que la diferencia del mes queda explicada al céntimo.

Si encuentras un error en una solución, abre una incidencia: ya corregimos una al ver que la prueba tenía razón y nosotros no.
