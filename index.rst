Aplicaciones web con Python - Estado del arte
=============================================

Estado del arte de aplicaciones web desarrolladas en Python.

Revisiones
----------

 * 7 de Diciembre de 2011 (Primera Revisión)

Objetivo
--------

 * Abordar brevemente las diferentes metodologías (frameworks) de
   desarrollo web en Python.

 * Tener una idea general de las tendencias y grupos de desarrollo.

Programación Orientada a Objetos
--------------------------------

Python cumple con las principales características de la programación
orientada a objetos.

 1) Abstracción

 2) Encapsulamiento

 3) Modularidad

 4) Principio de ocultación

 5) Polimorfismo

 6) Herencia

 7) Recolección de basura


Guiones (Scripting)
-------------------

Python se usa como un lenguaje de scripting para tareas de
administración de un servidor, y, obviamente para programación
puramente estructurado.


CGI
---

* Configuras tu web server para que ejecute un script de Python. El
  script de Python escupe HTML.

* Puedes hacer lo mismo con cualquier otro lenguaje de programación,
  como C, bash, ensamblador o Brainfuck ...

WSGI
----

Ir a: http://wsgi.org/wsgi/

* Se pronucia *Wisgui*, así como *Whiskey*.

* WSGI no se limita a Pyton, es una especificación, nacida en la
  comunidad *pythonera* y se trata de facilitar la comunicación entre
  servidores web (como nginx o apache) y aplicaciones.

App web independiente
---------------------

* Desarrollas tu app fuera de apache. 

* El servidor web lo hace muy bien sirviendo páginas web, imágenes,
  archivos, etc.

* Tu app hace todo lo demás.

* No se puede hablar todavía de ventajas y desventajas de seguridad
  explícitas.


Zope
----------------------------------

* Zope es el primer framework web orientado a la web. 

* Es un framework orientado a objetos.

* Pero ya la regaron un montón de veces y han acumulado experiencia
  desde 1999.

Zope - I
--------------------------------------

* Pronunciar **Zope** en la comunidad Pythonera es casi como decir el
  nombre real del *Señor obscuro* en los primeros libros de Harry Potter.

* Gracias a eso Zope ha quedado relegado como un ciudadano de segunda clase.

* *Where Zope leads, Python Follows*.

Zope - II
---------------------------------------

* Zope 2

* Zope 3 --> BlueBream

* *Grok*

* Pyramid (?)

Zope - III
----------------------------------------

* ZCA (Zope Component Architecture)

  * Interfaces, Utilities, Adapters

* Views

* Traversing (http://sitio/contenedor/objeto1/objeto2/@@vista

* La base de datos puede ser NoSQL (ZODB) o SQL.

* Deployment con WSGI o con un servidor aparte.

Django
------

* Framework MVT (Model, View, Template)

* Las urls se mapean a vistas, las cuales interactuan con los modelos).

* La base de datos es relacionar, pero tiene ORM para las bases de datos más.

* El Deployment es con WSGI o fastCGI.

Otros
-----

* Turbogears --> (Pylons/Pyramid) - http://turbogears.org/

* Pyramid (repoze.BFG + Pylons) - http://pylonsproject.org/

* CherryPy - http://www.cherrypy.org/

* web2py - http://web2py.com/



Otros - mini frameworks
-----------------------

* wsgiref (Distribuido en las distros recientes de Python)

* BaseHTTPServer (Incluido en las distros de Python)

* Bootle - http://bottlepy.org/

* Flask - http://flask.pocoo.org/


FAQ
---

* ¿Debería ir a probar un framework de Python inmediatamente después
  de este evento?

  * Si, por que ...

  * No, por que ...

* ¿Por qué python y no ... <lenguaje favorito="1" />?

  * Usar otras herramientas te ayuda a conocer mejor la que tu ya usas.

  * Tal vez encuentres una manera más sencilla de resolver problemas
    que ya hayas resulto.

FAQ - I
-------

* ¿Qué framework me recomiendas para empezar?

  * Flask, bootle.

  * Django

  * Pyramid, Bluebream (Zope 3), Grok, etc.

FAQ -II
-------

* ¿Debería escribir mi propio framework de Python?

  * Solo si tienes barba.


Final
-----

* El que les vino a quitar el tiempo se llama Noe Nieto
* Tiene una página en http://noenieto.com
* Esta presentación la hice con ``python-docutils``, ReSTructuredText y emacs.


