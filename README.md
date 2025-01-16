Proyecto literAlura 📚

literAlura está creado para los apasionados de la literatura, permitiéndoles buscar, registrar y listar tanto libros como autores. Además, cuenta con funciones avanzadas como listar autores vivos en un año específico y libros por idioma.

-Funcionamiento del Programa
Obtención de Datos: Los libros se obtienen de la API GutenDex.

Conversión a Objetos Java: La clase JsonParser convierte los datos de la API en objetos Java.

Procesamiento: Se procesan los datos para evitar duplicados en la base de datos.

Almacenamiento: Los libros y autores se almacenan en una base de datos SQL compatible (PostgreSQL, MySQL, MariaDB, SQL Server, H2).

-Desafío de Alura
Este proyecto fue desarrollado como respuesta al challenge de Alura, en el cual se nos retó a crear una aplicación moderna para gestionar una base de datos de libros y autores.

-Características 🌟
Buscar libro por título: Localiza libros por su título.

Listar libros registrados: Muestra todos los libros almacenados.

Listar autores registrados: Muestra todos los autores almacenados.

Listar autores vivos en un determinado año: Encuentra autores vivos en un año específico.

Listar libros por idioma: Filtra libros por su idioma.

-Tecnologías Utilizadas 🛠️
Java 11+

Spring Boot 2.6.4

Spring Data JPA

PostgreSQL, MySQL, MariaDB, SQL Server, H2

Jackson

Maven

-Instalación y Ejecución 🚀
Sigue estos pasos para configurar y ejecutar el proyecto localmente:

Prerrequisitos

Java 11 o superior

Maven 3.6 o superior

Una base de datos SQL (PostgreSQL, MySQL, MariaDB, SQL Server, H2)

Clonar el Repositorio

git clone https://github.com/Daveee481/Challenge-Literalura.git

Dependencias Asegúrate de añadir las dependencias necesarias en tu pom.xml para la base de datos que elijas.

Configurar la Base de Datos En application.properties, configura tu base de datos:

Ejecutar la Aplicación En tu IDE, ejecuta LiteraturaApplication. Aparecerá un menú en la consola con las siguientes opciones:

Bienvenidos a literAlura Elija una opción: 1 - Buscar libro por título 2 - Listar libros registrados 3 - Listar autores registrados 4 - Listar autores vivos en un determinado año 5 - Listar libros por idioma 0 - Salir

Selecciona la opción deseada ingresando el número correspondiente y sigue las instrucciones en pantalla.

