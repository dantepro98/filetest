Cabina  de desinfección Covid-19
===============

<img align="right" height="100" src="https://1.bp.blogspot.com/-cPh9PSBInTg/YC6X8WYMzcI/AAAAAAAAAwY/lcEx7VTsQ-sOd2ZmRRoRbAfPhtBDG2qvACLcBGAsYHQ/s803/imagen_2021-02-18_113806.png"/>


Una herramienta de inteligencia artificial para prevenir la propagación 
del coronavirus (COVID-19) mediante módulo de temperatura Arduino. Una 
herramienta de inteligencia artificial analizadora de información para 
mostrar los datos en graficas. Una aplicación de IoT que toma y envía 
lecturas de temperatura a través de Sigfox, siempre que se detecta movimiento.

##### :pencil: Requisito previo:

* Python básico
* Conocimientos básicos de creación de entornos virtuales python y Django 
REST framework.

##### :computer: Herramientas:

* Arduino IDE, VS Code, Pycharm  Profesional, Postgress.
* Paquetes de Python como se indica en `requirements.txt`

## Pycharm Profesional :snake:

En este proyecto se utilizo PyCharm ya que ofrece una gran compatibilidad con marcos de trabajo de desarrollo web moderno 
con [Django](https://www.jetbrains.com/help/pycharm/django-support7.html#django-support "soporte de Django en PyCharm"), 
proporciona una finalización del código inteligente, inspecciones del código, indicación 
de errores sobre la marcha y arreglos rápidos, así como refactorización de código automática
y completas funcionalidades de navegación.

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

## Aplicación Web VERSION 1.0 :bar_chart:

Entrono grafico de darrollo web.

![Imagen]( https://github.com/fionalayer/filetest/blob/main/web.gif "DEMO WEB")

Panel de control de la version de dashborad.

![Dashboard]( https://github.com/fionalayer/filetest/blob/main/dash.gif "DEMO WEB")

## Colaboradores

Estos datos han sido recopilados, agregados y documentados por Christian Guaman, 
Walter Bustamante, Pedro Morocho, Luis Maurizaca, John Rodas, Erick Matailo, Harman Cabrera.
