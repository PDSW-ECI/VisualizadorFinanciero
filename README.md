# VisualizadorFinanciero
Visualizador financiero que hace uso tanto de un visor como de una fuente de datos provistos por un tercero.

Actualmente el visualizador financiero usa la clase CloudStockData como fuente de datos. Sin embargo, los datos 'interesantes' los provee la clase DataExtractor. Desafortunadamente ambas clases usan interfaces incompatibles entre sí.

Mediante el uso de patrones de diseño estructurales, resuelva el problema de integración planteado.


#### Criterios de evaluación

- Funcional:
  - La herramienta muestra gráficamente el nuevo conjunto de puntos.

- Diseño:
  - La relación entre el adaptador y el elemento adaptado es de agregación (al adaptador se le pasa una referencia, éste NO crea uno nuevo).
