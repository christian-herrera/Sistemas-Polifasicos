# Sistemas Polifasicos

Los archivos `.m` son funciones utilizadas con MatLab, cada uno tiene su imagen donde se ve la configuraciones de los componentes y los valores que recibe por parametros. Estos codigos devuelven por consola los datos mas relevantes y grafican los respectivos voltajes, corrientes, potencias y triangulo de potencias final.

## Estrella - Estrella (Sin Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYSinNeutro.jpg?raw=true)
Este algoritmo necesita los valores de las tensiones en cada generador y los valores de cada impedancia.


## Estrella - Estrella (Con Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYConNeutro.jpg?raw=true)
Este algoritmo necesita los valores de tension en cada generador y los valores de cada impedancia.


## Estrella - Estrella (Con Impedancia en el Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYConZn.jpg?raw=true)
Este algoritmo necesita los valores de tension en cada generador y los valores de cada impedancia, incluido el de la impedancia entre centros de estrella..


## Triangulo - Triangulo
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgTriangTriang.jpg?raw=true)
Este algoritmo necesita los valores de tension en cada generador y los valores de cada impedancia.


## Estrella - Triangulo
Este ultimo algoritmo es una extension del anterior ya que recibe los valores de los generadores en estrella y las impedancias en las cargas en triangulo.