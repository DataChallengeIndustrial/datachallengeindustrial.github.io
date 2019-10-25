author: Horacio Tapia-McClung
summary: Reto-DCI4.0
id: Reto-DCI-c
categories: codelab,markdown
environments: Web
status: Draft
feedback link: https://github.com/htapia/TallerPythonIntroCienciaDatos/

# Reto Data Challenge Industrial 4.0

## Introduccion
Duration: 0:02:00
<img align="left" style="padding-right:10px;" src="figures/header_small.png">

### Estadisticas descriptivas de la perdida de producto

Este apartado se enfoca en conocer mas sobre el producto que se reporta como perdida de algun tipo. Primero se busca extraer estadisticas generales de la merma, lo que requiere obtener informacion cruzada entre las bases de datos, y la despcripcion de las caracteristicas del producto que presenta merma de algun tipo.

Positive
: **Importante:** Para responder correctamente las respuestas de este apartado puede ser necesario limpiar y preprocesar las bases de datos para asegurar que cada valor tiene el tipo de variable correcto (texto, punto flotante, entero, fecha, etc.)

## Preguntas a evaluar
Duration: 0:28:00

Positive
: **Importante:** Recuerden que cada respuesta debe ser justificada plenamente y acompañada del código asociado a su respuesta. 

Negative
: **Importante:** Recuerden que no se aceptará como válido código que deba compilarse. El código debe ser ejecutable y reproducible por el Comité si es necesario.

1. Indicar que tablas y/o columnas de los datos disponibles podrian estar relacionadas con la merma o perdida del producto.

2. Partiendo de la base de datos de *SELLADO*, identificar los productos reportados con merma [^fn] en cada parte del proceso anterior al sellado:
 1. extrusion
 2. impresion
 3. sellado

3. Para cada uno de los productos identificados en el punto anterior (es decir con reportados con merma en alguna parte del proceso), determinar que  codigos tienen asociados en las columnas *CLAVE SAP*, *NOMBRE DEL PEDIDO* y *N^o\[Degree] DE PEDIDO*. Indicar cuales usar para identificar inequivocamente los mismos en cada una de las otras bases de datos. 

4. De los codigos que registran merma positiva en la base de *SELLADO*, cuantos y cuales se pueden encontrar en la base de *IMPRESION*. 

5. Que significado tiene que estos codigos coinciden entre las dos bases?

6. De los codigos que registran merma positiva en la base de *SELLADO*, cuantos y cuales se pueden encontrar en la base de *EXTRUSION*

7. Estos codigos, internos de la empresa, identifican el producto que se manufactura. Que significado tiene que estos codigos coinciden entre las bases?  

8. Los productos que en la base de datos *SELLADO* presentan merma positiva y que tambien se encuentran en *EXTRUSION* tienen asociados, entre otros atributos, operadores y responsables _en ambas bases de datos_. Que _operadores_ son los mas comunes en este subconjunto de la base de datos de *EXTRUSION*.

9. Los productos que en la base de datos *SELLADO* presentan merma positiva y que tambien se encuentran en *IMPRESION* tienen asociados, entre otros atributos, operadores y responsables _en ambas bases de datos_. Que _operadores_ son los mas comunes en este subconjunto de la base de datos de *IMPRESION*.

10. Los productos que en la base de datos *SELLADO* presentan merma positiva y que tambien se encuentran en *IMPRESION* tienen asociados tambien tiempo: semana, turno, hora de inicio, hora final, etc. Como se reparte el producto con merma localizada en sellado que se identifica en impresion, en cada uno de estos periodos de tiempo.

11. Los productos que en la base de datos *SELLADO* presentan merma positiva y que tambien se encuentran en *EXTRUSION* tienen asociados tambien tiempo: semana, turno, hora de inicio, hora final, etc. Como se reparte el producto con merma localizada en sellado que se identifica en extrusion, en cada uno de estos periodos de tiempo.

[^fn]: Merma con valores positivos registrados.

## Preguntas adicionales sugeridas
Duration: 0:30:00

12. En la base de datos *EXTRUSION* el producto perdido _en esta parte del proceso_ se indica como recuperado y basura. Cual es el total de producto perdido en esta parte del proceso por turno, por semana, por dia de la semana, por cada dos semanas, por mes y por trimestres. Como se distribuye a lo largo del periodo disponible en las horas del dia? [^fn1].

13. En la base de datos *IMPRESION* el producto perdido _en esta parte del proceso_ se indica como recuperado. Cual es el total de producto perdido en esta parte del proceso por turno, por semana, por dia de la semana, por cada dos semanas, por mes y por trimestres. Como se distribuye a lo largo del periodo disponible en las horas del dia? [^fn1].

[^fn1]: Hay tres turnos de ocho horas, comenzando a las 6:00am los dias lunes y terminando a las 06:00 am los domingos.
