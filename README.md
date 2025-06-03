## Acerca de este proyecto

Proyecto de ejemplo creado para la clase de desarrollo de aplicaciones móviles para Android, con el objetivo de crear una pequeña API con un CRUD simple para demostrar los diferentes verbos de HTTP y mostrar como consumir el API desde un cliente o una aplicación esterna. No contiene autenticación, solo para fines demostrativos

### EndPoints de la API

- **http://127.0.0.1:8000/api/projects** Por método **GET** devuelve todos los registros de la tabla projects.
- **http://127.0.0.1:8000/api/projects/projects** Por el método **POST** crea un nuevo registro en la tabla de projects el la base de datos.
- **http://127.0.0.1:8000/api/projects/{id}** Por el método **GET** devuelve un registro por su id.
- **http://127.0.0.1:8000/api/projects/{id}** Por el método **PATCH** actualiza un registro específico por su id.
- **http://127.0.0.1:8000/api/projects/{id}** Por el método **DELETE** elimina un registro específico por su id.

### Datos requeridos por el API
Los datos requeridos por el API para los métodos HTTP de POST y PATCH son **name** y **description**.

Ejemplo en JSON:
```
{
  "name": "Project name",
  "description": "Project description"
}
```


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
