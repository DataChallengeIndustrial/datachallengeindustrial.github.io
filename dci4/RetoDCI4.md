author: Horacio Tapia-McClung
summary: Reto-DCI4.0
id: Reto-DCI4
categories: codelab,markdown
environments: Web
status: Draft
feedback link: https://github.com/htapia/TallerPythonIntroCienciaDatos/

# Reto Data Challenge Industrial 4.0

## Introducción
Duration: 0:05:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

La pérdida de producto útil, o merma, se refiere a la materia procesada que por algun motivo debe deshecharse y no se incorpora al producto final. En esta ocasión tenemos un conjunto de datos que nos permite trazar la pérdida del producto a lo largo del proceso de manufactura. Esto es importante porque permite a la empresa estimar costos del producto final y mejorar la producción, entre otras cosas. La merma es un ejemplo macroscópico tangible del inevitable desgaste que ocurre en cualquier proceso natural o humano; una manifestación del proceso de transformacion de la energía.

El siguiente video muestra de manera general el proceso de manufactura con el que van a trabajar en ésta ocasión. Agradecemos a la empresa que nos ha proporcionado los datos para crear el reto. 

<img align="left" style="padding-right:10px;" src="figures/proinvel.png" width="300" height="200"><a href="https://youtu.be/fFjJRKGFD6g?t=21">Video </a>

## Descripción General del Reto
Duration: 0:03:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

Como parte del control de calidad de la producción, cada tres semanas se contabiliza la merma generada del proceso para asegurar que la pérdida no rebase el 2%, es decir la fracción de producto pérdido a producto total, cada tres semanas, no debe rebasar este porcentaje.

El reto consiste de los siguientes apartados:

1. Limpieza de datos general
2. Estadísticas descriptivas generales
3. Estadísticas descriptivas de la pérdida de producto
4. Modelo para la clasificación del tipo de merma


Cada apartado contiene dos secciones con preguntas que los guiaran en el desarrollo del Reto. La primera seccion contiene preguntas que seran evaluadas y miden las competencias de su equipo en el apartado correspondiente. La segunda seccion de preguntas son preguntas adicionales que se proponen para explorar mas el contenido de los datos y potenciar su solucion. 

## Descripción de los datos
Duration: 0:02:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">
En el proceso que estudirán hoy se considera merma a todo aquel material que forma parte del proceso pero no contribuye al producto final, incluyendo el que no puede recuperarse.

Les serán proporcionados tres archivos de datos:

* `extrusion.csv`
* `impresion.csv`
* `sellado.csv`

Cada uno contiene información sobre el proceso de manufactura, indicado por el nombre del archivo.

En las bases de datos disponibles en los archivos listados, la merma puede estar claramente especificada como **merma** o puede indicarse la pérdida de producto con términos como _recuperacion_ o como _basura_.
 

## Horario de entregables
Duration: 0:03:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

Los apartados se irán habilitando de acuerdo al siguiente horario:
<!--img align="right" style="padding-right:750px;" src="figures/schedule_smaller.jpg"-->

**Sabado 26**

Numero de apartado | Horario
------------------ | ------------------ 
1. Limpieza de datos general | 12:00
2. Estadísticas descriptivas generales | 13:30
3. Estadísticas descriptivas de la pérdida de producto | 15:30

**Domingo 27**

Numero de apartado | Second Header
------------------ | ------------------ 
4. Modelo para la clasificación del tipo de merma | 11:30
Entrega de presentaciones | 16:30


## Entregas y evaluaciones
Duration: 0:03:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

La entrega de avances se debe realizar a través de la carpeta personalizada de cada equipo, la misma donde hicieron entrega de su Reto Filtro durante el proceso de inscripción. El sistema de entrega permanecerá abierto de modo que los equipos puedan entregar sus propuestas aun cuando se han abierto otros apartados.

El formato de entrega es libre, pero es imperativo que se responda de manera justificada cada una de las preguntas que se van a evaluar en cada apartado. En cada entrega debe proporcionarse como mínimo lo siguiente:

* la respuesta justificada con análisis de datos de cada pregunta, y
* codigo ejecutable para reproducir el análisis que justifica cada respuesta.

Negative
: **Importante:** No se aceptará como válido código que deba compilarse. El código debe ser ejecutable y reproducible por el Comité si es necesario.

Positive
: Cada apartado será evaluado por el Comité Técnico y el Jurado de Expertos conforme sea recibido, tomando en cuenta el tiempo de retraso si lo hubiere

## Contacto con el Comité Organizador
Duration: 0:02:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

Positive
: **Importante:** El Comité Organizador estará disponibles vía el grupo privado de facebook para cualquier comunicación que se requiera establecer entre los participantes y el Comité. [El grupo privado Data Challenge Industrial 4.0 en Facebook puede accederse aquí.](https://www.facebook.com/groups/517979235705607)

Negative
: **Importante:** Ningún participante debe acercarse a la mesa del Comité Organizador a menos que haya sido solicitado por el Comité Organizador. Esto solo se hará vía el único canal de comunicación que es el grupo privado.


Positive
: **Importante:** Los datos estarán disponibles en las carpetas asignadas a cada equipo durante el proceso de inscripcion. Si tienen problemas para acceder a los datos, contacten al Comité a través del [grupo privado Data Challenge Industrial 4.0 en Facebook.](https://www.facebook.com/groups/517979235705607)

