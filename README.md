# Limpieza-de-Datos

**Hecho por:** Sofía Quiroz Valencia 

El presente trabajo tiene como objetivo realizar un proceso de limpieza y preparación de datos (data cleaning) sobre el dataset **“Womens Clothing E-Commerce Reviews”**, el cual contiene reseñas de clientes sobre ropa de mujer recopiladas de una tienda en línea.

El análisis busca identificar problemas comunes en los datos como valores faltantes, duplicados, inconsistencias o ruido textual y aplicar las transformaciones necesarias para obtener un conjunto de datos más limpio, coherente y listo para análisis exploratorios o modelos de machine learning.

**Paso a paso del proceso realizado**

1. Importación del dataset

   Se importó el archivo CSV ubicado en la ruta local, Utilizando la librería pandas, se cargó el dataset y se revisaron sus dimensiones y primeras filas para conocer su estructura.

2. Análisis inicial de los datos

    Se identificaron las columnas, los tipos de datos y la cantidad de valores nulos. Esto permitió reconocer que algunas columnas, como “Title” y “Review Text”, contenían valores faltantes     o incompletos.

3. Identificación y corrección de 5 problemáticas

   - Valores nulos en texto y columnas con más del 50% de datos faltantes.

   - Registros duplicados

   - Valores fuera de rango (por ejemplo, edades o ratings inválidos)

   - Ruido en los textos (mayúsculas, símbolos, puntuación)

   - Inconsistencias en categorías (nombres con errores o mayúsculas variables)

4. Limpieza aplicada
 
   A lo largo del Notebook se aplicaron transformaciones con Python para depurar los datos.
