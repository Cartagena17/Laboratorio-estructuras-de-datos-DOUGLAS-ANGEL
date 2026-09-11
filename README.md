# Laboratorio-estructuras-de-datos-DOUGLAS-ANGEL
Douglas Daniel Cartagena Arauz 20250040
Angel Ricardo Ramos Chicas 20250443

¿Por qué ArrayList o LinkedList NO son aceptables?
R=No son aceptables por el hecho de que en linkedlist lo que se hace es insertar y tambien eliminar datos en ambos extermos que seria al inicio y al final y en este caso no se esta buscando eso, porque al buscar datos lo que pasa es que lo recorre por nodos y tiene que estar buscando dato por dato y en ArrayList se accede por la posición lo cual eso seria ideal ya sea para buscar ya sea en una lista de catalogos de productos y tambien porque puede haber datos duplicados

¿Por que HashSet NO resuelve el problema por si solo?
R=Porque en ese caso si se garantiza que no haya datos duplicados en esa parte tampoco importa el orden y en el caso de iniciar sesion, esa estructura de datos es mas ideal cuando hay correos ya registrados para buscarlos, tambien porque segun el enunciado no se podria ya que nos esta pidiendo clave-valor y en el caso de hashset se puede buscar ya sea con un solo dato o parametro.

¿Por qué TreeMap NO es la opcion ideal?
En treeMap lo que pasa es que en ese caso mantiene sus claves ordenadas automaticamente segun su orden natural o tambien mediante un comparator y tendria que tardar un poco mas para encontrar los datos

¿Cual es la ÚNICA estructura basada en hashing que resuelve todas las operaciones en tiempo promedio constante 0 (1)?
La que hemos encontrado en este caso es la de HashMap ya que ahi se necesita asociar la clave-valor para buscar por clave sin importar el orden, uno de los ejemplos que se puede utilizar esa estructura de HashMap es en este ejercicio, porque se esta asociando para iniciar sesion lo que seria solo el username y el password y asi se puede ir resolviendo los problemas
