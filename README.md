# Portfolio-Curso-Objetos

## Aplicaciones
Todas las aplicaciones cuentan con modelo de capas(IGU, Logica y Persistencia). Si cuentan con conexión a base de datos MySQL, funcionara el metodo CRUD que tiene implementado con ayuda de la JPA Controller seteado. 

### [Peluquería Canina](https://github.com/Moortin35/Portfolio-Curso-Objetos/tree/main/peluqueriaCanina/src/main/java/com/mycompany/peluqueriacanina)
Aplicación de peluquería canina donde se registra a mascotas y sus respectivos dueños. Se pueden agregar, editar, eliminar y consultar mascotas.

### [Concesionaria de Autos](https://github.com/Moortin35/Portfolio-Curso-Objetos/tree/main/Concesionaria/src/main/java/com/mycompany/concesionaria)
Aplicación de concesionaria de autos, se puede dar altas de vehiculos con su modelo e información. También implementado el metodo CRUD.

### [Login Basico](https://github.com/Moortin35/Portfolio-Curso-Objetos/tree/main/LoginBasico/src/main/java/com/mycompany/login)
Aplicación sencilla de login, donde se pueden registrar usuarios y son importados a la base de datos, y cuando en la pantalla principal ingresan, informa en una caja de información si el usuario se ha podido loguear correctamente. Solo tiene implementado el ALTA de usuarios.

### [Sistema de Roles de Usuarios(Login completo)](https://github.com/Moortin35/Portfolio-Curso-Objetos/tree/main/Login/src/main/java/com/mycompany/login)
Aplicación de creación y modificación de usuarios con permisos administrativos. Hay 2 tipos de usuarios, donde un rol es administrador, y si se loguea un admin, accede a una interfaz de creación, edición, eliminación y consulta de usuarios a traves de una tabla. Mientras que el usuario común al acceder solo puede ver la consulta de usuarios en la tabla. También cuenta con el registro de usuarios corrientes.