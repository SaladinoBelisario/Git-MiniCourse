# **About Version Control**
## ¿En qué consiste?

Un sistema de control de versiones o VCS en una computadora local contiene una base de datos. Este conjunto de versiones se puede manejar mediante un archivo con diferentes marcas de tiempo, sin embargo, tiene como inconveniente complicar el flujo de trabajo de manera externa a la computadora local pues no se da una vista o control de otros usuarios.
![Sistema VCS](VCS.jpg)

## Tipos de sistemas de control

Un *sistema de control de versiones centralizado*, tiene un servidor central que mantiene una copia original, permitiendo hacer copias locales para poder modificar el archivo de manera independiente. Sin embargo, si dicho servidor se cae, perdería el acceso a las versiones centrales. Obteniendo únicamente archivos sueltos previamente guardados de manera local.
![System central VCS](Central VCS.jpg)

Un *sistema de control de versiones distribuido*, en cambio, permite un servidor el cual tiene prácticamente la misma información que las versiones locales de cada computadora individual. Si ocurriera lo mismo que en el VCS central y perdieramos el servidor, los datos locales se pueden reestablecer en el servidor central para continuar con el proyecto. El inconveniente de estos dos tipos de control (VCS y distribuido) es el flujo de trabajo que coordine como se elaborará dicho proyecto.
![System distributed VCS](Distributed.jpg)