## Tarea Corta: Simon TEC
### Autor: Eduardo Bolívar Minguet
### Carné: 2020158103

El proyecto SimonTEC consiste en un juego de memoria interactivo en el que se debe se le mostrará al usuario diferentes combinaciones de los colores **amarillo**, **rojo**, **verde** y **azul** de forma aleatoria. El usuario deberá presionar los colores en el orden que aparecieron anteriormente, y con cada secuencia correcta que ingrese el usuario, un nuevo color de los cuatro mencionados será añadido. Si el usuario se equivoca al presionar un color, automáticamente el juego se reinicia.    

### _Historias de usuario encontradas_
```markdown
Como usuario:

1. Quiero ver el nivel en el que me encuentro.
2. Quiero que se iluminen los cuatro colores disponibles en el juego.
3. Quiero que el orden de iluminación de los colores sea aleatorio.
4. Quiero que muestre los colores lentamente en las primeras secuencias.
5. Quiero ver los colores en pantalla.
6. Quiero que los colores tengan los bordes blancos para identificar el área cuando no estén iluminados.
7. Quiero que la dificultad sea adaptable.
8. Quiero que la velocidad de aparición de los colores sea acorde a la dificultad actual.
9. Quiero que la dificultad no sea extremadamente alta.
10. Quiero que el mouse detecte las coordenadas de los colores para seleccionarlo.
11. Quiero que el puntero sea visible.
12. Quiero que sólo se ilumine un color a la vez.
13. Quiero que todos los colores funcionen.
14. Quiero que el color de fondo sea negro, para que no se confunda con los colores en juego.
15. Quiero que al hacer click sobre el color correcto, se repita la secuencia con otra iluminación al final.
16. Quiero que al hacer click en el color incorrecto, se imprima un mensaje en consola que lo comunique.
17. Quiero que sólo se pueda hacer click cuando la secuencia no esté en ejecución. 
18. Quiero ganar el juego al realizar correctamente un determinado número de secuencias.
19. Quiero que la dificultad sea acorde al nivel mostrado en pantalla.
20. Quiero que el nivel aumente cada cinco secuencias correctas. 
```
### _Diagrama conceptual_
A continuación se encuentra el diagrama conceptual que muestra la solución principal del problema a alto nivel: 
![Diagrama conceptual SimonTec](https://user-images.githubusercontent.com/62963679/116627385-4528c900-a90a-11eb-9374-d34a5064d000.png)

### _Diagrama de clases_
El siguiente diagrama de clases se presenta en el formato de Diagrama UML y especifica cada clase utilizada en la implementación de SimonTEC: ![Diagrama](src)

### _Clasificación por criticidad y frecuencia_
```markdown
A continuación se presenta un arreglo que acomoda features del programa SimonTEC entre barras verticales: 

Siempre usado ___________________________________________________________________________________________________________________
               |Abrir ventana de juego|       |   Mostrar color  |         |Mostrar nivel actual|      | Repetir secuencia |       
               |  Frecuencia: alta    |       | Frecuencia: alta |         |  Frecuencia: baja  |      | Frecuencia: media |

                      
               |  Cambio de dificultad  |       | Seleccionar color |            | Añadir color a la secuencia |
               |     Frecuencia: baja   |       | Frecuencia: media |            |       Frecuencia: baja      |
                      
                      
                                               |  Subir de nivel  |
                                               | Frecuencia: media|

                      
               | Ganar el juego  |              | Perder el juego |              
               | Frecuencia: baja|              | Frecuencia: baja|              
              ____________________________________________________________________________________________________________________
Rara vez usado
```
### _Minimal System Span_
```markdown
El Minimal System Span se refiere a los features mínimos que hacen que el programa sea funcional. 
De los features con los que cuenta SimonTEC, su funcionalidad recae en:


```
### _Plan de iteraciones_
```markdown
``` 
