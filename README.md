# Tus Finanzas


## Introducción 

En la actualidad, dentro del sector de servicios financieros, la revolución digtale ha brindado oportunidades en mercados de todos los tamaños para desbloquear interesantes beneficios económicos a través de la expansión. En consecuencia, el aumento de la adopción de aplicaciones innovadoras, que se les conoce en la industria como "fintech", representa la estrategia para mnatenerse competitivos entre bancos y fidelizar a sus clientes con alta efectividad.  


## Contexto

Un banco decidió lanzar una nueva aplicación móvil al mercado para que sus usuarios puedan administar sus gastos, visualizar sus movimientos mensuales y fomentar el ahorro. Luego de un periódo de 6 meses meses en el mercado y algo de tracción, el project manager nos brindó una data para responder 2 preguntas: 
1. ¿Es conveniente duplicar la inversión en publicidad (facebook ads)?
2. ¿Qué se podría rediseñar de la aplicación para optimizarla? 

Para lo cual nos proporcionaron la siguiente carpeta:       
[Carpeta de Data](https://drive.google.com/open?id=1gV6PwrT6SZigVTJ67q8W-dFzGTLePUyK)


## Objetivos del Proyecto   

- Rediseñar un producto ya existente.
- Analizar data 
- User testing
- Diseño de componentes de la interfaz                                                                                                                                     

## Implementación

Para poder llevar a cabo nuestra investigación se realizó lo siguiente:

|Actividad|Descripción|Puntos|
|:----|:---|:---:|
|Entrevistas con cliente|Realización de entrevistas con el cliente (dueño del reto) y establecimiento de sus metas y objetivos.|25|
|Benchmark| Revisión de features de la competencia y referencias análogas. | 20 |
|Entrevistas con usuarios| Entrevistas en profundidad con al menos 5 usuarios. | 60 |
|Testeos de las soluciones actuales de la competencia/actual| Sesiones de testing de productos actuales de la competencia para ver qué atributos valoran los usuarios. Al menos 5 usuarios. | 50 |
|Testeos de prototipos| Sesiones de testing de la solución propuesta (baja, media y alta fidelidad) con al menos 5 usuarios por sesión. | 60 |
|Prototipado de alta fidelidad| Elaboración de prototipo en base a las pantallas diseñadas. | 80 |
|| **TOTAL** | **295** |

[Archivo de implementación](https://drive.google.com/open?id=1-1siR0Zi9xdoQZ5iElPtZBqHcOngGFqfqiQqNjMQ-bE)

***

## Descubrimiento e Implementación

### Entrevista con el Cliente

En primer lugar, se solicitó una entrevista con Lalo Gonzales, Productor Manager de Aplicaciones Móviles, para comprender los objetivos de la app "Tus Finanzas" y resolver ciertas dudas en relación a los servicios que esta ofrece.  

Finalmente, se pudo identificar lo siguiente:

**Objetivo Principal de la App**
> - Fidelizar a sus usuarios a través de la fomentación de una cultura ahorro basada en metas personalizadas.

**Características de la App**
> - No se sincroniza con tarjetas de crédito porque es lo opuesto al ahorro.
> - Se realizó solo para el sistema iOS por falta de programadores.
> - En la sección de gastos, los valores de cada categoría es el acumulado de los movimientos diarios del mes.

**Comentarios del Cliente**    
> - Se debate la decisión de incrementar la inversión en facebook ads porque se capto gran público a través de este medio.
> - Se eligió al user principal por ser nativo digital.

_Documentación_: [Audio de la Entrevista](https://drive.google.com/open?id=1987Mmm6yqmWxv_3TQNohwg5DB2noXEuI)


### Análisis de la Data

Luego, con la data otorgada por el cliente, se propuso determinar si es conveniente duplicar la inversión en facebook ads y verificar si se esta implementando como sistema de fidelización a usuarios. Por lo tanto, se llevo cabo un estudio dónde se obtuvo lo siguiente:


**Análisis Funnel**

Desde el mes de febrero hasta el mes de julio, el número de impresiones de facebook ha sido un número razonablemente grande. Sin embargo, la cantidad de personas que se registra, es decir, usuarios que decidieron utilizar la app es muy pequeña. Esto se debe a que el porcentaje de pérdidas se ha incrementado en un 3.2% en este período.

<p align="center">
<img src='src\img\funnel_analisis.png'>
</p>


**Visitors-Mobile-Device**

Con respecto a las visitas al landing page, se pudo observar que la publicidad esta captando mayormente a un público que utiliza el sistema Android. Esto significa que no podrán ni descargarse y hacer uso de la aplicación. 

<p align="center">
<img src='src\img\Anali_Visitors.png'>
</p>

Adicionalmente, esta pérdida se debe considerar debido a que los celulares son los dispositivos que comprenden un número mayor visitas a diferencia de las tablets y los desktops.

<p align="center">
<img src='src\img\Anális_Visitors_Mobile.png'>
</p>

Por lo tanto, se llego a la siguiente conclusión:
> - Incrementar la inversión en publicidad podría generar mayores pérdidas para el banco, porque gran parte del mercado captado a trvés de facebook posee un sistema diferente al iOS. 


## Benchmark

Después, se realizó un estudio con 6 empresas (3 internacionales y 3 nacionales) para observar las distintas prácticas y, tal vez, adecuarlas a la aplicación móvil. Por lo tanto, en el siguiente cuadro se pueden apreciar ciertas categorías a considerar:

<p align="center">
<img src='src\img\Benchmark.png'>
</p>

## Entrevista con posibles usuarios

### Objetivo:

* Constatar el User Persona del Cliente.

### Documentación:

Realizamos entrevistas a posibles usuarios, entre ellos se ralizaron 5 del User Persona Primario y 5 del User Persona Secundario.

[Guía de preguntas](https://drive.google.com/open?id=1351BlcJLv1ChtZ5YY-XsY8M4JZnCazVyX1iQ66zdzsU)

[Entrevistas](https://drive.google.com/open?id=1ZIRMYz2HvXp7xcBcbyGzqSVgK9hNV7Cy)

### Problemas identificados:

* Poseen cultura de ahorro, mas no saben como realizarlo.
* La ocupación es un punto muy importante (estudian o trabajan).
* Los posibles usuarios tienen metas a corto y largo plazo.
* Un punto a tener en cuenta es que les gustaría tener todo los servicios que ofrecen en los bancos en una sola aplicación.

## 5. User Testing Online

Para realizar el Testing Online se utilizó la Herramienta Maze, ésta herramienta ayuda a poder testear prototipos, brindándo tareas para que las personas que accedan puedan cumplirlas.

**Personas Testeadas:** 50

### Tareas o Misiones:

1. Creación de un Usuario.
2. Creación de una cuenta de Ahorros.
3. Verificar los movimientos de Starbucks en el mes de Agosto.
4. Verificar los gastos del mes de Agosto.

### Conclusiones:

* Existen muchos pasos para poder acceder al aplicativo.
* La huella dactilar crea confusión.
* El menú es demasiado confuso.
* Mejorar la ubicación de las opciones.

[Link del Test Online](https://maze.design/projects/3569338/mazes/3569092)

***

## **II. Síntesis y Definición**

## 1. Affinity Map

Luego de realizar las entrevistas, procedemos a elaborar el affinity map con la finalidad de agrupar y categorizar temas recurrentes.

<center>

![image](https://user-images.githubusercontent.com/47750982/59631421-62d15880-910d-11e9-8ddf-c17d3af463a0.png)


</center>

[Fotos del proceso](https://drive.google.com/open?id=1NyRpxnMQvNKNhNhjfnUJBkUAPcBwfSD0)

[Conclusiones de cada grupo](https://docs.google.com/document/d/1vhcpZga_J8jl-ww2CdVO7yhKN4s3udxxQ09Hmj01jA4/edit?usp=sharing)

Realizamos 10 entrevistas en total. Una vez terminadas las entrevistas, analizamos los resultados y los dividimos en 14 grupos, los cuales son:

- Cultura de Ahorro.
- Ocupación.
- Redes Sociales.
- Ocio.
- Canal.
- Sistema Operativo.
- Valoración.
- Tarjetas.
- Servicios.
- Influencias.
- Metas.
- Sugerencias.
- Publicidad.
- Flujo.

### Principales conclusiones:

* El 50% de las personas entrevistadas estudian y el otro 50% trabajan.
* El 70% de las personas entrevistadas utilizan el Sistema operativo Android.
* Las personas entrevistadas saben que el ahorro es muy importante, pero no lo practican.
* Lo que valoran de las aplicaciones de banco, es que tenga todos los servicios para realizar de manera rápida cualquier trámite.
* Sólo el 40% vió alguna publicidad en Facebook, pero no ingresaron a link.

## 2. User Persona

Con las entrevistas y la elaboración del affinity map, creamos una user persona principal llamada **Cecilia Molina** y un user persona secundario llamado **Sebastián Arias**. Los caules representan a todos nuestros posible usuarios, sus frustraciones, motivaciones, sus datos demográficos, etc.

### User Persona Principal

<center>

![user 1](https://user-images.githubusercontent.com/47750982/59633379-fad14100-9111-11e9-9244-3e986209e482.png)

</center>

### User Persona Secundario

<center>

![user 2](https://user-images.githubusercontent.com/47750982/59633883-1c7ef800-9113-11e9-8433-a44da34d0cad.png)

</center>

## 3. Customer Journey Map

Esta herramienta nos sirvió para identificar y solucionar los puntos relevantes del viaje del usuario. Los puntos a enfocarnos son: la búsqueda de información, la comunicación entre el cliente y la empresa, los medios de pago y el servicio personalizado.

<center>

![Customer Journey Map](ThePlanningCo/Imagenes/customerjourneymap.jpg)

</center>

[Proceso del Customer Journey Map](https://drive.google.com/open?id=13whu8XL7CGXEO2hLvr0Ose10GZl_KkQF)


## Entrega

El proyecto será entregado en un repositorio de GitHub. En él deberás agregar
lo siguiente:

README.md  detallando:

* Objetivos iniciales del proyecto
* Problemas encontrados tanto a nivel de negocio como a nivel de usuario
* Recomendaciones de próximos pasos para el banco con respecto al app (estas
  recomendaciones tendrán que ser sustentadas por tu investigación):
  * Qué modificaciones se deberían hacer
  * Cuáles deberían ser los próximos desarrollos
  * En qué se debería invertir el presupuesto de marketing
* De acuerdo al punto anterior, de requerirse cambios y desarrollos nuevos,
  estos deberán ser diseñados y entregados en un prototipo de alta definición.
* Link de Zeplin, InVision inspects o Marvel Hand-offs para compartir tus
  diseños con desarrolladores

Un video en Loom de máximo 5 minutos explicando tu documento.
* Estos 5 minutos tienes que utilizarlos para explicar los puntos indicados en
  el `README.md` y para hacer un demo de la solución propuesta.

En las otras carpetas del repositorio o en las carpetas de Google Drive podrás
agregar los documentos complementarios que sustenten tu proceso.

