# Documentacion de la API

## URL

/usuario/registro         POST        Crear usuarios

/usuario/login            POST        login de usuarios

/usuarios/{id}            GET         Obtener usuarios

/usuarios/{id}            PATCH       Actualizar usuarios

/usuarios/subirImagen     POST        SubirImagen

/usuarios/obtenerImagen   GET         Obtener Imagen

## Modelos

### Usuario

nombres: String

apellidos: String

correo: String

imagen: String

contrasena: String

privilegio: String
