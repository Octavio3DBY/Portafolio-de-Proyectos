# Descripción del Proyecto

Este proyecto consistió en el rediseño y automatización del reporte de gastos de la planta productiva de gomas y caramelos más grande del mundo: Planta Puebla de Mondelēz International.

El proceso que definí para la generación de este reporte, grosso modo, consistió en lo siguiente:

1. Cada mes se hacía una extracción de SAP de la transacción KSB1 de todos los gastos en los que había incurrido la planta. Esta extracción se exportaba en un archivo Excel con un formato establecido que alimentaba la base de datos del reporte (ver pestaña DetalleMes): cada hilera es un gasto y  cada columna es una variable de este gasto.
2. Después de alimentar la base de datos, 
