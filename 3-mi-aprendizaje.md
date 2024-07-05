En esta practica, aprendí a definir y configurar múltiples servicios en un archivo compose.yaml.
Entendí que es muy importante establecer correctamente los volúmenes y variables de entorno para asegurar que los servicios funcionen de la manera esperada.

De manera más específica, el manejo de Bases de Datos en contenedores es una de las cosas que aprendí. Entendí cómo configurar y conectar una base de datos PostgreSQL con otro servicio como SonarQube.

También, practiqué el mapeo de puertos entre el host y los contenedores. Por ejemplo, investigué que el puerto 9000 permite acceder al servicio de SonarQube.

Durante la práctica, me encontré con algunos problemas que pude solucionar.

Inicialmente, recibí una advertencia sobre la versión obsoleta en Docker Compose y me saltó un error indicando que el daemon de Docker no estaba corriendo. Leyendo documentación, aprendí que las versiones más recientes de Docker Compose ya no requieren especificar version. Sin embargo, empecé por lo más simple, reinicie el servicio de Docker y con eso funcionó correctamente.
