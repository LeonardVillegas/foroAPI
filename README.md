# Desafío Challenge Back End: ForoHub
En este proyecto, he replicado el funcionamiento de un foro a nivel de back end, creando una API REST usando Spring. La API permite a los usuarios realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre tópicos en el foro.


## Integración de JWT
Para usar JWT, es necesario agregar la biblioteca de Auth0 en el archivo pom.xml de tu proyecto. Puedes obtenerla en JWT.IO.

Generación y validación de tokens
DTO UsernamePasswordAuthenticationToken: Crea una clase DTO para recibir el nombre de usuario y contraseña.
TokenService: Implementa una clase de servicio para gestionar la generación y validación de tokens.
En la clase TokenService, se utiliza la biblioteca JWT para crear tokens con el algoritmo HMAC256 y una contraseña específica. Además, se configura la fecha de expiración del token.