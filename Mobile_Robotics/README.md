### Parametrización.xml 

#### Actividad 2.1 (Parametrización de trayectorias)
* Implementar el código requerido para generar la parametrización de las siguientes trayectorias en un plano 2D.
* Obtener las siguientes trayectorias definidas a partir de curvas paramétricas

Código base para el funcionamiento:
```MATLAB
t = -20*pi:0.01:20*pi;      %Linspace 
x = -cos(t)+cos(-0.35*t);   %vectors as sym x
y = -sin(t)-sin(-0.35*t);   %vectors as sym y 

comet(x, y)                 %Animation plot

```
