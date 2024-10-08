## Cuello de Botella de Von Neumann
---
El cuello de botella es el resultado de usar solamente una sola ruta para el intercambio de datos a causa de la diferencia de velocidades entre la memoria y el procesador. Al no poder acceder a los datos en la velocidad que lo requiere, el procesador termina esperando y genera un caída en el rendimiento del sistema (lo torna mas lento). *[throughput](https://es.wikipedia.org/wiki/Tasa_de_transferencia_efectiva)*
#### Soluciones

- **Prefetch** %% busqueda anticipada de instrucciones %%
- **Memoria Caché**
- **[Pipeline de instrucciones](#Pipeline)**%% paralelismo a nivel de instrucciones %%
# Pipeline %% del ingles, tuberia %%
---
Cada etapa del ciclo de instrucción se ejecuta en un ciclo de clock, ejecutar una instrucción demanda 5 ciclos de clock.

![[Pasted image 20240905171535.png]]

Resulta util para acumular/superponer en el tiempo la ejecucion de varias instrucciones a la vez

### *Linea de Montaje*

![[Pasted image 20240905171705.png]]

- Los bloques funcionales trabajan en paralelo operando en forma simultanea pero cada uno en una instruccion diferente
- El **pipeline** no reduce el tiempo de ejecucion de cada instruccion individual, sino que al aplicarse en paralelo al flujo de instrucciones, incrementa el numero de instrucciones completadas por unidad de tiempo. %% se hace uso de la misma cantidad de tiempo para los procesos pero consiguiendo una mayor cantidad de resultados %%
- Este concepto es conocido como **Paralelismo a Nivel de Instrucciones ILP (Instruction Level Paralelism)**