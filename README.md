# Intro a Unity

## Uso de Git y Github con Unity

Al crear un proyecto en Unity se generan muchos archivos que no son necesarios subir a Github para su funcionamiento (en su mayoría estos archivos son logs del proyecto que se pueden generar en cada computadora).

El propósito de no incluirlos en el repositorio es que Github no permite subir archivos mayores a `100MB` a menos que esté activo `LFS` (Large File System) en el repo (aún así esta opción tiene un límite mensual).

## Intro a interfaces gráficas

Un manual sobre los componentes básicos y más usados de una interfaz gráfica.

[Explicacion GUI](InterfazDeUsuario.md)

## Estructura Repositorio

### Proyecto Integral Unity 1

[ReadMe Proyecto](ProyectoIntegralUnity1/README.md)

La idea de este proyecto es incluir en un mismo lugar los espectos fundamentales de Unity que se tocan en los siguientes 3 proyectos.

### Explosión Objetos

[ReadMe Proyecto](ExplosionCubos/README.md)

<img src="imgMds/explosionObjetos.png" alt="explosionObjetos" width="350" height="200"/>

### Colisión Objetos

[ReadMe Proyecto](ColisionObjetos/README.md)

<img src="imgMds/colisionObjetos.png" alt="colisionObjetos" width="350" height="200"/>

### Salto Obstáculos

[ReadMe Proyecto](SaltoObstaculos/README.md)

<img src="imgMds/saltoObjetos.png" alt="saltoObjetos" width="350" height="200"/>

Se mueve el fondo en loop (en eje x) y van entrando objetos (cajas) al marco y desaparecen cuando llegan a una cierta posición en x. El personaje se queda en la misma posición de x pero cuando se una la `space bar` se eleva en eje y simulando un salto, se utilizan animaciones del personaje para que el movimiento sea más suave.

Para más información sobre como utilizar las animaciones de un modelo consultar [este archivo](MovimientoPersonaje.md).

## Realidad Aumentada

[Repositorio con proyectos de AR](https://github.com/marielsgtzz/RealidadAumentada/tree/main)

#### Referencias

https://www.udemy.com/course/unity-curso-completo-profesional-de-programacion-desde-cero/
