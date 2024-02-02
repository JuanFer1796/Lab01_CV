# Vision por Computadora 2024 - Lab 1

Este repositorio contiene los resultados del Laboratorio 1 de Visión por Computadora, realizado el 01 de febrero de 2024.

## Contenido del Repositorio

### 1. Operador Hit or Miss

En la sección 9.4 del libro "Digital Image Processing" de González y Woods, se explica el operador Hit or Miss. Este operador se construye a partir de operaciones básicas como dilatación, erosión, opening, closing y diferencia. A continuación, se presenta un ejemplo con una imagen binaria para demostrar cómo el operador Hit or Miss detecta la ubicación de objetos específicos.

- [Ejemplo_Hit_or_Miss.ipynb](1_Operador_Hit_or_Miss/Ejemplo_Hit_or_Miss.ipynb)

### 2. Transformaciones Morfológicas en Imagen de Huella Digital

Se invierte y binariza la imagen `fingerprint.jpeg`, seguido de la aplicación de transformaciones morfológicas para remover y restaurar la imagen.

- [Transformaciones_Huella_Digital.ipynb](2_Transformaciones_Huella_Digital/Transformaciones_Huella_Digital.ipynb)

### 3. Operaciones Morfológicas en Imágenes en Escala de Grises

Se aplican diversas operaciones morfológicas a las imágenes en escala de grises: `butterfly.jpeg`, `quetzalgris.png`, `chestXray.jpeg`. Se explora el efecto de dilatación, erosión, opening, closing y white top-hat en estas imágenes.

- [Operaciones_Morfologicas_Grises.ipynb](3_Operaciones_Morfologicas_Grises/Operaciones_Morfologicas_Grises.ipynb)

### 4. Filtrado Secuencial en Imagen con Ruido

Se busca una imagen en grises con ruido, y se aplica un filtrado secuencial utilizando openings y closings con diferentes elementos estructurantes. Se comparan los resultados obtenidos para evaluar el efecto resultante.

- [Filtrado_Secuencial_Ruido.ipynb](4_Filtrado_Secuencial_Ruido/Filtrado_Secuencial_Ruido.ipynb)

### 5. Gradiente Morfológico en Imagen de Tomografía Cerebral

Se obtiene el gradiente morfológico de la imagen `brain-scan.jpeg` y se explica el resultado. Se sugiere experimentar con otras imágenes en escala de grises para comprender el efecto de esta operación.

- [Gradiente_Morfologico.ipynb](5_Gradiente_Morfologico/Gradiente_Morfologico.ipynb)

### 6. Conteo de Granos de Arroz en Imagen de Arroz

Se trabaja con la imagen `rice.jpg`, binarizándola y aplicando un algoritmo de componentes conexas para contar los granos de arroz en la imagen.

- [Conteo_Granos_Arroz.ipynb](6_Conteo_Granos_Arroz/Conteo_Granos_Arroz.ipynb)

### 7. Análisis de Imagen Microscópica

Se realizan diferentes pasos en la imagen `microscope.png`, como binarización, obtención de la componente conexa de menor tamaño, recorte de la componente conexa más grande y aplicación de operaciones morfológicas para contar el número de células.

- [Analisis_Imagen_Microscopica.ipynb](7_Analisis_Imagen_Microscopica/Analisis_Imagen_Microscopica.ipynb)

### 8. Resultados Específicos

Se presentan cuatro resultados específicos (a)-(d) con las imágenes correspondientes, y se determina el elemento estructurante y la operación morfológica necesarios para obtener cada resultado.

- [Resultados_Especificos.ipynb](8_Resultados_Especificos/Resultados_Especificos.ipynb)

## Instrucciones de Uso

Cada carpeta contiene un archivo de Jupyter Notebook que detalla el análisis y los resultados para cada parte del laboratorio. Los archivos pueden ejecutarse en entornos de Jupyter Notebook.

¡Gracias por revisar el laboratorio! Si tienes alguna pregunta, no dudes en contactarme.
