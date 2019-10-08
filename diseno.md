Análisis de Tweets en Colombia relacionados con PAZ
Natalia Jaramillo - njaram15@gmail.com
Sebastián Palacio Arango - sebaspalacio@gmail.com

El objetivo es sacar conclusiones sobre las frecuencias de las palabras en los tweets de Colombia que tienen que incluyen la palabra PAZ en el 2019

Los requerimientos técnicos son: Acceso a los datasets de Tweets de Colombia de 2019, elección de lenguaje a emplear, acceso a al cluster para pruebas. 

1.	Entender bien el problema
2.	DIseñar e Implementar un algoritmo secuencial  (dependiendo de la opción) en C o python en forma secuencial, tomar el tiempo de procesamiento (Ts)
3.	Diseñar e implementar el algoritmo paralelo en el paradigma o combinación de ellos, según sea el caso (OpenMP, MPI, CUDA-GPU, etc). Hallar el tiempo de procesamiento paralelo con diferentes recursos (Tp(P)) y hallar el SpeedUp y Eficiencia.
4.	Diseñar e implementar el algoritmo paralelo combinando MPI, OpenMP, coprocesamiento:
a.	Aplicar la técnica de diseño de algoritmo PCAM, en donde defina claramente el mecanismo de particionamiento (funcional y/o datos), mecanismos de comunicación entre tareas, optimización o aglomeración y finalmente el mapeo a unidades de ejecución (cores de procesamiento).
b.	Determinar un balance entre partes del algoritmo que se desarrollarán en OpenMP, coprocesamiento y partes con MPI.
c.	Realizar el análisis del SpeedUp y eficiencia para varios escenarios de recursos.
5.	Implementar el algoritmo en la plataforma MPI dispuesta para el curso. (192.168.10.40 con su usuario de la vpn y clave asignada)
6.	Realizar el análisis de rendimiento con varios números de procesadores (1: secuencial, paralelo: 2, 3 y 4 procesadores). SpeedUp y Eficiencia. Hacer conclusiones.


Referencias:

http://www.scielo.org.mx/scielo.php?script=sci_arttext&pid=S0188-25032018000100115

http://analytics.stradata.co/2016/09/29/analisis-opinion-estadistico-del-plebiscito-para-la-paz-en-colombia/

https://revistas.usb.edu.co/index.php/Agora/article/view/3229

