# Autores
Daniel Alejandro Molina Yepes - 1128442271
Dorian Alexander Jaramillo - 1128442271

# Forecasting On Power Consumption Of Tetouan City

La energía juega un papel trascendental en la economía de un país; por tanto, la predicción del consumo de energía se convierte en un
problema de vital importancia para la toma de decisiones con el fin de cubrir la demanda requerida para un tiempo o temporada específica.

El presente proyecto tiene como objetivo principal el desarrollo de un modelo de predicción de consumo de energía eléctrica en la ciudad de Tetouan, Marruecos, con el fin de predecir el consumo de energía en un intervalo de 24 horas y así poder tomar decisiones con respecto a la generación de energía eléctrica.

En este trabajo se analiza la base de datos [Power consumption of Tetouan city Data Set](https://archive.ics.uci.edu/ml/datasets/Power+consumption+of+Tetouan+city), tratándose de
un problema de regresión se utilizaran los siguientes modelos: 
- Redes neuronales
- Regresión múltiple
- Random Forest
- Ventana de parzen 
- Máquinas de soporte vectorial

Los modelos serán aplicados variando
algunos parámetros y seleccionando aquel para el cual se obtengan los mejores resultados.

## Artículo
En el siguiente enlace podrás  acceder al [artículo](https://raw.githubusercontent.com/programanime/modelos2_power_consumption_tetouan_city/main/Entrega_II_-_Power_consumption_of_Tetouan_city.pdf) de investigación de este proyecto, donde se presentan los resultados de aplicar cada uno de los modelos de Machine Learning.

## Colab
En el siguiente Colab podrás acceder a la [implementación](https://colab.research.google.com/github/programanime/modelos2_power_consumption_tetouan_city/blob/main/Entrega_II_Power_consumption_of_Tetouan_city.ipynb) de este proyecto, donde se realiza un EDA seguido de un entrenamiento para cada uno de los algoritmos de Machine Learning mencionados previamente.

## Instrucciones Colab
1. Abrir el siguiente enlace [Colab](https://colab.research.google.com/github/programanime/modelos2_power_consumption_tetouan_city/blob/main/Entrega_II_Power_consumption_of_Tetouan_city.ipynb)
2. Clic en Runtime -> Run All

> Nota: puede tomar mucho tiempo en correr y en ocasiones puede que se caiga el entorno de ejecución.

## Instrucciones para ejecutarlo en tu maquina
1. Instalar Python3, Git, Visual Studio Code y la extensión de Jupyter para Visual Studio Code
4. clonar el repositorio
```shell
git clone https://github.com/programanime/modelos2_power_consumption_tetouan_city.git
```
2. Instalar las dependencias
```shell
pip install -r requirements.txt
```
3. Abrir el archivo `Entrega_II_Power_consumption_of_Tetouan_city.ipynb` con Visual Studio Code
4. Hacer click en "Run All"