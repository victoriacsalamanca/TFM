# TFM
The following files contain the essential code to run a factor, cluster and trend analysis of the United Nations Sustainable Development Goals implemented in 2015. This is part of the Master Thesis of the course in Computational Social Sciences of the UC3M. Data is available in Eurostat database web page. 

## Installation
- Prerequisites to have `R` and an `rmd` reader installed. 
- Then `git clone` the [TFM repository](https://github.com/victoriacsalamanca/TFM.git).
- Install dependencies (`install_dependencies.R`)

## Usage
El modo de uso requiere la realización de los siguientes pasos en el orden establecido. la primera vez que se ejecutan todos los ficheros ha de hacerse en el orden que se marca en su nombre. 
1. Se ejecuta `1-preprocessing-clustering.rmd`que proporciona la base de datos necesaria para continuar con los análisis.
2. Se ejecuta `2-preprocessing-trends.rmd` que proporciona la base de datos necesaria para realizar el análisis de tendencias.
3. Se ejecuta `3-clustering_analysis.rmd` en el que se realiza y sintetiza el analisis de clústeres de los datos preprocesados. 
4. Se ejecuta `4-factor_analysis.rmd` en el que se realiza y sintetiza el analisis de factores de los datos preprocesados. 
5. Se ejecuta `5-trends_analysis.rmd` este fichero supone un complemento al dashboard y a los ficheros anteriores, genera gráficos que se muestran en el Dashboard
6. Se ejecuta `6-APP.rmd` que genera el Dashboard final y reune toda la información extraída de los analisis. 

## Example
![Screenshot of the main page of the Dashboard](www/screenshot.png)
