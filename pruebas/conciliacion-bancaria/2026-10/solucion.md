# Solución — conciliación bancaria, octubre 2026

Ficheros: `banco.csv` (extracto) y `mayor_572.csv` (mayor de la cuenta 572, con debe y haber).

Movimiento neto del mes: banco +8.362,87 €; 572 +7.652,45 €. **Diferencia (banco − 572): +710,42 €.**

| # | Caso | Qué es | Efecto en la diferencia |
|---|---|---|---|
| 1 | Comisión de mantenimiento, 06/10, −15,00 | Solo en el banco: falta contabilizarla (626) | −15,00 |
| 2 | Intereses de la cuenta, 30/10, +0,42 | Solo en el banco: faltan por contabilizar (769) | +0,42 |
| 3 | Cobro de Delta Hoteles, 3.025,00 | Banco 16/10, asiento 15/10: fecha distinta, mismo importe | 0,00 |
| 4 | Liquidación TPV del 17/10 | Banco 1.544,75, asiento 1.545,75: error al teclear | −1,00 |
| 5 | Pago a Textil Sur, 2.178,00 | Asiento 1019 en el debe por error, 1020 lo anula, 1021 es el pago real. 1019 y 1020 suman cero; 1021 se empareja con el banco | 0,00 |
| 6 | Pagaré de Gráfica Levante, 30/10, −726,00 | Solo en la contabilidad: pendiente de cargo. No es un error | +726,00 |
| 7 | Sin referencia común | El banco no trae número de asiento: hay que emparejar por importe, fecha y concepto | — |

**Comprobación:** −15,00 + 0,42 − 1,00 + 726,00 = **710,42 €**.

Además: falta el asiento 1005 en la numeración (no es una diferencia, pero conviene señalarlo).
