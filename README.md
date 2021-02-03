Cabina Covid-19
===============

<img align="right" height="156" src="https://1.bp.blogspot.com/-CNRT-KeE5ZU/YBhWttxTgrI/AAAAAAAAAvQ/npX4KbEQdfYiu4kwWX09APOZad9YTTQpQCLcBGAsYHQ/w320-h118/covidlogo.png"/>


Una herramienta de inteligencia artificial para prevenir la propagación 
del coronavirus (COVID-19) mediante módulo de temperatura Arduino. Una 
herramienta de inteligencia artificial analizadora de información para 
mostrar los datos en graficas. 

##### Requisito previo:

* Python básico
* Conocimientos básicos de creación de entornos virtuales python y Django 
REST framework. Recomendado usando pyenv.

##### Herramientas:

* Arduino IDE, VS Code, Pycharm  Profesional, Postgress.
* Paquetes de Python como se indica en `requirements.txt`

## Sigfox & Arduino

Una aplicación de IoT que toma y envía lecturas de temperatura a través de 
Sigfox, siempre que se detecta movimiento.

Se envía el valor de temperatura a Sigfox cada vez que la placa detecta un 
movimiento. Para visualizar los datos enviados, se verifica el monitor serial 
del Arduino IDE. También puede verificar los mensajes a través del backend de 
Sigfox seleccionando la ID del dispositivo de la lista de dispositivos.

Mira mas informacion sobre la [guia de conexion](https://create.arduino.cc/projecthub/55019/connect-your-thinxtra-xkit-using-sigfox-c8b2ba)
de project HUB.

## Aplicacion Web VERSION 1.0 

Entrono grafico de darrollo web.

![Imagen]( https://github.com/fionalayer/filetest/blob/main/web.gif "DEMO WEB")

Panel de control de la version de dashborad.

![Dashboard]( https://github.com/fionalayer/filetest/blob/main/dash.gif "DEMO WEB")

## Instalacion

#### PIPENV

Se verifica que se tenga instalado en Python en este caso es la versión 3.8.2

+ El comando para verificar la version de `python`:

    >python -V

+ Se instala la herramienta de gestion de paquetes, con el comando:

    >pip install pipenv
    o
    >python -m pip install pipenv
    
+ Verificamos la instalacion del paquete pipenv con el siquiente comando:

    >pipenv

+ Creamos el entorno de desarrollo con el comando:
   
    >pipenv shell 

+ Se instalacion las dependencias con el comando:

    >pipenv install

+ Verificamos que las dependencias esten instaladas con el comando:

    >pipenv graph

## Colaboradores

Estos datos han sido recopilados, agregados y documentados por Christian Guaman, 
Waltes Bustamante, Pedro Morocho, Luis Maurizaca, John Rodas, Erick Matailo, Harman Cabrera.
