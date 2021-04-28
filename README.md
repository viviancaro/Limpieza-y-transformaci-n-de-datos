# PROYECTO 2: LIMPIEZA Y TRANSFORMACIÓN DE DATOS
El objetivo de este proyecto es continuar con la limpieza de datos, aplicando diferentes técnicas para remover valores faltantes y outliers, También agregar nuevos atributos al DataFrame.
El proceso que se lleva acabo en este proyecto es:
-	Descripción de los atributos que serán analizados.
-	Importación de las bibliotecas necesarias para la exploración. Para este análisis se trabajará con Pandas, Numpy, Seaborn y MatplotLib.pylab.
-	Carga y lectura del dataset, ordenando las instancias por fecha de creación de las mismas.
### Outliers
-	Visualización gráfica por medio de "distplot" y “boxplot” de Seaborn sobre el atributo de interés, después de descartar los valores NaN de esta columna.
-	Análisis de los gráficos anteriores y confirmación de la presencia de valores extremos
-	Estimación de parámetros estadísticos.
-	Aplicación de la técnica del rango intercuartílico, calculo de valores mínimos y máximos.
-	Filtración y descarte de datos por fuera de los rangos establecidos.

### Valores Faltantes
-	Verificación de la existencia de valores nulos o faltantes en los atributos de interés.
-	Estudio porcentual sobre cantidad de instancias nulas, con el fin de evaluar si se eliminan o se corrigen para ser consideradas en el análisis.
-	Análisis de estrategias para atribuir los valores faltantes.
-	Aplicación de la clase Imputer de Scikit-learn sobre los atributos con valores faltantes, utilizando la media y la mediana como medidas.
### Variables Binarias
- Generación de variables binarias sobre variable categórica, utilizando LabelEncoder de Scikit-learn para convertirlas de tipo string a valores numéricos.
-	Creación de nuevo DataFrame con OneHotEnconder de Scikit-learn con las variables binarias creadas.
-	Visualización de la nueva matriz creada.
-	Unión de dos DataFrame relacionándolas con su índice con la herramienta Concat de Pandas.
-	implementación de función para la creación de un nuevo atributo, evitando posibles errores al aplicar operación matemática entre dos columnas.
-	Verificación de la existencia de valores faltantes después del procedimiento.
-	Conclusión del proyecto.
