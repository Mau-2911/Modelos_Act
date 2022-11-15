![Open in Codespaces](https://classroom.github.com/assets/open-in-codespaces-abfff4d4e15f9e1bd8274d9a39a0befe03a0632bb0f153d0ec72ff541cedbe34.svg)
# Segundo parcial: Curso Simulacion, Otoño 2022

![Grades](https://github.com/ag-classrooms/autograding-r/actions/workflows/classroom.yml/badge.svg)

## Instrucciones del examen 

Resuelve los ejercicios en el documento `Rmd`. Recuerda que el trabajo es
individual. La entrega se realiza como se han realizado las entregas de las
tareas en el curso. Es decir, por medio del repositorio asociado. Puedes usar el 
codespace para realizar la tarea. Pero que no se te olvide realizar los _commits_ y
los _pushes_ al repositorio.

El repositorio contiene un compilador del `rmarkdown`. Esto servirá para detectar cuando 
una entrega es capaz de correr sin problemas. Es decir, será una alerta para saber si 
tu entrega es reproducible o no. En caso de que no sea reproducible perderás un punto 
(corresponde a 10%) de la calificación del parcial. La ponderación será: 

1. Ejercicio de tráfico (_bootstrap_).  50%   
2. Ejercicio de cobertura de intervalos. 50%   

## Recordatorios generales

Para usar la librería de `rsample` para calcular intervalos es *indispensable* que tu estimador regrese `tibbles` con: 

1. tenga una columna que se llama `estimate`; 
2. tenga una columna que se llame `term`; 

## Instrucciones generales para usar `Codespace`

Cada vez que inicies por primera vez un `codespace` (botón `Code` ->
`Codespaces` -> `create codespace`) tendrás que ejecutar los
siguientes pasos para poder garantizar tener un ambiente de trabajo.
1. Desde el archivo de `assignment.Rmd` ejecuta la línea `renv::restore()` y
   acepta instalar todas las librerías correspondientes.
2. En la pantalla del editor aparecerá un cuadro de alerta para
   avisarte que necesitas instalar la librería `languageserver`,
   acepta dicha instalación y cuando termine selecciona la consola
   donde se está ejecutando y dale `enter`.
3. Interrumpe la sesión activa de `R` por medio de la instrucción
   `quit()` en la consola de `R` y acepta ejecutar dicha instrucción.

Si todo sale bien, entonces no tendrás problemas con el editor y los
atajos de autocompletar en los archivos con terminación `.R` o `.Rmd`.
