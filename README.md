# SOA_HPC

La práctica consiste en la resolución de dos ejercicios utilizando los cuadernos de Colab. Para el
primer ejercicio, la cátedra asignará la funcionalidad a implementar. Para el ejercicio 2, la
funcionalidad es libre, siempre que esté encuadrada en HPC (GPU, OpenMP y MPI).

## Ejercicio 1

* El fin del ejercicio implementado en Python: es comparar y analizar la ejecución en forma
secuencial (solo usando CPU) y su versión paralela (con CUDA).

* Se debe confeccionar un solo cuaderno en Colab que tenga las secciones:
  
  - Introducción: Debe explicar la base teórica de la funcionalidad pedida.
  
  - Armado del ambiente: En esta sección deben estar todos los comandos
  previos, que son necesarios para la ejecución del ejercicio.
  
  - Desarrollo CPU: Debe tener el código que resuelve el ejercicio desde el punto
  de vista secuencial.
  
  - Desarrollo GPU: Debe tener el código que resuelve el ejercicio desde el punto
  de vista optimizado con CUDA.
  
  - Métricas: Se recompilará la información obtenida de la ejecución secuencial y
  paralela.
  
  - Conclusiones: Explicación de las métricas obtenidas y sus comparaciones.
  
  - Bibliografía: Toda referencia utilizada para confeccionar el ejercicio (incluyendo
  el código si tomaron la idea de otro lado).

* Se pide que en la versión del GPGPU se implemente en CUDA. Que se desarrolle la
funcionalidad del Kernel (no es válido utilizar bibliotecas externas que lo resuelvan).
Tenga en cuenta que Kernel debe ejecutar sobre dos dimensiones. Se recomienda usar
el tipo de memoria Imagen (no vector).

* Que el ejercicio sea parametrizable y que tenga manejo de excepciones.

* Para poder responder y verificar las preguntas del informe, lo pueden desarrollar en una
sección aparte o en otro cuaderno, invocando al desarrollo con diferentes parámetros.

* La funcionalidad a aplicar, se asignará en clase por medio de algoritmo aleatorio
(¡lotería!). Esta funcionalidad puede tener complejidad baja o mediana, que requiere
aplicar a una imagen una función de conversión o una matriz de conversión:

  - Low pass filter.

  - High pass filter.

  - Sobel filter.

  - Contrast filter.

  - Brightening filter.

  - Darkening filter.

  - Mean filter.

  - Tone Mapping.

  - Box blur.

  - Escala de imagen (aplicar por factor en punto flotante).

  - Escala de la imagen (reducir por factor en punto flotante).

  - Girar imagen (indicando los grados).

  - Translación de imagen (x, y).

  - Adición de 2 imágenes

  - Diferencia de 2 imágenes.

  - Inversión de color.

## Ejercicio 2

El objetivo del ejercicio es investigar sobre las funcionalidades que brinda Python y Colab
aplicando los conceptos de HPC.
  
* El tema del ejercicio es libre, mientras que aplique a HPC (volumen de datos –
complejidad del algoritmo) y los recursos que provee Python y Colab. Pueden utilizarse
bibliotecas de terceros.

* Que los ejercicios sean reales y originales (manteniendo el sustento teórico). No debe
ser solo un ejemplo de internet o idea compartida entre otros trabajos.

* Se debe confeccionar un solo cuaderno en Colab que tenga las secciones:

  - Introducción: Debe explicar la base teórica de la funcionalidad presentada.
  Tips: Que parte del tema HPC están cubriendo.

  - Armado del ambiente: En esta sección deben estar todos los comandos
  previos, que son necesarios para la ejecución del ejercicio.

  - Desarrollo: Debe tener la explicación y el código que resuelve el ejercicio
  propuesto.

  - Métricas: (solo si corresponde) Se recompilará la información obtenida de la
  ejecución secuencial y paralela.

  - Conclusiones: Palabras finales sobre la idea presentada.

  - Bibliografía: Toda referencia utilizada para confeccionar el ejercicio.
  (incluyendo el código si tomaron la idea de otro lado).

5. Que el ejercicio sea parametrizable y que tenga manejo de excepciones.
