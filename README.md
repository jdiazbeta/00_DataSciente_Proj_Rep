<h1 align="center">Comparaciones básicas de alojamientos en Seattle y Boston</h1>

## Table of contents

- [Descripción e Instalaciones](#Desc-inst)
- [Motivación](#Motivación)
- [Descripción de los archivos](#Desc-files)
- [Interactuando con el proyecto](#Interact)


## Descripción e Instalaciones
El código se encuentra ambientado en el lenguaje de programación Python. Se presenta la capacidad de ser ejecutable tanto en la plataforma de colab como en un cuaderno Jupyter.

Para su correcta ejecución se deben tener instalados los siguientes módulos:
- numpy
- pandas
- matplotlib
- sklearn
- seaborn
- Version de Python: 3.10.12

## Motivación
Por motivos de intercambio, motivos laborales o netamente ocio y querer descansar y conocer lugares, es importante pensar en el lugar donde se pasará la noche. Los anfitriones, dueños de dichos hospedajes por tanto se interesan en este detalle en pro de poder tener huespedes.

De cara al anfitrión una de las principales preguntas sería ¿Cuales son las características que mas valoran los huespedes para sentirse comodos en un alojamiento? ¿Como puedo mejorar la experiencia de los huespedes en pro de ganar confianza para que el hospedaje acoja cada vez mas?

De cara al huesped la pregunta puede radicar en que factores pueden ser potenciales para un aumento en el valor de un hospedaje.

Personalmente no suelo viajar mucho, por ende no conozco mucho el tema pero es de particular interés dado que entender desde ahora este tipo de comportamientos apalancará futuras decisiones en cuanto a vacaciones, viajes de negocio u oportunidades de estudio. Esto mas la curiosidad que generá esta labor en pro de poder apoyar en la entrega de herramientas e insights que permitan mejorar dichos servicios.

## Descripción de los archivos
En cuanto a bases de datos, en el repositorio se podrán encontrar:
- [listings.csv](listings.csv) Contiene información referente a descripciones de alojamientos de Seattle, así como descripciones de la experiencia y calificaciónes de los huespedes, entre otros aspectos de interés. La información fue recolectada de la plataforma [Kaggle](https://www.kaggle.com/datasets/airbnb/seattle/data).
- [listings_BOS.csv](listings_BOS.csv) Contiene información referente a descripciones de alojamientos de Boston, así como descripciones de la experiencia y calificaciónes de los huespedes, entre otros aspectos de interés. La información fue recolectada de la plataforma [Kaggle](https://www.kaggle.com/datasets/airbnb/boston).

En cuanto a código, el archivo [Project_1_Airborn_SyB.ipynb](https://github.com/jdiazbeta/00_DataSciente_Proj_Rep/blob/a5484dc4ed7933d70d13f0edaa3afb6f213d9cad/Project_1_Airborn_SyB.ipynb) contiene el código realziado para llevar a cabo el análisis. 

## Interactuando con el proyecto
El proyecto esta pensado para dar un primer bosquejo en cuanto a un gran proyecto que permita dar a entender, bajo la perspectiva de huesped como de anfitrión, las principales características a la hora de escoger alojamiento que van desde el precio, sus características e incluso potenciales mejoras dada su ubicación geográfica. 

Este cuaderno puede descargarse para trabajar de manera local o desde google colab.

Se emplean técnicas basicas de imputación de datos, así como un muy breve análisis descriptivo - exploratorio. Así mismo, se usa la librería de Skit-Learn para crear un modelo de regresión lineal multiple para entender las potenciales variables que impactan significativamente al precio de alojamiento.

A corte de Julio 8 de 2024 el código es funcional, y muy disponible para uso y mejora, esta apenas es la primer versión, realizada a modo de exploración inicial. Invito a mejorarlo para futuros trabajos brindando nuevas perspectivas , desde la depuración y análisis descriptivos hasta modelos que resulten de interés.















