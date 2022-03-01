# Inteligencia Artificial 2022

Inteligencia Artificial es un término que se escucha ampliamente hoy en día. Sin embargo, es un área del conocimiento que ya tiene varias décadas. Este es un curso introductorio  a la inteligencia artificial, la cual es un área donde se mezclan muchas disciplinas: lógica, programación, matemática, estadística y probabilidad, algoritmos, robótica. Al inicio del curso se hace una revisión histórica de las diferentes áreas y campos de aplicación de la inteligencia artificial, para luego entrar en los temas de lógica proposicional y el sistemas de estados, y el desarrollo de modelos basados en reglas y sistemas expertos. Se hace una revisión de algoritmos de búsqueda como BFS, DFS, y *backtracking*, entre otros, así como el desarrollo de heurísticas y algunos métodos de optimización combinatoria: algoritmos genéticos, evolución diferencial. Luego, combinamos estos conocimientos con el área de probabilidad, para estimar incertidumbre en los modelos. Desarrollaremos métodos de redes bayesianas, y modelos ocultos de Markov. Seguidamente, haremos una introducción al aprendizaje automático, en donde desarrollamos algunos modelos de agrupamiento de datos, clasificación y estimación predictiva. Finalmente, el curso termina con temas de actualidad, como el aprendizaje profundo, en donde implementaremos redes neuronales, principalmente aplicadas a dos campos importantes: visión computacional, y procesamiento del lenguaje, para finalizar con algunos temas de aprendizaje por refuerzo.

El curso requiere madurez por parte del estudiante, pues se integran contenidos de muchos cursos de computación, matemática y estadística. Entre los prerrequisitos se encuentra tener un buen dominio de las técnicas vistan en los cursos de matemática discreta, grafos, autómatas, lógica, programación y algoritmos, cálculo, álgebra lineal, probabilidad y estadística. 


# Programa del curso
<div id='id-programa'/>

[Programa del curso](programa/Programa-ia2022.pdf){:target="_blank"}

### Horario
<div id='id-horario'/>

* Martes y jueves, de 19:50 a 21:30 horas.

### Office Hours
<div id='id-office'/>

* Viernes de 18:00 a 20:00 horas, o por solicitud del estudiante. También pueden enviar sus dudas por correo electrónico.


# Material del curso
<div id='id-material'/>

  **No.**  | **Fecha**    | **Tópicos**                                                                    | **Recursos**
  -------- | ------------ | ------------------------------------------------------------------------------ |  -------------------------------------
  01       | 13.01.2022   | Introducción. Historia de las redes neuronales. <br/> [Aula 01](aulas/Aula01.pdf){:target="_blank"} | 
  02       | 18.01.2022   | Historia de la IA. Estado del arte actual. <br/> [Aula 02](aulas/Aula02.pdf){:target="_blank"} | Russell y Norvig, Capítulo 1.
  03       | 20.01.2022   | Agentes racionales. Clasificación de ambientes. <br/> [Aula 03](aulas/Aula03.pdf){:target="_blank"} | Russell y Norvig, Capítulo 2.
  04       | 27.01.2022   | Métodos de Búsqueda. Representación. <br/> [ Aula 04](aulas/Aula04.pdf){:target="_blank"} [Aula 04 notas](aulas/Aula04_notas.pdf){:target="_blank"} | Russell y Norvig, secciones 3.1 y 3.2.
  T1       | 29.01.2022   |                                                                                | **[Tarea 1](tareas/tarea01.pdf){:target="_blank"}** <br/> **Fecha de entrega: Viernes 04 de febrero.**
  05       | 01.02.2022   | Estrategias de Búsqueda: BFS, DFS, Greedy, Backtracking. <br/> [Aula 05](aulas/Aula05.pdf){:target="_blank"} [Aula 05 notas](aulas/Aula05_notas.pdf){:target="_blank"} | Simulación de Algoritmos *shortest path* <br/> [visualgo.net/en/sssp](https://visualgo.net/en/sssp){:target="_blank"}
  06       | 03.02.2022   | Algoritmos: ruta más corta, árbol de expansión mínima. <br/> [Aula 06](aulas/Aula06.pdf){:target="_blank"} | Simulación de Algoritmos *shortest path* <br/> [cmps-people.ok.ubc.ca/ylucet/DS/Dijkstra.html](https://cmps-people.ok.ubc.ca/ylucet/DS/Dijkstra.html){:target="_blank"}
  07       | 08.02.2022   | Heurísticas. Algoritmo A*. <br/> [Aula 07](aulas/Aula07.pdf){:target="_blank"} | *Pathfinding simulation*: A* y otros. <br/> [https://qiao.github.io/PathFinding.js/visual/](https://qiao.github.io/PathFinding.js/visual/){:target="_blank"}
  T2       | 09.02.2022   |                                                                                | **[Tarea 2](tareas/tarea02.pdf){:target="_blank"}** <br/> **Fecha de entrega: Jueves 24 de febrero.**
  08       | 10.02.2022   | Comentarios sobre heurísticas y A*. <br/>                                      | 
  09       | 15.02.2022   | Búsqueda en espacios continuos.  <br/> [Aula 09](aulas/Aula09.pdf){:target="_blank"} | [Aula 09 notas](aulas/Aula09_notas.pdf){:target="_blank"} 
  10       | 17.02.2022   | Descenso gradiente. *Steepest Descent*. Ejemplos.  <br/> [Aula 10](aulas/Aula10.pdf){:target="_blank"} | [Aula 10 notas](aulas/Aula10_notas.pdf){:target="_blank"} 
  11       | 22.02.2022   | Otros metodos de descenso. Descenso gradiente estocástico.  |                         
  12       | 24.02.2022   | Optimización libre de derivadas. Método de Nelder-Mead. <br/> [Aula 12](aulas/Aula12.pdf){:target="_blank"}  |                        
  13       | 01.03.2022   | Enfriamiento simulado. <br/> [Aula 13](aulas/Aula13.pdf){:target="_blank"}  |                        
  T3       | 01.03.2022   |                                                                                | **[Tarea 3](tareas/tarea03.pdf){:target="_blank"}** <br/> **Fecha de entrega: Martes 15 de marzo.**
  
# Referencias
<div id='id-ref'/>

### Textos:

* [S. Russell y P. Norvig (2021). *Artificial Intelligence: A Modern Approach*.](http://library.lol/main/9B28FC2A4A9B21237063BC7E6B42DEFD){:target="_blank"}

* [W. Ertel (2017). *Introduction to Artificial Intelligence*.](http://library.lol/main/3FA154D019C435DA970C2F19999889A8){:target="_blank"}

### Otras Referencias:

* [El-Ghazali Talbi (2009). *Metaheuristics: From Design to Implementation*. Wiley.](){:target="_blank"}

* [S. Luke (2013). *Essential of Metaheuristics*.](){:target="_blank"}
    
* [A. E. Eiben, J. E. Smith (2003). *Introduction to Evolutionary Computing*. Springer.](){:target="_blank"}

* [T. Bäck (1996). *Evolutionary Algorithms in Theory and Practice: Evolution Strategies, Evolutionary Programming,
Genetic Algorithms*. Oxford University Press.](){:target="_blank"}

* [M. Mitchell (1999). *An Introduction to Genetic Algorithms*. MIT Press.](){:target="_blank"}

* [C. Bishop (2000). *Pattern Recognition and Machine Learning*. Springer.](){:target="_blank"}

* [T. Hastie, R. Tibshirani, J. Friedman (2013). *The Elements of Statistical Learning*. Springer.](){:target="_blank"}
    
* [Daphne Koller, Nir Friedman (2012). *Probabilistic Graphical Models*. MIT Press.](){:target="_blank"}

* [K. Murphy (2012). *Machine Learning: a Probabilistic Perspective*. MIT Press.](){:target="_blank"}


Enlaces a las referencias serán agregadas en breve.
---
