# Trabajo Práctico 7 - Análisis de Datos en la Nube  

## Descripción

Análisis de 64,651 transacciones del caso de corrupción de las Tarjetas Black de Caja Madrid (2003-2012), donde 86 directivos gastaron aproximadamente 15.5 millones de euros en fondos públicos. El proyecto utiliza Apache Spark en Databricks para procesamiento distribuido, análisis exploratorio, transformaciones complejas, y persistencia con Delta Lake.

## Dataset

**Fuente:** 
- Dataset Github:
https://github.com/rafadelascuevas/limpieza-analisis-basico/tree/master/datasets/
hoja_calculo_tarjetas_black/03_csv_para_limpiar
- Audiencia Nacional. (2017). Sentencia del Caso Tarjetas Black - Procedimiento
Abreviado
- 63/2013. Tribunal Penal, Sección Segunda. Madrid, España.
- El País. (2014-2017). Especial: El Caso de las Tarjetas Black:
https://elpais.com/especiales/2014/tarjetas-opacas-caja-madrid/

**Características:**
- 64,651 transacciones originales
- Período: 2003-2012
- 9 columnas

**Plataforma:**
- Databricks Free Edition
- Unity Catalog para gobernanza de datos
- Apache Spark para procesamiento distribuido

**Lenguajes y Frameworks:**
- Python 3.11
- PySpark (Spark SQL, DataFrames API)
- Delta Lake para almacenamiento ACID

**Librerías de Análisis y Visualización:**
- Pandas para manipulación de datos
- NumPy para operaciones numéricas
- Matplotlib para visualizaciones base
- Seaborn para gráficos estadísticos

## Ejecución

Este proyecto fue desarrollado en Databricks Free Edition. Para replicar:

1. Crear cuenta en Databricks Community Edition
2. Importar notebooks desde carpeta `notebooks/`
3. Configurar Unity Catalog con catálogo `workspace` y schema `transactions`
4. Subir dataset CSV a Volume en Unity Catalog
5. Ejecutar notebook `TP_Transacciones_Databricks.ipynb`

---

## Autor
Saldeña, Silva, Chavez, Moya - Estudiantes de Desarrollo de Software
ITU - Universidad Nacional de Cuyo
