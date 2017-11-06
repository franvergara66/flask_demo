![featured-image](https://raw.githubusercontent.com/franvergara66/flask_demo/master/flask_image.jpg)

#### <i class="icon-file"></i> Review

Flask es un microframework simple y fácil de usar para Python que puede ayudar a crear aplicaciones web escalables y seguras. Aquí hay algunas razones por las que Flask es ideal para principiantes:

 - Es fácil de configurar 
 - Es apoyado por una comunidad activa 
 - Está bien documentado 
 - Es muy simple y minimalista, y no incluye nada que no
   uses
 - Al mismo tiempo, es lo suficientemente flexible como para
   agregar extensiones si necesita más funcionalidad

En este tutorial, cubriremos lo siguiente:

 - Estructura recomendada de archivos y directorios para un proyecto de Flask
 - Configuración e inicialización de una aplicación Flask
 - Creando vistas y plantillas

Al final de este tutorial, habremos creado un sitio web estático simple usando Flask. 

Comencemos...

#### <i class="icon-file"></i> Instalación


Necesitaremos lo siguiente instalado para este tutorial:

 - Python (este tutorial usa Python 2)virtualenv y virtualenvwrapper (para crear un ambiente virtual aislado)
 - Flask
Es posible que ya tenga Python instalado en su sistema. Puede verificar ejecutando el comando python en su terminal. Si está instalado, debería ver el siguiente resultado:

```
$ python
Python 2.7.10 (default, Oct 23 2015, 19:19:21)
[GCC 4.2.1 Compatible Apple LLVM 7.0.0 (clang-700.0.59.5)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

Si no lo tiene instalado, puede descargarlo aquí.

Comenzaremos por instalar virtualenv, una herramienta para crear entornos de Python aislados. Necesitamos usar entornos virtuales para mantener separadas las dependencias utilizadas por diferentes proyectos de Python, y para mantener nuestro directorio global de paquetes de sitios limpio. Vamos a ir un paso más allá e instalar virtualenvwrapper, un conjunto de extensiones que hacen que el uso de virtualenv sea mucho más fácil al proporcionar comandos más simples.
