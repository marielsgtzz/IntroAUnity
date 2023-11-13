# Intro a Unity

## Uso de Git y Github con Unity

Al crear un proyecto en Unity se generan muchos archivos que no son necesarios subir a Github para su funcionamiento (en su mayoría estos archivos son logs del proyecto que se pueden generar en cada computadora).

El propósito de no incluirlos en el repositorio es que Github no permite subir archivos mayores a `100MB` a menos que esté activo `LFS` (Large File System) en el repo (aún así esta opción tiene un límite mensual).

Cuando se crea un repositorio en Github existe la opción de agregar un archivo `README.md` y un `.gitignore`.

La plataforma tiene diferentes plantillas para el `.gitignore` dependiendo la naturaleza del repositorio, para Unity recomiendan usar [esta](https://github.com/github/gitignore/blob/main/Unity.gitignore) plantilla.

El propósito del `.gitignore` es que cuando se ejecute el comando `git add .` no se incluyan todos los archivos del `.gitignore` en la etapa de `staging`.

### Evitar merge conflicts

Cuando se trabaja en la escena cambia su script, y resolver merge conflicts cuando más de una persona trabaja en la escena se vuelve algo complicado.

Una buena práctica es no trabajar la escena simultáneamente de forma directa, para esto es útil el uso de [prefabs](InicioProyecto.md#prefabs).

Si se quiere editar un objeto de la escena es mejor volverlo un `prefab` y agregar el prefab a la escena, las modificaciones hay que hacerlas directamente al prefab, de esa forma no cambia el archivo de la escena (se evitan merge conflicts) ya que lo que cambia es el archivo del prefab que idealmente solo está siendo trabajado por una persona a la vez.

## Intro a interfaces gráficas

Un manual sobre los componentes básicos y más usados de una interfaz gráfica.

[Explicacion GUI](InterfazDeUsuario.md)

## Como exportar de Unity a un dispositivo

Un manual sobre los pasos a seguir para tener las experiencias en iOS o Android.

[Explicacion exportación](ExportarUnaExperiencia.md)

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
