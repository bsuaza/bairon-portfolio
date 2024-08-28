# Proyecto de Limpieza de Datos

## Descripción

Este proyecto tiene como objetivo demostrar técnicas básicas de limpieza de datos utilizando una base de datos ficticia de empleados. Se abordan problemas comunes como valores nulos, datos inconsistentes, y entradas erróneas. El propósito de este proyecto es preparar los datos para su análisis posterior y asegurar que la información sea precisa y confiable.

## Estructura del Proyecto

El proyecto está estructurado de la siguiente manera:

- **data_cleaning_project.ipynb:** Este es el notebook principal en Google Colab donde se realiza todo el proceso de limpieza de datos.
- **empleados_limpios.csv:** El archivo CSV resultante que contiene los datos después del proceso de limpieza.

## Pasos Realizados

1. **Importación de Bibliotecas:**
   - Se importaron las bibliotecas necesarias para la manipulación y análisis de datos (`Pandas`, `NumPy`).

2. **Creación del DataFrame:**
   - Se generó un DataFrame con datos ficticios que simulan un conjunto de datos de empleados.

3. **Limpieza de Datos:**
   - **Manejo de valores nulos:** 
     - Se eliminaron filas con nombres faltantes.
     - Se rellenaron valores nulos en las columnas de `Edad` y `Salario` con la mediana y el promedio, respectivamente.
     - Se asignó "Sin Asignar" a los valores nulos en la columna de `Departamento`.
   - **Normalización de Datos:**
     - Se aseguraron valores consistentes en las columnas categóricas.
   
4. **Exportación de Datos:**
   - Los datos limpios se exportaron a un archivo CSV para su uso posterior.

## Tecnologías Utilizadas

- **Python:** Para el análisis y manipulación de datos.
- **Pandas:** Para la creación y limpieza de DataFrames.
- **NumPy:** Para cálculos numéricos.
- **Google Colab:** Como entorno de desarrollo para escribir y ejecutar el código.

## Cómo Usar Este Proyecto

1. **Clonar el Repositorio:**
   - Clona este repositorio en tu máquina local utilizando el siguiente comando:
     ```bash
     git clone https://github.com/tu-usuario/tu-repositorio.git
     ```

2. **Abrir el Notebook:**
   - Abre el archivo `data_cleaning_project.ipynb` en Google Colab o en Jupyter Notebook.

3. **Ejecutar el Código:**
   - Sigue las instrucciones dentro del notebook para replicar el proceso de limpieza de datos.

## Resultados

El proyecto produce un conjunto de datos limpio y estructurado que está listo para análisis o modelado predictivo. Los datos se guardan en el archivo `empleados_limpios.csv`.

## Contacto

Si tienes alguna pregunta o sugerencia sobre este proyecto, no dudes en contactarme:

- **Correo:** suazabairon@gmail.com
- **LinkedIn:** [Perfil de LinkedIn](https://www.linkedin.com/in/tu-perfil)
