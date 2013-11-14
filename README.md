Datafest: La gran propuesta
===========================

Datos publicados por la Jefatura de Gabinete de Ministros sobre la inversión en publicidad oficial por proveedor y tipo de medio. Información desde Diciembre de 2008, estructurada por razón social, tipo de medio y total general.

Requerimientos
==============

- Ruby 1.9.3
- MySQL


Instrucciones
=============

Un vez que bajas el repo, hay que configurar el archivo `config/database.yml`. 
Luego desde la terminal, dentro del directorio donde esta la aplicación hay que ejecutar esta serie de comandos:

~~~ bash
$ bundle install
$ rake db:migrate
$ ruby app.rb
~~~

Sí todo salio bien la aplicación deberia estar andando en en la siguiente ruta: http://0.0.0.0:4567

![preview](http://cl.ly/image/3V1y2J453a3X/datafest_la_gran_pauta_preview.png)

Equipo
======

- Adrian Pino
- Alejandro Di Meglio
- Diego Peralta
- Diego Tripodi
- Elena Brizuela
- Fernando Ruiz
- Gerardo Gera
- Jorge Lerche

