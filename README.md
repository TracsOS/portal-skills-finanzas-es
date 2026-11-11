# Skills de finanzas para empresas españolas

Skills para Claude adaptadas a cómo trabaja una empresa española: el Plan General Contable, el extracto del banco en Norma 43, la cuenta 572 con su debe y su haber.

Una skill es un conjunto de instrucciones que Claude sigue paso a paso. Muchas de las que se publican están pensadas para Estados Unidos o para fondos de inversión, y fallan con unos libros españoles. Cuando una falla, la adaptamos, la volvemos a probar y la publicamos aquí, con el original enlazado.

Cada skill tiene su ficha en [tracs.es](https://tracs.es): qué hace, cómo la probamos, qué salió y qué falló.

## Cómo instalarlas

En Claude Code:

```
claude plugin marketplace add TracsOS/portal-skills-finanzas-es
claude plugin install finanzas-es@tracs-finanzas-es
```

Tu agente también puede leer cualquier skill directamente desde este repositorio o desde su ficha en tracs.es, sin instalar nada.

## Skills

| Skill | Para qué sirve | Original |
|---|---|---|
| [conciliacion-bancaria-572](plugins/finanzas-es/skills/conciliacion-bancaria-572/SKILL.md) | Concilia el extracto del banco con el mayor de la 572 y explica cada diferencia | [gl-recon](https://github.com/anthropics/financial-services/blob/main/plugins/agent-plugins/gl-reconciler/skills/gl-recon/SKILL.md), de Anthropic |
| [comprueba-tus-cifras](plugins/finanzas-es/skills/comprueba-tus-cifras/SKILL.md) | Comprueba unas cifras ya preparadas, con tu skill o con la de otro, con las comprobaciones que sacamos de cada prueba; las lee de tracs.es, así que crecen con cada skill probada | Tracs |

## Cómo las probamos

Cada skill pasa la misma prueba antes de publicarse: Claude la sigue a ciegas con meses de una empresa ficticia y comparamos lo que da con una solución que no ve. Los meses y sus soluciones están en [`pruebas/`](pruebas/), para que puedas repetir la prueba.

## Límites

Son la versión gratuita y de aficionado: las hemos probado con datos ficticios y no contabilizan nada. Revisa cada propuesta antes de usarla. Si necesitas que las finanzas de tu empresa funcionen con cifras en las que puedas confiar, eso lo hacemos en [Tracs](https://tracs.es).

## Licencia

Apache 2.0. Las skills derivadas de las de Anthropic indican el original y los cambios; ver `NOTICE`.
