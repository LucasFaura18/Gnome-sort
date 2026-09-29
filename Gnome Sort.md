# GNOME SORT

**Complejidad en el mejor caso:** O(n)

**Complejidad en el peor caso:** O(n²)

**Complejidad en el caso promedio:** O(n²) 

**¿Es adecuado para Big Data? ¿Por qué?**

No, es muy poco eficiente cuando tiene mucho volumen de datos, ya que crece rápidamente y en el peor de los casos tiene que comparar cada elemento con todos los demás.

**Explicación:** 

El algoritmo de ordenamiento del gnomo (Gnome Sort), también conocido como "ordenamiento estúpido" (Stupid Sort), se basa en la idea de un gnomo de jardín ordenando sus macetas. Un gnomo de jardín ordena las macetas siguiendo este método:

Observa la maceta en la que está y la anterior, si están en el orden correcto, avanza una maceta hacia adelante, de lo contrario, las intercambia y retrocede una maceta hacia atrás. Si no hay una maceta anterior (está al principio de la fila de macetas), da un paso hacia adelante, si no hay ninguna maceta delante de él (ha llegado al final de la fila), ha terminado.

[Ejemplo visual](https://sortvisualizer.com/gnomesort/)

