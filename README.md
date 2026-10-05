# Análisis experimental y teórico de deflexión en viga

Este repositorio contiene los datos, análisis y el documento final correspondientes al análisis de deformaciones en un elemento estructural sometido a flexión.

El proyecto está diseñado para que cualquier persona ajena al trabajo pueda reconstruir los resultados siguiendo la estructura de los archivos disponibles.

## 1. Estructura del Repositorio

El proyecto está organizado en las siguientes carpetas:

* **`data/`**: Contiene los datos originales y parámetros.
  * `datos_viga.csv`: Datos experimentales de carga y deflexión.
  * `parametros_viga.xlsx`: Parámetros geométricos y mecánicos iniciales.
  * `esquema_viga.png`: Imagen del esquema de la viga.
* **`analysis/`**: Contiene el archivo de cálculo `analisis_viga.xlsx`, donde se calculó la inercia, la deflexión teórica y la diferencia relativa, además de incluir el desarrollo para generar el gráfico carga v/s deflexión.
* **`figures/`**: Contiene los gráficos generados.
  * `gráfico carga vs deflexión.png`: Gráfico comparativo de los resultados.
* **`report/`**: Contiene los archivos finales del documento.
  * `Nota_técnica..pdf`: Versión final compilada de la nota técnica.
  * `Nota_técnica.zip`: Archivo comprimido con el proyecto completo en LaTeX.
* **``declaracion_ia.md/`**: Declaración formal sobre el uso de herramientas de Inteligencia Artificial (

## 2. Fuentes de Datos (Inputs)
Los parámetros iniciales y las mediciones experimentales se encuentran en la carpeta `data/`. El archivo `datos_viga.csv` contiene los registros ordenados de carga y deflexión, mientras que `parametros_viga.xlsx` contiene las propiedades de la viga.

## 3. Transformaciones y Procesamiento
Los datos fueron procesados de la siguiente manera:
1. **Cálculos:** En el archivo `analisis_viga.xlsx` (ubicado en la carpeta `analysis/`) se procesaron los datos crudos para calcular la inercia, la deflexión teórica y las diferencias relativas, también se encuentra el gráfico carga v/s deflexión. Adicionalmente, se integraron datos de verificación.
2. **Generación de gráficos:** Se generó el archivo `gráfico carga vs deflexión.png` a partir de los datos procesados, almacenado en `figures/`.

## 4. Salidas Esperadas (Outputs)
El resultado final consolidado es la nota técnica en formato PDF.
* **Ubicación:** `report/Nota_técnica..pdf`.

## 5. Instrucciones de Reproducción
Para compilar o revisar el documento original:
1. Descarga y extrae el archivo `report/Nota_técnica.zip`, el cual contiene el proyecto en LaTeX.
2. Utiliza un entorno LaTeX (como Overleaf, TeX Live o MiKTeX) para compilar los archivos fuente extraídos.
3. Para revisar los cálculos, abre `analysis/analisis_viga.xlsx` donde se encuentran las fórmulas aplicadas.

## Autores
* **Gabriela Soto**
* 
