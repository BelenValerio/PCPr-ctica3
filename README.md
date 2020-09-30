# PCPractica3
Es este código se implementa la desactivación de interrupciones
el cual es un método de exclusión mutua el cuál no cumple con las condiciones de competencia
1. Dos procesos no deben encontrarse al mismo tiempo dentro de una SC con el mismo recurso
compartido.
2. No se deben hacer hipotesis sobre la velocidad y numero de CPU. 
3. Ningun proceso que este en ejecución fuera de su secci ´ on crítica puede bloquear a otros
procesos.
4. Ningun proceso debe esperar de manera ilimitada para entrar a su sección críıtica.

Se hace uso de bandera las culaes se activan cuando un proceso esta a su sección crítica
y se desactivan cuando el proceso sale de ella.
