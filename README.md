# TP1-IngDeSW
### Primer trabajo práctico de Ingeniería de Software

## Autores

#### Chort Julio, Moya Macarena, Quarin Federico, Reynoso Valentín

## Resolución

### Inciso 2b
Con el archivo .gitignore se pueden ignorar todos los cambios realizados sobre archivos y/o carpetas que estén especificados dentro del mismo. Entonces para ignoarlos sólo se debe poner el nombre del elemento a ignorar dentro de este archivo.

### Inciso 2c y 2d
Para crear los branch que pide el ejercicio primero nos ubicamos dentro de la rama "Develop" y desde ahí utilizamos el comando "git checkout -b <nombre_rama>". Ejecutado el comando ya nos encontramos dentro de la rama.

### Inciso f
En este inciso hicimos una rama secundaria a partir de "Release2" desde donde hicimos modificaciones para luego generar un PR hacia la misma.

### Inciso 2g
Siguiendo Gitflow lo que debe hacerse es crear un pull request desde la rama Release1 a Develop, luego hay que crear una rama "Release-v.1.0.0" que posteriormente se hara un PR tanto a main como a Develop. Es decir, es una rama temporal que sirve para tener la versión lista en una rama y probarla antes de pasarla a la rama principal (main). Creemos que en este punto deberíamos haber creado el tag "v1.0.0" pero no lo hicimos.

### Inciso 2h
Se hicieron los mismos pasos que en el inciso anterior pero ahora con la rama Release2. Una vez llevados los cambios a main, se publicó una nueva versión mediante el tag "v1.1.0".

### Inciso 2i
Se hicieron los mismos pasos que en los incisos 2c y 2d.

### Inciso j
Para deshacer la modificación B se utilizó el comando "git revert HEAD", con lo que se deshace el último commit realizado (en este caso la modificación B).

### Inciso 2k
Se hicieron los mismos pasos que en el inciso 2g y se colocó el tag "v1.2.0".

### Ejercicio 3
Se puede documentar con git de 2 maneras: un README ó por changelog. En este TP utilizamos un README.

### Inciso 3a
Dentro del README se deberían documentar los aspectos generales del producto de software contenido dentro del repositorio, como pueden ser: cómo se utiliza la aplicación, los propietarios, ejemplos de uso, etc.

### Inciso 3b
Al externo se le pediría una breve descripción de los cambios realizados, haciendo énfasis en las funcionalidades agregadas y/o los bugs arreglados. También se debería agregar si responde a algún requerimiento de cambio solicitado por algún usuario o desarrollador de la aplicación. 
Para ayudarnos con esto, GitHub nos ofrece la posibilidad de colocarle un título y una descripción tanto a cada commit realizado como también al PR creado. En estos campos es donde deberían estar todos estos datos anteriormente pedidos. 

## Gráfico de Network

A continuación se anexa el gráfico del árbol de este proyecto

![Diagrama de Network](https://user-images.githubusercontent.com/57647406/193060258-3e32245e-cd9a-4ba8-bcfe-641adf93b240.png)


