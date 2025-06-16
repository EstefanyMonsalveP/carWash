# CarWash - Sistema de Gestión para Lavadero de Autos 🚗🧼

Este proyecto es una aplicación web diseñada para gestionar las operaciones básicas de un lavadero de autos, facilitando el control de clientes, vehículos y facturación y PQRS.

## ✨ Funcionalidades

- Registro y gestión de clientes
- Ingreso y control de vehículos
- Creación y consulta de facturas
- Ingreso y gestión de PQRS
- CRUD completo en todos los módulos
- Comunicación entre frontend y backend mediante CORS

## 🛠️ Tecnologías utilizadas

- **Backend:** C# con .NET Framework 4.8 (API REST)
- **Frontend:** ASP.NET , JS, CSS, HTML
- **Base de datos:** SQL Server
- **Comunicación:** CORS habilitado entre cliente y servidor

## 🗂️ Estructura del Proyecto

├── BackEnd/ # Lógica del servidor y controladores
├── FrontEnd/ # Interfaz del usuario con ASP.NET
├──.gitignore #Archivos y carpetas que no deben subirse al repositorio
└── README.md # Descripción del proyecto

## 🚀 Estado del proyecto

Este proyecto fue desarrollado inicialmente en colaboración con un compañero como parte de un trabajo universitario, y actualmente está en fase de finalización de forma individual.

##🛠️ Cómo ejecutar el proyecto

1. Clonar el repositorio:
git clone https://github.com/EstefanyMonsalveP/carWash.git
cd carWash

## 🗂️ Configuración de la base de datos

1. Ejecutar el script de base de datos
   - Ubica y descarga el archivo carWashDatabase.sql en la carpeta /Database.
   - Ejecuta el script en SQL Server (puedes usar SQL Server Management Studio).
   Esto creará la base de datos y las tablas necesarias para el funcionamiento de   la aplicación.

2. Actualizar la configuración en el Backend
   - Abre el archivo de configuración web.config.
   - Ubica la sección <connectionStrings>.
   - Modifica la propiedad *data source* para que apunte a tu propio servidor SQL Server
   - Asegúrate de usar la configuración de autenticación correcta según tu entorno: 

*Autenticación de Windows(Por defecto): data source=TU_SERVER-NAME;initial catalog=LAVADERO;integrated security=True;

*Si usas autenticación con usuario y contraseña (SQL Auth):
data source=TU_TU_SERVER-NAME;initial catalog=LAVADERO;User ID=tu_usuario;Password=tu_contraseña;

3. Ejecutar los proyectos
  - Dentro de las carpetas /FrontEnd y /Backend encontraras los archivos con extensión .sln. 
  - Abre ambos proyectos en visual studio  y ejecútalos simultáneamente para el correcto funcionamiento de la aplicación.


## 👩‍💻 Autora

Estefany Monsalve  
Tecnóloga en Desarrollo de Software 
[GitHub](https://github.com/EstefanyMonsalveP)