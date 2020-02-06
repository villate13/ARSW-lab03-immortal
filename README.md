# ARSW-lab03-immortal

### Juan Villate

# Parte I

 1) Revise el funcionamiento del programa y ejecútelo. ejecute jVisualVM..
   ![Consumo CPU programa normal](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/captureMonitoreoParte1Inicio.png)
 
 2) Haga los ajustes necesarios para que la solución use más eficientemente la CPU...
 
![Consumo eficiente de CPU](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/captureProceso2Parte1.3.png)

![Consumo eficiente de CPU2](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/ccaptureProceso2Parte1.png)

 3) Haga que ahora el productor produzca muy rápido, y el consumidor consuma lento...
 
 ![Consumo Produce mas rapido](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/captureProceso3Parte1.png)

 ![Consumo Produce mas rapido](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/captureProceso3Parte1.2.png)

# Parte I

  Programa funcionando.
  
  ![Consumo Produce mas rapido](https://github.com/villate13/ARSW-lab03-immortal/blob/master/img/captureParte2Proceso.png)
 
### PREGUNTAS:

#### PARTE 1
   1) Razon del consumo?
   - La razon del consumo de la CPU es por producir muy lento y el consumidor consume rapido generando una mayor cantidad de      ejecuciones en un tiempo.
   2) Clase responsable del consumo?
   la clase responsable por el consumo es el CONSUMER ya que es la clase que siempre procesa
   
#### PARTE 2
   1) Valor de puntos de vida?
   -El valor de vida el cual comienza un inmortal es de 100, la invariante seria N*100
   3) Funcionamiento de 'pause and check', se cumple la invariante?
   -Al iniciar la aplicacion y en probar la funcion 'pause and check' vemos que la invariante no se cumple
