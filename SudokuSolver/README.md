# Solucionador de sudokus
## Descripción
Una aplicación minimalista de Python que resuelve un problema de sudoku dado en un archivo *.csv* siguiendo ciertas *reglas de formato*.

### Reglas de formato para sudokus .txt
- La **primera fila** del archivo *.csv* debe ser la siguiente: `a,b,c,d,e,f,g,h`.
- Las siguientes filas serán los **números** del sudoku dado. El número **cero (0)** representa una celda vacía o *celda desnuda*.
- Los números se separarán con comas, dando formato a las **columnas**.
- Se puede encontrar un ejemplo de archivo *.csv* en la carpeta **ejemplos**.

## Requisitos

Este proyecto utiliza las siguientes bibliotecas externas:
- **NumPy**
- **Pandas**

Para poder ejecutar este proyecto, ejecute: `pip install -r requirements.txt`

## Pasos para la ejecución

- En la carpeta *SudokuSolver*, ejecute: `python3 main.py`
- Se requerirá la ruta para un archivo *.csv* que siga las reglas de formato anteriores. **NO DEBE ESCRIBIR LA EXTENSIÓN .CSV JUNTO AL NOMBRE DEL ARCHIVO**.
- Ejemplo de entrada: **examples/ex2**

## TODOS
- Implemente una **GUI** simple utilizando la biblioteca *tkinter*.
- En la **GUI** mencionada anteriormente, implemente un regulador de velocidad para poder ver cómo el algoritmo prueba, falla y retrocede.