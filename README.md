El proyecto "ESTACIONAMIENTO" es una aplicación web para la gestión de un estacionamiento, que permite a los usuarios registrarse, iniciar sesión y administrar los espacios de estacionamiento. Aquí hay una descripción de su funcionamiento y estructura basada en los archivos clave del proyecto:

### Descripción del Proyecto
El proyecto se enfoca en gestionar los espacios de estacionamiento a través de una interfaz web. Los usuarios pueden registrarse, iniciar sesión y realizar operaciones relacionadas con el estacionamiento, como registrar, modificar, ver y eliminar espacios de estacionamiento.

### Estructura del Proyecto
1. *Archivos Principales:*
   - index.php: Página de inicio donde los usuarios pueden iniciar sesión o registrarse.
   - conexion.php: Archivo para la conexión a la base de datos.
   - parking_tabla.php: Página principal donde se muestra la tabla de espacios de estacionamiento.
   - usuario_login.php: Script para manejar el inicio de sesión de los usuarios.
   - usuario_registrar.php: Script para manejar el registro de nuevos usuarios.

2. *Archivos de Estilos y Scripts:*
   - css/style.css: Archivo CSS para los estilos de la aplicación.
   - scripts.js: Archivo JavaScript para funcionalidades adicionales en el frontend.

3. *Subdirectorios:*
   - parking/: Contiene scripts PHP para gestionar las operaciones CRUD (crear, leer, actualizar, eliminar) de los espacios de estacionamiento.
     - parking_eliminar.php
     - parking_modificar.php
     - parking_registrar.php
     - parking_ver.php

### Funcionamiento del Proyecto
1. *Registro de Usuarios:*
   - Los usuarios pueden registrarse a través de un formulario en index.php, enviando los datos a usuario_registrar.php, que verifica si el correo ya está registrado y, si no es así, inserta el nuevo usuario en la base de datos.

2. *Inicio de Sesión:*
   - Los usuarios pueden iniciar sesión desde index.php, enviando los datos a usuario_login.php, que verifica las credenciales y, si son correctas, redirige al usuario a parking_tabla.php.

3. *Gestión de Estacionamiento:*
   - Después de iniciar sesión, los usuarios pueden ver la tabla de espacios de estacionamiento en parking_tabla.php.
   - Los usuarios pueden agregar nuevos espacios de estacionamiento utilizando parking_registrar.php, modificar espacios existentes con parking_modificar.php, ver detalles con parking_ver.php y eliminar espacios con parking_eliminar.php.

### Conclusión
Este proyecto es una aplicación web básica para la gestión de estacionamientos, utilizando PHP y MySQL para la lógica del servidor y el almacenamiento de datos, junto con HTML, CSS y JavaScript para la interfaz de usuario
