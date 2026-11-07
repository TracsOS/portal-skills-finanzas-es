# Solución — conciliación bancaria, noviembre 2026

Ficheros: `banco_nov.csv` (extracto) y `mayor_572_nov.csv` (mayor de la 572 con formato español: `;` como separador y coma decimal).

Movimiento neto del mes: banco +4.097,28 €; 572 +2.738,85 €. **Diferencia (banco − 572): +1.358,43 €.**

| # | Caso | Qué es | Efecto en la diferencia |
|---|---|---|---|
| 1 | Comisión por transferencia, 03/11, −2,50 | Solo en el banco (626) | −2,50 |
| 2 | Intereses del préstamo, 14/11, −84,20 | Solo en el banco (662). La cuota de capital (−850,00) sí está contabilizada y debe emparejarse | −84,20 |
| 3 | Vodafone, −64,13 | Anotado dos veces (2107 y 2109); el banco lo cargó una vez | +64,13 |
| 4 | Devolución de Amazon, +120,00 | En el banco entra dinero; el asiento 2111 la lleva al haber, como un pago: signo cambiado | +240,00 |
| 5 | Imprenta Rivas | Banco −954,50, asiento −945,50: cifras cambiadas de orden | −9,00 |
| 6 | Pagaré de Herrajes Delta, vencimiento 15/12, −1.150,00 | Solo en la contabilidad: pendiente. No es un error | +1.150,00 |
| 7 | Kappa Hoteles, 2.299,00 | Banco 18/11, asiento 16/11: fecha distinta dentro del margen | 0,00 |
| 8 | Alquiler de la nave, −1.815,00 | Banco 16/11, asiento 14/11: fecha distinta dentro del margen | 0,00 |
| 9 | Lambda Retail, factura 2026-140, 1.452,00 | Banco 24/11, asiento 30/11: seis días, fuera de un margen de tres. Mismo número de factura: es el mismo cobro | 0,00 |
| 10 | Omega Logística, 3.630,00 | Una transferencia paga dos facturas: asientos 2101 (2.420,00) y 2102 (1.210,00) | 0,00 |
| 11 | Dos cobros de 500,00 el 04/11 | Norte Pack y Sur Catering, en distinto orden en cada lado: se distinguen por el nombre | 0,00 |
| 12 | Formato español | Importes como `1.210,00` en el mayor: hay que convertirlos antes de comparar | — |

**Comprobación:** −2,50 − 84,20 + 64,13 + 240,00 − 9,00 + 1.150,00 = **1.358,43 €**.
