# Desafío TelecomX_II

## Análisis Predictivo de la Rotación de Clientes

Este repositorio contiene la solución al desafío de Telecom X, centrado en el análisis predictivo de la rotación de clientes, utilizando técnicas de aprendizaje automático para identificar los factores que conducen a la cancelación del servicio.

## 🎯 Objetivo

Telecom X se enfrenta a una alta tasa de rotación de clientes y busca:

Recopilar, procesar y preparar los datos de los clientes.

Analizar y explorar los datos para comprender su comportamiento.

Desarrollar modelos predictivos para identificar a los clientes con mayor riesgo de rotación.

Aportar información estratégica para reducir la rotación y mejorar la retención.


## 🧹 Limpieza y Tratamiento de Datos

Principales pasos realizados:

✅ Importación y tratamiento de datos, incluyendo la transformación de variables categóricas y numéricas.

✅ Eliminación de valores faltantes y estandarización de datos.

✅ Análisis de correlación para seleccionar y excluir variables redundantes.

✅ Preparación de datos para el modelado predictivo.

## 🔍 Análisis Exploratorio y Modelado Predictivo

Tasa de abandono: aproximadamente el 25,8 % de los clientes cancelaron sus servicios.

Modelos probados: Regresión Logística, Bosque Aleatorio y Modelo Aleatorio.

Mejor modelo: Regresión Logística, con una precisión del 79,96 %, una exactitud del 65,44 %, una tasa de recuperación del 52,14 % y una puntuación F1 del 58,04 %.

Variables más relevantes para la predicción:
Duración del contrato (los clientes con contratos más cortos tienen mayor riesgo)

Valor mensual (los valores más altos se correlacionan con el abandono)

Servicios adicionales como la seguridad en línea y las copias de seguridad también influyen.

## ✅ Recomendaciones Estratégicas

Desarrollar iniciativas de retención personalizadas para clientes con contratos cortos y valores mensuales altos.

Ofrecer paquetes promocionales y descuentos progresivos para aumentar la fidelización.

Utilizar el modelo de Regresión Logística para la monitorización continua, lo que permite intervenciones proactivas para los clientes con mayor riesgo de abandono.


## 🔧 Tecnologías y herramientas
Python 3.10+

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Google Colab / VSCode

## ✍️ Autor

Proyecto realizado por Miguel Angel Escurra como parte del reto de análisis de datos en el sector de las telecomunicaciones dado por Alura.
