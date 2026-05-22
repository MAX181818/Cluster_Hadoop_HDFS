# Cluster_Hadoop_HDFS
Sistema de Ficheros Distribuido Hadoop (HDFS). En su desarrollo, se categorizan y documentan los comandos principales del cluster mediante la ejecucion de ejemplos practicos.


Es un sistema de almacenamiento organizado bajo un modelo de maestro y esclavo. En este sentido, la arquitectura se clasifica en dos partes principales: 

- NameNode que controla el sistema
- Multiples DataNodes que almacenan fısicamente los datos.

Ademas, el sistema replica la informaci´ on en varios equipos; por lo tanto, esta accion causa una alta tolerancia a los fallos tecnicos impidiendo la perdida de informacion.

![Arquitectura general del framework Hadoop: Interacci´on del usuario, procesamiento de tareas y almacenamiento en Big Data.](Cluster_Hadoop_HDFS/Arquitectura_General_Hadoop.png)
