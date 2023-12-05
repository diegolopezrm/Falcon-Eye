# Falcon-Eye---Reconocimiento-de-voz

![image](https://github.com/diegolopezrm/Falcon-Eye/assets/63005462/ace577f6-49b2-4c30-b7b9-973bfb039c4f)

## Authors

Diego Alejandro Lopez Camacho - 2200162 

Gabriel Fernando Reyes Guevara - 2200141 

## RESUMEN
Este proyecto se enfoca en el desarrollo de un avanzado sistema de reconocimiento de características en archivos de audio mediante el uso de Inteligencia Artificial, específicamente Redes Convolucionales (CNN). Utilizando un dataset proporcionado por Mozilla, nuestro objetivo es entrenar una CNN que tenga la capacidad de identificar y clasificar diversas características en archivos de audio, tales como el género (hombre o mujer), la edad, y posiblemente otras características relevantes.

| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0001.jpg"> blah |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0002.jpg">|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0003.jpg">|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0004.jpg">  |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0005.jpg">|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0006.jpg">|
|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0007.jpg">  |  <img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0008.jpg">|<img width="1604" alt="screen shot 2017-08-07 at 12 18 15 pm" src="/Power Your Virtual Presentation Skills (1)_page-0009.jpg">|



## Objetivo

- Recopilación y Preprocesamiento de Datos:

Recopilar un dataset exhaustivo de archivos de audio proporcionado por Mozilla.
Realizar tareas de preprocesamiento para garantizar la calidad y uniformidad de los datos, como la normalización del audio y la extracción de características relevantes.
- Entrenamiento de la Red Convolucional(CNN):

Diseñar y entrenar una CNN utilizando técnicas de aprendizaje profundo y convolucion para reconocer patrones complejos en los archivos de audio.
Implementar algoritmos de optimización para mejorar la precisión y eficiencia del modelo.
- Clasificación de Características:

Desarrollar algoritmos de clasificación que permitan identificar el género (hombre/mujer) y estimar la edad en base a los patrones de audio identificados por la CNN.
Explorar posibles características adicionales, como el tono de voz, el estado emocional, etc., y clasificarlas adecuadamente.
- Evaluación y Validación del Modelo:
Realizar pruebas de validación cruzada para asegurar la generalización del modelo a datos no vistos.


## Dataset

Mozilla Common Voice es un proyecto de código abierto que busca hacer la tecnología de voz más inclusiva. Los colaboradores donan datos de voz a un conjunto de datos público, que cualquiera puede usar para entrenar tecnologías habilitadas para la voz. El objetivo es ayudar a enseñar a las máquinas cómo hablan las personas reales, en diferentes idiomas, acentos y edades

El conjunto de datos de Mozilla Common Voice tiene las siguientes características como dataset:

* Es el más grande de su tipo en el dominio público, con más de 29 mil horas de voz en 87 idiomas.
* Es de código abierto y tiene una licencia CC-0, lo que significa que cualquiera puede usarlo, modificarlo y compartirlo sin restricciones.
* Incluye metadatos demográficos como edad, sexo y acento de los colaboradores, que pueden ayudar a entrenar la precisión de las tecnologías de reconocimiento de voz.
* Está compuesto por voces reales de personas de todo el mundo, que reflejan la diversidad y la riqueza de las lenguas humanas.
* Se actualiza periódicamente con nuevas voces y lenguas, y ofrece segmentos delta que contienen los clips más recientes desde el último lanzamiento.

[COMMONVOICE](https://commonvoice.mozilla.org/es/datasets)


## Modelos
Se extrajeron diversas características de archivos de audio para el entrenamiento del modelo. Estas características incluyen: 
* los coeficientes cepstrales de frecuencia mel (MFCCs)
* el croma
* el espectrograma mel
* el contraste espectral
* el tonnetz.

Los MFCCs capturan la información espectral, el croma representa la distribución de energía tonal, el espectrograma mel describe la energía en diferentes frecuencias, el contraste espectral refleja la variación de energía y el tonnetz representa las relaciones tonales. Estas características son fundamentales para caracterizar la información acústica y fueron ser utilizadas como entrada para entrenar el modelo de aprendizaje automático, en tareas relacionadas con la clasificación de género y edad en archivos de audio.

[MODELO ENTRENADO EDADES](https://drive.google.com/file/d/1lNhk74Fb65KmsaYlPWvWo34CcSz2gC1m/view?usp=sharing)

[MODELO ENTRENADO GENERO](https://drive.google.com/file/d/14-IsPoxgwo11bmzOcXbUr-qpSwIrZ7on/view?usp=drive_link)

## Enlaces

[NOTEBOOK](https://colab.research.google.com/drive/1DUh43dANb9zn_KbFFux8wkHqjvaxM75N?usp=sharing)



