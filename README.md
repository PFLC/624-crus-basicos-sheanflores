# INVESTIGACION DE CRUD

# Que es CRUD?

El código CRUD es una forma de organizar las operaciones básicas que se pueden realizar sobre una base de datos o un sistema de información. CRUD es un acrónimo que significa Create (Crear), Read (Leer), Update (Actualizar) y Delete (Eliminar). Estas operaciones son fundamentales en cualquier sistema de gestión de bases de datos o aplicación que interactúe con datos.

Basicamente se puede describir CRUD en el siguente ejemplo:
Crear: Agregar un nuevo empleado.
Leer: Ver la información de un empleado.
Actualizar: Modificar la información de un empleado.
Eliminar: Borrar un empleado.

![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/671f684c-c225-4175-a7d2-7797d30039e5)

# Su aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHPPHP :** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

# Ejemplo 1

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.
    
# Ejemplo 2

## 1-Crear
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/98d58792-5051-4a90-9dbc-431f5354da0b)

## 2-Leer 
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/3dc0c03a-1950-4f79-97c4-c81325dc5220)


## 3-Modificar
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/6ffc9d71-e90b-45dd-9567-218ba8f8096a)


## 4-Eliminar
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/c49ad314-699c-4ee0-b4ce-852c8a4e8958)


## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Conxion de base de datos con LAMP

Conectarte a una base de datos LAMP (Linux, Apache, MySQL/MariaDB, PHP) desde PHP es un proceso común y relativamente sencillo. Aquí te muestro cómo hacerlo utilizando la extensión MySQLi de PHP, que es una de las opciones más comunes:
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/f81b1f1c-37b1-44af-b4bb-76d3bd9b985f)

Una vez que la conexión se ha establecido con éxito, puedes realizar operaciones CRUD como crear, leer, actualizar y eliminar registros en la base de datos utilizando consultas SQL. Aquí hay algunos ejemplos básicos:

Crear (Create):
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/a900302f-1b04-49eb-8f81-c8a27aad2df4)

Leer (Read):
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/3e170201-4696-45d9-9cb4-689f8219b50d)

Actualizar (Update):
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/4e0844fa-b8d5-4962-af90-b7b1a917fdd0)


Eliminar (Delete):
![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/43e3d298-585c-4665-b486-daa0f345c765)


No olvides cerrar la conexión cuando hayas terminado de trabajar con la base de datos:

![image](https://github.com/PFLC/624-crus-basicos-sheanflores/assets/114175568/c5e8fbc3-0e9c-4ead-8493-22ef21e7217a)

Recuerda reemplazar "localhost", "usuario", "contraseña", "basededatos", "tabla", "campo1", "campo2" y las condiciones con los valores específicos de tu configuración y tu base de datos.
## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

