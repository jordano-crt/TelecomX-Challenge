# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

## 📌 Descripción
Este proyecto tiene como objetivo analizar los factores que influyen en la **evasión de clientes** (Churn) en la empresa ficticia **Telecom X**.  
A través de técnicas de **ETL (Extracción, Transformación y Carga)**, **Análisis Exploratorio de Datos (EDA)** y visualizaciones, se identifican patrones y tendencias que podrían ayudar a reducir la tasa de cancelaciones.

El análisis se realiza con **Python** utilizando bibliotecas como `pandas`, `numpy`, `matplotlib` y `seaborn`.

---

## 🎯 Objetivos
- Identificar las variables más relevantes que afectan la cancelación de clientes.
- Limpiar y transformar los datos para su correcto análisis.
- Visualizar patrones y relaciones entre variables.
- Generar conclusiones y recomendaciones estratégicas para reducir el Churn.

---

## ⚙️ Instalación y Dependencias
Este proyecto utiliza Python 3.11+ y las siguientes bibliotecas:

```bash
pip install pandas numpy matplotlib seaborn
```
## 🚀 Clona este repositorio
git clone [https://github.com/usuario/TelecomX_Churn_Analysis.git](https://github.com/jordano-crt/TelecomX-Challenge/edit/main/README.md)

## ⚠️ Posibles Problemas
Datos con valores nulos o inconsistentes que requieren limpieza antes del análisis.

Columnas categóricas deben ser codificadas antes de aplicar modelos predictivos.

Los resultados dependen de la calidad y representatividad de los datos.

## Diccionario de datos
extraido( https://github.com/ingridcristh/challenge2-data-science-LATAM/blob/main/TelecomX_diccionario.md#diccionario-de-datos)
Diccionario de datos
customerID: número de identificación único de cada cliente
Churn: si el cliente dejó o no la empresa
gender: género (masculino y femenino)
SeniorCitizen: información sobre si un cliente tiene o no una edad igual o mayor a 65 años
Partner: si el cliente tiene o no una pareja
Dependents: si el cliente tiene o no dependientes
tenure: meses de contrato del cliente
PhoneService: suscripción al servicio telefónico
MultipleLines: suscripción a más de una línea telefónica
InternetService: suscripción a un proveedor de internet
OnlineSecurity: suscripción adicional de seguridad en línea
OnlineBackup: suscripción adicional de respaldo en línea
DeviceProtection: suscripción adicional de protección del dispositivo
TechSupport: suscripción adicional de soporte técnico, menor tiempo de espera
StreamingTV: suscripción de televisión por cable
StreamingMovies: suscripción de streaming de películas
Contract: tipo de contrato
PaperlessBilling: si el cliente prefiere recibir la factura en línea
PaymentMethod: forma de pago
Charges.Monthly: total de todos los servicios del cliente por mes
Charges.Total: total gastado por el cliente
