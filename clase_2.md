# Clase 23/03/2016

## Qué vimos

 - Repasamos la idea de herencia múltiple
 - Presentamos el [problema del diamante](https://es.wikipedia.org/wiki/Problema_del_diamante).
 - Explicamos que los mixins aplican resolución implícita de conflictos mediante linearización.
 - Comentamos que los traits usan un mecanismo de resolución explícita.
 - Comenzamos a solucionar el trabajo práctico de ensamblaje de PCs.
 - Comparamos diferentes soluciones a los primeros puntos del trabajo.
 - Destacamos una solución que aplicaba el patrón stackable mixin y lo explicamos.
 - Comparamos el stackable mixin con patrones clásicos como el [Decorator Pattern](https://en.wikipedia.org/wiki/Decorator_pattern).
 
## Repositorios para el tp

 Como primer TP de la materia se pidió terminar los ejercicios vistos en clase.
 Cada grupo tiene asignado un repo vacío. Para usarlo, pueden encontrarse en alguna de las siguientes situaciones:

### 1. Estuvieron versionando en un repo local solamente.

En este caso pueden agregar el repo remoto con:

    git remote add origin URL_DEL_REPO

Y pushean los cambios

    git push -u origin master


### 2. Estuvieron versionando localmente y ya tienen un repo propio remoto.

En este caso, lo más sencillo es hacer que el origin de su repo pase a ser el de la materia:

    git remote set-url origin URL_DEL_REPO

Y luego push como siempre. De ahora en más lo que pusheen va a ir al repo de la materia


### 3. No tienen versionado

En este caso se crean el repo local como siempre:

    git init
    git add
    git commit -m "initial commit"

Y pasan al caso #1

De todas maneras en sus repos vacios aparecen mini guías según cada caso. 
 
