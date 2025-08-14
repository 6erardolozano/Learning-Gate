Reto | Análisis del progreso mundial de vacunación
a. Extraer la información del archivo. 
b. Mostrar la estructura y tipos de datos de cada columna para identificar qué operaciones puedes realizar con cada una de ellas, asegurándote que las columnas con fechas sean del tipo datetime64. 
c. Determinar la cantidad de vacunas aplicadas de cada compañía (con base en cómo lo reporta cada país en la columna vaccines, en otras palabras, agrupe por vaccines y realice la sumatoria). 
d. Obtener la cantidad de vacunas aplicadas en todo el mundo. 
e. Calcular el promedio de vacunas aplicadas por país. 
f. Determinar la cantidad de vacunas aplicadas el día 29/01/21 en todo el mundo. 
g. Crear un dataframe nuevo denominado conDiferencias que contenga los datos originales y una columna derivada (diferencias) con las diferencias de aplicación entre las columnas daily_vaccionations y daily_vaccionations_raw.  
h. Obtener el periodo de tiempo entre el registro con fecha más reciente y el registro con fecha más antigua. 
i. Crear un dataframe nuevo denominado conCantidad que contenga los datos originales y una columna derivada (canVac) con la cantidad de vacunas utilizadas cada día (usar la columna vaccines y separar por el carácter , ). 
j. Generar un dataframe denominado antes20 con todos los registros que se hayan realizado antes del 20 de diciembre de 2020. 
k. Obtener un dataframe denominado pfizer con todos los registros donde se haya utilizado la vacuna Pfizer. 
l. Almacenar los dataframes generados (conDiferencias, conCantidad, antes20 y pfizer) en un archivo de Excel denominado resultadosReto.xlsx, donde cada dataframe ocupe una hoja diferente. Se recomienda ver la documentación de pd.ExcelWriter. 
