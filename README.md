Taller ASP.NET

-Caracteristicas principales-

    Aplicación web construida con ASP-NET Core MVC.
    Autenticación de usuarios (cada usuario accede a su cuenta).
    Gestión de listas de tareas personalizadas por usuario.
    Funcionalidades CRUD:
    Crear nuevas tareas.
    Leer y visualizar tareas.
    Actualizar tareas existentes.
    Eliminar tareas.
    Filtrado por prioridad y orden para organizar las tareas.
---------------------------------------------------------------------
-Instrucciones para ejecutar el proyecto-
1.- Clonar repositorio

       git clone

2.- Abrir el proyecto
Abre la solución en Visual Studio.

3.- Configurar la base de datos.
Actualiza la cadena de conexion appsetings.json segun su entorno
Ejecuta alas migraciones:
    
    dotnet ef database update

4.- Ejecuta la aplicación


    dotnet run

---------------------------------------------------------------------
Tecnologias utilizadas 
-ASP.NET Core 7.0
-Entity Framework Code
-SQLite
-Bootstrap para diseño responsivo

---------------------------------------------------------------------

Estructura del proyecto.
Taller ASP.NET Core/
│
├── Controllers/        # Controladores MVC
├── Models/             # Modelos de datos
├── Views/              # Vistas Razor
├── wwwroot/            # Recursos estáticos (CSS, JS)
├── appsettings.json    # Configuración
└── README.md           # Documentación del proyecto
