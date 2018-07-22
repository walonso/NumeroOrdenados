Creador: Walter Javier Alonso Roa <walonsor@psl.com.co>
Ubicación en Github: https://github.com/walonso/NumeroOrdenados
Fecha Subida : 22/07/2018 13:54

----------------------------------------------------------------------------------------------------------------------------------
Descripcion:
Un número “ordenado” es un entero en base 10, sin cero a la izquierda, tiene todos sus dígitos ordenados en orden no-descendente. 
Ejemplos: 9, 234, 888, 1578  y 113399. Algunos números que no cumplen esta propiedad: 30, 432, 596 and 88881.

Se requiere un algoritmo que, dado un número N, encuentre el mayor número “Ordenado” presente.
----------------------------------------------------------------------------------------------------------------------------------
Orden: N. 
----------------------------------------------------------------------------------------------------------------------------------
Pasos Para correr el proyecto:

1. Compile el arhivo (g++ >= 4.3)
Comando: g++ -std=c++11 -o ejecutable main.cpp   
2. Reemplace el archivo "entrada.txt" con el archivo de prueba.
3. Ejecute el proyecto.
Comando: ./ejecutable

----------------------------------------------------------------------------------------------------------------------------------
Para compilar el proyecto en DEV C++:
- Habilitar el standar de compilacion C++ 11. 
Ir al menu seleccionar Project -> Project Options, en la ventana emergente ir a compiler -> Code generation
y escojer GNU C++ 11  en Language standar (-std).


