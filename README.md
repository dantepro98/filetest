<img align="center"  src="https://lh3.googleusercontent.com/-9kMdhysCq-0/YC7SEMUmdFI/AAAAAAAAAx4/lp70QwwQpCwt-1hMo1yBxJDEjdjmRE1IwCLcBGAsYHQ/image.png"/>

<img align="center" src="https://lh3.googleusercontent.com/-K3GMAcdCLwk/YC7SCS7VOTI/AAAAAAAAAx0/xBQhZQB-HksdKB1GLTfnb2A6nJz_qj1HQCLcBGAsYHQ/image.png"/>

Covid-19 Detector 
=================

El presente proyecto aborda el diseño y desarrollo de un sistema ubicuo de cámaras duales 
(térmica y fotográfica), de bajo costo construidas sobre una arquitectura ARM que, al ser 
desplegadas en espaciospúblicos cerrados, detectarán la temperatura de las personas en 
tiempo real, notifica sobre posibles casos de COVID-19 a los responsables de mantener la 
seguridad en dichos lugares y registra información relacionada a la cantidad de personas 
presentes en el lugar. La arquitectura funcional del sistema requiere una red de comunicación 
local, toda la información captada por el sistema es enviada a un servidorcentral a través 
de la red Sigfox para su posterior análisis. 

<img align="center" width="" height="200" src="https://1.bp.blogspot.com/-RiU64XkZtwQ/YC6bs-YFQqI/AAAAAAAAAw0/kkHGqTQ77n4O0Ve-ElX6G0xyXlA_wSq8wCLcBGAsYHQ/s530/imagen_2021-02-18_115408.png"/>

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

- Página Inicio 

![Imagen](https://github.com/fionalayer/filetest/blob/main/web.gif "DEMO WEB")

- Página Dashboard 

![Dashboard](https://github.com/fionalayer/filetest/blob/main/dash.gif "DEMO WEB")

## Contribuidores

<a href="https://minka.gob.ec/Nogyboy"><img align="" width="" height="50" src="https://1.bp.blogspot.com/-Vlx0DSsj9Fg/YC6grJfv4PI/AAAAAAAAAxU/2xNXWvBPu6USfZaUiknitOlNPH91uI0IACLcBGAsYHQ/s138/imagen_2021-02-18_121521.png"/></a>

## Licencia

Sin especificar...

