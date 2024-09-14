# CRUD MVC - ASP.NET, Entity Framework, SQL

Este proyecto es una aplicación CRUD (Crear, Leer, Actualizar, Eliminar) desarrollada utilizando ASP.NET Core MVC, Entity Framework Core y SQL Server. 

## Descripción

Esta aplicación demuestra cómo construir una aplicación web utilizando el patrón MVC (Modelo-Vista-Controlador) con ASP.NET Core, integrando Entity Framework Core para el manejo de datos y SQL Server como sistema de gestión de bases de datos. La aplicación permite realizar operaciones básicas CRUD sobre un conjunto de datos.

## Tecnologías Utilizadas

- **ASP.NET Core MVC**: Framework para desarrollar aplicaciones web basadas en el patrón MVC.
- **Entity Framework Core**: ORM (Object-Relational Mapper) para interactuar con la base de datos de manera eficiente.
- **SQL Server**: Sistema de gestión de bases de datos relacional.

## Instalación

1. **Clona el repositorio**:
    ```bash
    git clone https://github.com/tu-usuario/tu-repo.git
    ```
2. **Navega al directorio del proyecto**:
    ```bash
    cd tu-repo
    ```
3. **Restaurar los paquetes NuGet**:
    ```bash
    dotnet restore
    ```
4. **Ejecutar las migraciones de Entity Framework**:
    ```bash
    dotnet ef database update
    ```
5. **Iniciar la aplicación**:
    ```bash
    dotnet run
    ```

## Uso

1. **Navega a la aplicación** en tu navegador: `http://localhost:5000`.
2. **Accede a las diferentes secciones** para crear, leer, actualizar y eliminar datos.

## Estructura del Proyecto

- **Controllers**: Contiene los controladores de la aplicación.
- **Models**: Contiene las clases de modelo que representan los datos y la lógica de negocio.
- **Views**: Contiene las vistas Razor que definen la interfaz de usuario.
- **Data**: Contiene la configuración de Entity Framework y la conexión a la base de datos.
