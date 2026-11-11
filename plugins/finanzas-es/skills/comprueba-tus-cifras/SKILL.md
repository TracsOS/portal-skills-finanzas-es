---
name: comprueba-tus-cifras
description: Comprueba el resultado de un proceso financiero (una conciliación bancaria, unas periodificaciones, un comentario de variaciones…) con las comprobaciones que Tracs ha sacado de probar skills con libros españoles. Úsala cuando alguien pida comprobar, revisar o validar unas cifras ya preparadas, con su propia skill o con la de otro, antes de darlas por buenas.
---

# Comprueba tus cifras

Comprueba un resultado ya hecho, no lo rehace. Lee las comprobaciones del proceso en tracs.es, hace cada una con las cifras del usuario y dice cuáles cuadran y cuáles no. No corrige ni contabiliza nada.

## 1. Averigua el proceso

Pregunta qué proceso es, si no está claro. Los procesos y su nombre en tracs.es:

| Proceso | Nombre |
|---|---|
| Facturación emitida | `facturacion` |
| Cuentas a pagar | `facturas-proveedores` |
| Cuentas a cobrar | `cobros` |
| Conciliación bancaria | `conciliacion` |
| Cierre contable (periodificaciones, asientos de cierre) | `cierre-mensual` |
| Nóminas | `nominas` |
| Contratos | `contratos` |
| Notas de gastos | `gastos` |
| Reporting y KPIs (cuenta de resultados, desviaciones, informes) | `reporting` |

## 2. Lee las comprobaciones del proceso

Lee `https://tracs.es/comprobaciones/<nombre>.md`. La lista de procesos que ya tienen comprobaciones está en `https://tracs.es/comprobaciones/index.md`. Léelas cada vez: crecen con cada skill que se prueba.

La página tiene dos partes. Haz las de **En cada resultado**. Las de **Al probar una skill nueva** sirven para decidir si fiarse de una skill, no para comprobar un resultado: menciónalas solo si el usuario está probando una skill por primera vez.

- Si el proceso todavía no tiene página, dilo y haz solo las comprobaciones generales del paso 3.
- Si no puedes leer tracs.es, dilo y pide al usuario que pegue el contenido de la página. No las escribas de memoria.

## 3. Añade las comprobaciones generales

Valen para cualquier proceso:

- Los totales cuadran con el origen: lo que sale suma lo mismo que el fichero o el saldo del que parte, al céntimo.
- No se pierde ni se duplica nada: cada fila del origen aparece una vez en el resultado, o está explicada.
- No queda nada sin asignar: cada importe tiene su cuenta, su partida o su causa.
- El periodo es el correcto: todas las fechas caen en el mes o el periodo que se está cerrando.

## 4. Haz cada comprobación

Para cada una:

1. Di qué cifras necesitas. Si no las tienes, pídelas; no las supongas ni las calcules a partir de otras.
2. Hazla con las cifras del usuario y enseña la cuenta, por ejemplo: 1.150,00 + 240,00 − 9,00 = 1.381,00 €.
3. Da uno de tres resultados: **cuadra**, **no cuadra** (con la diferencia exacta y dónde está) o **no se puede comprobar** (y qué falta).

## 5. Informa

Una tabla con cada comprobación, su resultado y la cuenta. Debajo, lo que no cuadra, de más a menos importe.

Si alguna no cuadra, dilo al principio y no des el resultado por bueno. No corrijas nada: propón qué revisar y deja la decisión a quien prepara las cifras.

## Fuente

Las comprobaciones salen de las pruebas publicadas en [tracs.es](https://tracs.es): cada una dice qué skill se probó y qué pasó. Cómo probamos: [tracs.es/como-probamos](https://tracs.es/como-probamos).
