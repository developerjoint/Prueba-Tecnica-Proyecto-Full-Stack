# Prueba Tecnica Proyecto Full Stack

Muchas gracias por tu interés en hacer parte de este curso, debido a que tenemos cupos limitados y a una alta demanda de aspirantes, nos vemos en la necesidad de hacer una prueba técnica para evaluar tus competencias en la lógica de programación. Esta prueba está diseñada para ser realizada en poco tiempo. A continuación te dejo las instrucciones para ser realizada, y los problemas a resolver.

### Instrucciones

- Podrá utilizar el lenguaje de programación de su preferencia.
- Tendrá dos opciones de envío de la prueba técnica.
  1. Subir el código a un archivo .txt y adjuntarlo al formulario de envío de la prueba.
  2. Subirlo a un repositorio de GitHub y adjuntar el link en un archivo .txt que posteriormente será adjuntado al formulario de envío.
  
 - Se valorará la forma en que llego a la solución del caso.
 - Se valorará la utilidad de los comentarios que utilicé en el código.
 - Se debe adjuntar una breve explicación de la solución, si lo prefiere puede ser en un comentario dentro del código o en un archivo aparte .txt.
 - El plazo para enviar la prueba es hasta el día 17/02/2023 a las 12:00 PM, se valorará la eficiencia para el envío de la prueba. 
 
 ## Caso número 1
 
HackerLand University has the following grading policy:

* Every student receives a grade in the inclusive range from 0 to 100.

* Any grade less than 40 is a failing grade.

Sam is a professor at the university and likes to round each student's grade according to these rules:

* If the difference between the grade and the next multiple of 5 is less than 3, round grade up to the next
multiple of 5.

* If the value of grade is less than 38, no rounding occurs as the result will still be a failing grade.

### Examples

* grade = 84 round to 85 (85 - 84 is less than 3)

* grade = 29 do not round (resultis less than 40)

* grade = 57 do not round (60 - 57 is 3 or higher)

Given the initial value of grade for each of Sam's n students, write code to automate the rounding process.

### Function Description

Complete the function gradingStudents ín the editor below.

gradingStudents has the following parameter(s);

* int grades[n]: the grades before rounding

### Returns

e int[n]: the grades after rounding as appropriate

### Input Format

The first line contains a single integer, n, the number of students. Each line of the n subsequent lines contains a single integer, **grade[i].**

### Constraints
* 1 < n < 60

* 0 < gradesf[i] < 100

### Sample Input 0

```
4
73
67
38
33
```

### Sample Output 0

```
75
67
40
33
```

### Explanation 0

![tabla](https://user-images.githubusercontent.com/125691306/219765194-a7cb7676-4dbd-4ec9-b632-7203d2b22d90.png)


1. Student 1 received a 73, and the next multiple of 5 from 73 is 75. Since 75 — 73 < 3, the student's grade is rounded to 75.

2. Student 2 received a 67, and the next multiple of 5 from 67 is 70. Since 70 — 67 = 3, the grade will not be modified and the student's final grade is 67.

3. Student 3 received a 38, and the next multiple of 5 from 38 is 40. Since 40 — 38 < 3, the student's grade will
be rounded to 40.

4. Student 4 received a grade below 33, so the grade will not be modified and the student's final grade is 33.

## Caso número 2

¿Por que crees que es importante crear una línea de atención dentro de la página web de la universidad que tenga un enfoque en casos basados en violencia de género?

 
 
