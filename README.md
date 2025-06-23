Telecom X: Análisis de Evasión de Clientes
Sobre este Proyecto
Este proyecto es un análisis exploratorio de datos (EDA) para entender por qué los clientes de Telecom X cancelan sus servicios (churn). El objetivo es limpiar y preparar los datos, y encontrar información útil que pueda ayudar a reducir la evasión de clientes.

Archivos en este Repositorio
TelecomX_Data.json: El archivo original con los datos de los clientes.
challenge_telecom_x.ipynb: El notebook de Jupyter/Colab con el código de análisis.
README.md: Este documento.
Observaciones Clave
Algunos puntos importantes encontrados en el análisis son:

Los contratos mes a mes se asocian con más evasión.
Los clientes con menos tiempo con la empresa tienden a irse más.
El tipo de servicio de internet, como la fibra óptica, puede influir en la decisión de irse.
Ciertos cargos mensuales y la falta de servicios adicionales también pueden estar relacionados con la evasión.
Cómo Ejecutar el Análisis
Para ver y ejecutar el análisis:

Con Google Colab (Recomendado)
Abre Google Colab.
Sube el archivo TelecomX_Data.json a la sesión de Colab.
Copia el contenido del notebook challenge_telecom_x.ipynb en una nueva celda y ejecútala.
En tu Computadora (Jupyter/Python)
Descarga todos los archivos de este repositorio.
Asegúrate de que TelecomX_Data.json esté en la misma carpeta que challenge_telecom_x.ipynb.
Instala las librerías necesarias: pandas, numpy, matplotlib, seaborn. Puedes usar pip install pandas numpy matplotlib seaborn.
Abre el notebook challenge_telecom_x.ipynb con Jupyter Notebook y ejecuta las celdas.
