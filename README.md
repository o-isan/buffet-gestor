# Buffet Gestor
Buffet Gestor es una agenda de finanzas personales para controlar los ingresos, y gastos.
Su nombre  es en honor al inversionista estadounidense: "Warren Buffet".

Está hecha en python con la tecnología de GUI kivy. Para almacenar los datos se usa SQLite3.
Pues este gestor de bbdd es idóneo para aplicaciones pequeñas que almacenen los datos en el propio dispositivo.


Los datos se pueden representar con gráficos que son elaborados con la libería matplotlib.
![Gráfico que representa los ingresos por un lado y los gastos por otro](img/1.jpg)


Se pueden obtener resumenes financieros seleccionando el periodo de tiempo que deseemos.
![resumen de gastos, ingresos y beneficios en un periodo de tiempo](img/3.jpg)


## Más vistas:
Registros como filas
![registros como filas](img/2.jpg)

**Panel de control**
![el panel de control, o menú](img/4.jpg)

**Añadir un registro de ingreso a la agenda**
![ventana de añadir un ingreso](img/5.jpg)



## Vídeo de demostración:
[Ver video](vid/1.mp4)



## Muestras de código
**Añadir gasto**
![ventana de añadir un gasto](img/6.png)


**Añadir ingreso**
![ventana de añadir un ingreso](img/7.png)


**Iniciar sesión**
No es realmente inicio de sesión en una web, sino una forma de proteger la agenda
Las credenciales se configuran la primera vez que se ejecuta la app (cuando no hay nada guardado en BBDD)
![ventana de login](img/8.png)


**Configuración**
![Configuración](img/9.png)







