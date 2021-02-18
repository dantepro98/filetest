Covid-19 Detector 
=================

<img align="right" width="300" height="150" src="https://1.bp.blogspot.com/-cPh9PSBInTg/YC6X8WYMzcI/AAAAAAAAAwY/lcEx7VTsQ-sOd2ZmRRoRbAfPhtBDG2qvACLcBGAsYHQ/s803/imagen_2021-02-18_113806.png"/>

El presente proyecto aborda el diseño y desarrollo de un sistema ubicuo de cámaras duales 
(térmica y fotográfica), de bajo costo construidas sobre una arquitectura ARM que, al ser 
desplegadas en espaciospúblicos cerrados, detectarán la temperatura de las personas en 
tiempo real, notifica sobre posibles casos de COVID-19 a los responsables de mantener la 
seguridad en dichos lugares y registra información relacionada a la cantidad de personas 
presentes en el lugar. La arquitectura funcional del sistema requiere una red de comunicación 
local, toda la información captada por el sistema es enviada a un servidorcentral a través 
de la red Sigfox para su posterior análisis. 

##### :pencil: Objetivo General:

Determinar la eficiencia de un dispositivo ubicuo, embebido con sensores infrarrojo y 
fotográfico y de bajo costo para detectar posibles casos COVID-19, sintomáticos en ambientes 
reales. 

## Desarrollo:

El proyecto se encuentra desarrollado como una aplicación web haciendo uso del framework 
[Django](https://www.djangoproject.com/) con [Python](https://www.python.org/), junto a 
Rest Framework para la construcción del API Rest, para la base de datos se utiliza 
[PostgreSQL](https://www.postgresql.org/) y para el dispositivo Sigfox se utiliza C++. 

## Aplicación Web :bar_chart:

a. Página Inicio 

![Imagen]( https://github.com/fionalayer/filetest/blob/main/web.gif "DEMO WEB")

b. Página Dashboard 

![Dashboard]( https://github.com/fionalayer/filetest/blob/main/dash.gif "DEMO WEB")

## Colaboradores

Estos datos han sido recopilados, agregados y documentados por Christian Guaman, 
Walter Bustamante, Pedro Morocho, Luis Maurizaca, John Rodas, Erick Matailo, Harman Cabrera.

## Sigfox & Arduino :satellite:

[Sigfox](https://www.sigfox.com/en "Sigfox Web"): es una solución de conectividad celular mundial para el Internet of 
Things pensada para comunicaciones de baja velocidad que permite reducir los
precios y el consumo de energía para los dispositivos conectados.

[Arduino](https://www.ingmecafenix.com/electronica/arduino/): es una plataforma de prototipos electrónica de código abierto (open-source) basada en una sencilla placa con entradas y salidas, en un entorno de desarrollo que está basado en el lenguaje de programación Processing. Es un dispositivo que conecta el mundo físico con el mundo virtual, o el mundo analógico con el digital.

Se envía el valor de temperatura a Sigfox cada vez que la placa detecta un 
movimiento. Para visualizar los datos enviados, se verifica el monitor serial 
del Arduino IDE. También puede verificar los mensajes a través del [backend de 
Sigfox](https://www.aprendiendoarduino.com/2018/03/05/arduino-y-sigfox/ "Backend de Sigfox") seleccionando la ID del dispositivo de la lista de dispositivos.

Mira mas informacion sobre la [guia de conexion](https://create.arduino.cc/projecthub/55019/connect-your-thinxtra-xkit-using-sigfox-c8b2ba)
de project HUB.

## PostgreSQL :cloud:

Python tiene varios controladores de base de datos para PostgreSQL. Cubre las 
actividades más comunes para interactuar con PostgreSQL en la aplicación Pycharm Profesional:

* [Conexión al servidor de base de datos PostgreSQL](https://www.jetbrains.com/help/pycharm/connecting-to-a-database.html#connect-to-postgresql-database "conexión a la base de datos postgresql ") : muestra cómo conectarse al servidor de base de datos PostgreSQL desde PyCharm.
* Actualización de datos en la tabla de PostgreSQL en Python.
* Consulta de datos de las tablas de PostgreSQL.
* Llamar a una función de PostgreSQL en Python.
* Llamar a un procedimiento almacenado de PostgreSQL en Python.
* Eliminación de datos de tablas de PostgreSQL en Python.
