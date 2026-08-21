# Modelos Multifactoriales y Frontera Eficiente (CAPM y APT)

## Descripción del Proyecto
Este repositorio contiene un análisis cuantitativo enfocado en la optimización de carteras y la estimación del riesgo sistemático de 8 activos líquidos del mercado estadounidense. Se aplica la teoría moderna de portafolios de Markowitz para hallar la frontera eficiente y se implementan modelos de valoración de activos (CAPM y APT).

## Metodología Matemática
El análisis se divide en etapas estructuradas:
* **Frontera de Mínima Varianza:** Cálculo matricial para minimizar el riesgo dado un retorno objetivo, determinando el Portafolio de Mínima Varianza (MVP) y la Cartera de Tangencia.
* **CAPM (Capital Asset Pricing Model):** Estimación del riesgo sistemático (beta) y el alfa de Jensen mediante regresiones de mínimos cuadrados ordinarios (OLS).
* **APT (Arbitrage Pricing Theory):** Implementación de modelos multifactoriales evaluando el impacto del S&P 500, el índice VIX y el índice DXY (riesgo cambiario), validando las primas de riesgo mediante el procedimiento de Fama-MacBeth.

## Herramientas y Tecnologías
* **Python** (Análisis estadístico, simulaciones de Monte Carlo y modelos de regresión).
* **LaTeX** (Documentación técnica y maquetación de demostraciones matemáticas).
