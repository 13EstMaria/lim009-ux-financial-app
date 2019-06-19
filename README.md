# Tus Finanzas

## Introducción 

En la actualidad, dentro del sector de servicios financieros, la revolución digtale ha brindado oportunidades en mercados de todos los tamaños para desbloquear interesantes beneficios económicos a través de la expansión. En consecuencia, el aumento de la adopción de aplicaciones innovadoras, que se les conoce en la industria como "fintech", representa la estrategia para mnatenerse competitivos entre bancos y fidelizar a sus clientes con alta efectividad.  

## Contexto

Un banco decidió lanzar una nueva aplicación móvil al mercado para que sus usuarios puedan administar sus gastos, visualizar sus movimientos mensuales y fomentar el ahorro. Luego de un periódo de 6 meses meses en el mercado y algo de tracción, el project manager nos brindó una data para responder 2 preguntas: 

1. ¿Es conveniente duplicar la inversión en publicidad (facebook ads)?
2. ¿Qué se podría rediseñar de la aplicación para optimizarla? 

Para lo cual nos proporcionaron la siguiente carpeta: [Carpeta de Data](https://drive.google.com/open?id=1gV6PwrT6SZigVTJ67q8W-dFzGTLePUyK)

## Objetivos del Proyecto   

* Rediseñar un producto ya existente.
* Analizar data
* User testing
* Diseño de componentes de la interfaz

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

## **I. Descubrimiento e Implementación**

## 1. Entrevista con el Cliente

En primer lugar, se solicitó una entrevista con Lalo Gonzales, Productor Manager de Aplicaciones Móviles, para comprender los objetivos de la app "Tus Finanzas" y resolver ciertas dudas en relación a los servicios que esta ofrece.  

Finalmente, se pudo identificar lo siguiente:

### Objetivo Principal de la App

* Fidelizar a sus usuarios a través de la fomentación de una cultura ahorro basada en metas personalizadas.

### Características de la App

* No se sincroniza con tarjetas de crédito porque es lo opuesto al ahorro.
* Se realizó solo para el sistema iOS por falta de programadores.
* En la sección de gastos, los valores de cada categoría es el acumulado de los movimientos diarios del mes.

### Comentarios del Cliente

* Se debate la decisión de incrementar la inversión en facebook ads porque se capto gran público a través de este medio.
* Se eligió al user principal por ser nativo digital.

[Audio de la Entrevista](https://drive.google.com/open?id=1987Mmm6yqmWxv_3TQNohwg5DB2noXEuI)


## 2. Análisis de la Data

Con la data otorgada por el cliente, se propuso determinar si es conveniente duplicar la inversión en facebook ads y verificar si se esta implementando como sistema de fidelización a usuarios. Por lo tanto, se llevó a cabo un estudio dónde se obtuvo lo siguiente:

### Análisis Funnel

Desde el mes de febrero hasta el mes de julio, el número de impresiones de facebook ha sido un número razonablemente grande. Sin embargo, la cantidad de personas que se registra, es decir, usuarios que decidieron utilizar la app es muy pequeña. Esto se debe a que el porcentaje de pérdidas se ha incrementado en un 3.2% en este período.

<p align="center">
<img src='src\img\funnel_analisis.png'>
</p>


### Visitors-Mobile-Device

Con respecto a las visitas al landing page, se pudo observar que la publicidad esta captando mayormente a un público que utiliza el sistema Android. Esto significa que no podrán ni descargarse y hacer uso de la aplicación. 

<p align="center">
<img src='src\img\Anali_Visitors.png'>
</p>

Adicionalmente, esta pérdida se debe considerar debido a que los celulares son los dispositivos que comprenden un número mayor visitas a diferencia de las tablets y los desktops.

<p align="center">
<img src='src\img\Anális_Visitors_Mobile.png'>
</p>

### Conclusión

Incrementar la inversión en publicidad podría generar mayores pérdidas para el banco; porque gran parte del mercado captado a través de facebook, posee un sistema diferente al iOS. 

[Data Completa](https://drive.google.com/open?id=1uc1Ced5KWegtuDysdMprOhE64ZoziE5e)

## 3. Benchmark

Se realizó un estudio con 6 empresas (3 internacionales y 3 nacionales) para observar las distintas prácticas y, tal vez, adecuarlas a la aplicación móvil. Por lo tanto, en el siguiente cuadro se pueden apreciar ciertas categorías a considerar:

<p align="center">
<img src='src\img\Benchmark.png'>
</p>

## 4. Entrevista con posibles usuarios

A continuación, se decidió realizar entrevistas a personas con características similares a los user personas brindados por el cliente, con el propósito de constatar la realidad de los perfiles.

Finalmente, con el apoyo de una [guía de preguntas](https://drive.google.com/open?id=1351BlcJLv1ChtZ5YY-XsY8M4JZnCazVyX1iQ66zdzsU), se llevó a cabo la entrevista; contando con 5 personas relacionado al user primario y 5 personas relacionado al user secundario. 

### Documentación

[Entrevistas](https://drive.google.com/open?id=1ZIRMYz2HvXp7xcBcbyGzqSVgK9hNV7Cy)

### Conclusiones

* La ocupación (estudiar y trabajar) es un factor bastante influyente en los objetivos de los usuarios.
* Las metas a corto y largo plazo son propuestas en relación a sus actividades cotidianas.
* La cultura de ahorro del user primario se basa en ser "concientes" que es importante para planificar un mejor futuro.
* Un punto a tener en cuenta es que les gustaría tener todo los servicios que ofrecen en los bancos en una sola aplicación.

## 5. User Testing Online

Para realizar el Testing Online se utilizó la Herramienta Maze, ésta herramienta ayuda a poder testear prototipos, brindando tareas para que las personas que accedan puedan cumplirlas.

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

Esta herramienta nos sirvió para identificar y solucionar los puntos relevantes del viaje del usuario. Los puntos a enfocarnos son: registro en la aplicación, creación de una cuenta de ahorro y la salida de la app.

<p align="center">
<img width="1224" alt="Costumer Journey Map" src="https://user-images.githubusercontent.com/47750982/59724719-7dc8c900-91f0-11e9-9ebe-08e37379bb72.png">
</p>

## 4. Problem Statements

Se obtuvo 4 **Problem Statements**, los cuáles nos ayudarán en la Ideación:

### **<center>{Persona} necesita una manera {necesidad}, porque/para {insight}.</center>**

* Cecilia necesita registrarse rápidamente en la app porque desea acceder a los servicios.
* Cecilia necesita conocer las secciones de la app detalladamente para encontrar los servicios que ofrece.
* Cecilia necesita crear una meta para ahorrar en algo específico.
* Cecilia necesita una manera de cerrar sesión para sentirse segura.

[Problem Statements](https://drive.google.com/open?id=1vXTEa1YQABlJF-8VoT2VHteGMltJzBZz)

## 5. How Might We

Una vez obtenido los **Problem Statements** se pasó a realizar los **How Might We** de cada uno de ellos.

**Cecilia necesita registrarse rápidamente en la app porque desea acceder a los servicios.**

* ¿HMW agilizar el registro?

* ¿HMW hacer que su experiencia de registro sea buena?

**Cecilia necesita conocer las secciones de la app detalladamente para encontrar los servicios que ofrece.**

* ¿HMW mostrar los servicios que ofrece la app?

* ¿HMW hacer que Cecilia visualice las secciones de una manera sencilla?

**Cecilia necesita crear una meta para ahorrar en algo específico.**

* ¿HMW hacer que comprenda que es diferente a una cuenta de ahorros?

* ¿HMW mostrar que la meta es un ahorro a largo plazo?

**Cecilia necesita una manera de cerrar sesión para sentirse segura.**

* ¿HMW hacer que Cecilia se sienta segura al cerrar sesión?

* ¿HMW evitar que otras personas accedan a la cuenta de Cecilia?

[Problem statements & HMW](https://drive.google.com/open?id=1vXTEa1YQABlJF-8VoT2VHteGMltJzBZz)

***

## **III. Ideación**

## 1. Prototipo de Baja Fidelidad

Se realizó el Prototipo de Baja Fidelidad, sólo de las pantallas que se harán cambios; teniendo en cuenta todo lo recopilado en **Descubrimiento e Implementación** y en **Síntesis y Definición** y así entender que es lo que necesita el usuario.

**PORTADA / NUMERO DE CUENTA / CORREO Y CLAVE**

![Portada-Cuenta-Correo](https://user-images.githubusercontent.com/47750982/59727705-54159f00-91fc-11e9-8bd4-20818f6b83b1.png)


**MENU / META / CREAR META**

![Home-Metas-CrearMetas](https://user-images.githubusercontent.com/47750982/59727780-b8d0f980-91fc-11e9-8cf8-0cdd989583f8.png)

**ELIMINAR METAS / GASTOS / GASTOS PORCENTAJE**

![EliminarMetas-Gastos-DetallesDeGastos](https://user-images.githubusercontent.com/47750982/59727798-d1411400-91fc-11e9-8e6a-9c8b9f971922.png)

[Prototipo de Baja Fidelidad](https://drive.google.com/open?id=1e5mh0F8daNL1QeYa203O-aymjtbxJLZa)

## 2. Prototipo de Media Fidelidad

Al concluir con el **Prototipo de Baja Fidelidad**, pasamos a realizar el **Prototipo de Media Fidelidad** con algunos cambios que nos dieron los usuarios.

**PORTADA**

![PORTADA](https://user-images.githubusercontent.com/47750982/59728019-dd79a100-91fd-11e9-93a2-7f9c5ebd5207.png)

**NUMERO DE CUENTA**

![NUMERO DE CUENTA](https://user-images.githubusercontent.com/47750982/59728053-039f4100-91fe-11e9-845b-72afbdaac6d2.png)

**CORREO Y CLAVE**

![CORREO Y CLAVE](https://user-images.githubusercontent.com/47750982/59728116-4bbe6380-91fe-11e9-83b3-18b8e59f5da1.png)

**MENU**

![MENU](https://user-images.githubusercontent.com/47750982/59728181-9809a380-91fe-11e9-8b90-25315ed8e352.png)

**META**

![META](https://user-images.githubusercontent.com/47750982/59728199-b2438180-91fe-11e9-9976-4c45dd476246.png)

**CREAR META**

![CREAR META](https://user-images.githubusercontent.com/47750982/59728212-c4252480-91fe-11e9-8f1f-b65f9a0de5bb.png)

**ELIMINAR META**

![ELIMINANDO META](https://user-images.githubusercontent.com/47750982/59728254-e7e86a80-91fe-11e9-83ba-a5f2e452ba32.png)

**GASTOS**

![GASTOS](https://user-images.githubusercontent.com/47750982/59728271-ffbfee80-91fe-11e9-8a8c-3aac75452fe9.png)

**GASTOS PORCENTAJE**

![GASTOS PORCENTAJE](https://user-images.githubusercontent.com/47750982/59728328-3b5ab880-91ff-11e9-996a-7c040bf307cf.png)


[Prototipo de Media Fidelidad](https://drive.google.com/open?id=1wSojev4l-H6TQrJWBZvk4YPa1tkBmTpl)

***

## **IV. Prototipado**

## 1. Prototipo Alta Fidelidad

Luego de plantear los prototipos de baja y media fidelidad, definimos nuestro prototipo de alta. Al elaborarlo decidimos qué colores usar, las tipografías, iconos y otros elementos visuales que mantendrían la identidad de Tus Finanzas y fortalecerían su imagen frente al público.

**PORTADA**

![Portada](https://user-images.githubusercontent.com/47750982/59728590-5679f800-9200-11e9-88b6-74ce4b1320bb.png)

**NUMERO DE CUENTA**

![NUMERO DE CUENTA 1](https://user-images.githubusercontent.com/47750982/59728682-b53f7180-9200-11e9-9807-136f68dafffb.png)
![NUMERO DE CUENTA 2](https://user-images.githubusercontent.com/47750982/59728691-bffa0680-9200-11e9-88f7-a6f9d3b0189f.png)

**CORREO Y CLAVE**

![CORREO Y CLAVE 1](https://user-images.githubusercontent.com/47750982/59729120-96da7580-9202-11e9-80ae-13ce68ce9521.png)
![CORREO Y CLAVE 3](https://user-images.githubusercontent.com/47750982/59729122-980ba280-9202-11e9-9a9f-3ff396e44ea3.png)

**MENU**

![Home](https://user-images.githubusercontent.com/47750982/59729147-b8d3f800-9202-11e9-98a4-58cba1a2b95b.png)

**META**

![Metas](https://user-images.githubusercontent.com/47750982/59729165-dacd7a80-9202-11e9-8a47-4730240e720f.png)

**CREAR META**

![Crear meta](https://user-images.githubusercontent.com/47750982/59729226-0e100980-9203-11e9-9a13-01d9344f53bd.png)
![Crear meta 3](https://user-images.githubusercontent.com/47750982/59729227-0f413680-9203-11e9-9f36-09ccc67a8ddb.png)

**ELIMINAR META**

![Editar+Eliminar](https://user-images.githubusercontent.com/47750982/59729300-647d4800-9203-11e9-9e56-055f9b5f71e1.png)

**GASTOS**

![gastos-activo-noexpandido](https://user-images.githubusercontent.com/47750982/59729345-99899a80-9203-11e9-88a2-b4dc7d9bd38c.png)

**GASTOS PORCENTAJE**

![Porcentaje](https://user-images.githubusercontent.com/47750982/59729355-b2924b80-9203-11e9-88d0-265e0678f6e4.png)


[Prototipo de Alta Fidelidad](https://drive.google.com/open?id=1bZtGvbNnWU3wP-GVCOd_zgGbA_AEl_fk)

***

## **V. User Testing**

### 1. Entrevistas

Se realizó 5 entrevistas del **Prototipo de Alta Fidelidad** a posibles usuarios de **Tus Finanzas**, dándoles las siguientes tareas:

* Instala la Aplicación Tus Finanzas.
* Crea un Usuario en la App Tus Finanzas.
* Verifica el detalle del último movimiento, realizado en el mes de Mayo.
* Crea una meta.
* Verifica el porcentaje de los gastos realizados en el mes de Mayo.

[Testing Online - Maze](https://t.maze.design/3629398)

Terminada las entrevistas se pudo sacar las siguientes conclusiones, las cuales se tendrán en cuenta para poder realizar la iteración.

* Al momento de insertar la clave, que sea más específica.
* Cambiar los íconos del menú.
* En la pantalla de Home, que exista información de gastos y ahorros.

[User Testing](https://drive.google.com/open?id=1Fq7TcjtRBBcPeox5s0dVEOjc2IzUP74uCUADDOuuM9M)

### 2. Prototipo de Alta Fidelidad Final

Terminada las entrevistas se pasó a prototipar las pantallas teniendo en cuenta el feedback recibido.

**CONTRASEÑA**

![ContraseñaCompleta-SignUp](https://user-images.githubusercontent.com/47750982/59778364-f4f76f00-927b-11e9-80cd-73fd79fa092f.png)

**PANTALLA MENU**

![Home](https://user-images.githubusercontent.com/47750982/59778537-4b64ad80-927c-11e9-8e20-f5e327f0c51a.png)

[Prototipado Final](https://drive.google.com/open?id=1mq_APKPGX6jjukix3QdNqmxxXmisXVFg)

[Flujo - Prototipado Final](https://marvelapp.com/4ab84jf/screen/58092759)

***

## **VI. Conclusiones**

### 1. Recomendaciones

- Comenzar a invertir en programadores Android debido a que, actualmente, la publicidad capta mayormente al público con dispositivos que trabajan con este sistema.

- Indicar a los sus usuarios a dónde se debita el dinero de sus cuentas.

- Con respecto a Active Devices, se encontró errores dentro de la data que podría ser crucial para futuras evaluaciones.

### 2. Documentación extra

[Link de video en LOOM](https://www.loom.com/share/ef164b2c4e3b47139d0ec571f3a559d2)

[Link carpeta de trabajo en Drive](https://drive.google.com/open?id=1yP5W-szbvWFLFHt-6CVA2_tIIi3JURY-)

[Link de prototipo en Zeplin](zpl.io/V1Q9Egk)



