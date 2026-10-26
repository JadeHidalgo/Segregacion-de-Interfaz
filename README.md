# Segregacion-de-Interfaz.
En este proyecto, el principio de segregación de interfaces se aplica mediante la división de los comportamientos en tres interfaces específicas: enviable, que contiene el método enviar(); reemplazable, que contiene el método reemplazar(); y expirable, que contiene el método expirar().
Cada interfaz representa un comportamiento particular y puede ser implementada únicamente por las clases que lo necesitan.
La clase Fisico hereda de Producto, Enviable y Remplazable, ya que un producto físico puede enviarse y reemplazarse, pero no necesita implementar el comportamiento de expiración. Por su parte, la clase Digital hereda de Producto y Expirable, porque puede tener una fecha de vencimiento, pero no necesita las funcionalidades de envío y reemplazo físico.
De esta manera, cada clase implementa únicamente los métodos que corresponden a sus características, evitando dependencias innecesarias.
