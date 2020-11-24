# Sistemas Polifasicos

Los archivos `.m` son funciones utilizadas con MatLab, cada uno tiene su imagen donde se ve la configuraciones de los componentes y los valores que recibe por parametros. Estos codigos devuelven por consola los datos mas relevantes y grafican los respectivos voltajes, corrientes, potencias y triangulo de potencias final.

## Estrella - Estrella (Sin Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYSinNeutro.jpg?raw=true)
Este algoritmo necesita los valores de `V<sub>RN<\sub>`, `V<sub>SN<\sub>` y `V<sub>TN<\sub>`. Ademas de las cargas `Z<sub>rn<\sub>`, `Z<sub>sn<\sub>` y `Z<sub>tn<\sub>`.


## Estrella - Estrella (Con Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYConNeutro.jpg?raw=true)
Este algoritmo necesita los valores de `V<sub>RN<\sub>`, `V<sub>SN<\sub>` y `V<sub>TN<\sub>`. Ademas de las cargas `Z<sub>rn<\sub>`, `Z<sub>sn<\sub>` y `Z<sub>tn<\sub>`.


## Estrella - Estrella (Con Impedancia en el Neutro)
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgYYConZn.jpg?raw=true)
Este algoritmo necesita los valores de `V<sub>RN<\sub>`, `V<sub>SN<\sub>` y `V<sub>TN<\sub>`. Ademas de las cargas `Z<sub>rn<\sub>`, `Z<sub>sn<\sub>`,  `Z<sub>tn<\sub>` y `Z<sub>nN</sub>`.


## Triangulo - Triangulo
![img](https://github.com/christian-herrera/Sistemas-Polifasicos/blob/main/docs/imgTriangTriang.jpg?raw=true)
Este algoritmo necesita los valores de `V<sub>RS<\sub>`, `V<sub>ST<\sub>` y `V<sub>TR<\sub>`. Ademas de las cargas `Z<sub>rn<\sub>`, `Z<sub>sn<\sub>` y  `Z<sub>tn<\sub>`.


## Estrella - Triangulo
Este algoritmo es una extension del anterior ya que recibe los valores de `V<sub>RN<\sub>`, `V<sub>SN<\sub>` y `V<sub>TN<\sub>` y calcula los respectivos `V<sub>RS<\sub>`, `V<sub>ST<\sub>` y `V<sub>TR<\sub>`.
