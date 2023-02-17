
Descripción
El prestigioso centro médico dental de Ñuñoa le ha encargado la tarea de obtener información estadística acerca de las consultas dentales que realizó durante el día de ayer. Para esto, se le entregará un listado de las consultas realizadas. El listado, contiene una tabla con las siguientes columnas: hora de atención, médico especialista, nombre del paciente, Rut del paciente y previsión (Fonasa o Isapre).
Las información debe ser desplegada en una página HTML que usted debe crear. Puede utilizar la función ​document​.write() ​y desplegar la información solicitada entre párrafos, o como usted estime conveniente, lo importante es que la información que se le solicite se muestre en dicha página que creará.
Ejemplo:
​document​.write(​'<p>Estadisticas centro médico ñuñoa</p>'​);
Requerimientos
1. Crear la estructura de datos mediante arreglos y objetos. Debe crear 1 arreglo por cada listado (Radiología, Traumatología y Dental) y 1 objeto por cada fila de información que contengan los listados, considerando las propiedades establecidas en la descripción.
2. Mostrar por pantalla la primera y última atención de cada listado, desplegando el nombre del paciente junto con la previsión, separados por un guión (utilizar índices de arreglos para esto).
Ej: Primera atención: Juan Pérez - Fonasa | Última atención: Ana Gálvez - Isapre.
3. Recorrer el arreglo y mostrar su contenido en una tabla.