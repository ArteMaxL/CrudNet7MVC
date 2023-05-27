## Documentación de la Aplicación de Contactos

### Descripción
La Aplicación de Contactos es una aplicación web desarrollada en .NET 7 utilizando el patrón de diseño Modelo-Vista-Controlador (MVC). Permite al usuario gestionar una lista de contactos, realizar operaciones de creación, lectura, actualización y eliminación de contactos, y mantener información detallada como nombre, teléfono, celular y correo electrónico para cada contacto.

### Requisitos del Sistema
-** Windows 10 o versión posterior
-** .NET 7 Runtime instalado
- **Navegador web moderno (Chrome, Firefox, Edge, etc.)
- **Tecnologías Utilizadas
- **.NET 7
- **ASP.NET Core MVC
- **Entity Framework Core
- **HTML5
- **CSS3
- **C#
- **SQL Server (opcional, se puede usar otro proveedor de bases de datos compatible con Entity Framework Core)

### Instalación
1. Descarga el archivo de la aplicación desde [enlace de descarga] e extrae el contenido en tu directorio de trabajo preferido.
2. Abre el proyecto en tu IDE de desarrollo favorito (por ejemplo, Visual Studio 2022).
3. Restaura las dependencias y paquetes de NuGet utilizados en el proyecto.
4. Configura la conexión a la base de datos en el archivo appsettings.json si estás utilizando SQL Server o en el archivo de configuración correspondiente a tu proveedor de bases de datos elegido.
5. Compila la aplicación para asegurarte de que no hay errores.

### Configuración
La aplicación no requiere configuración adicional. Sin embargo, asegúrate de que la cadena de conexión a la base de datos sea correcta y de que la base de datos esté creada antes de ejecutar la aplicación.

### Uso
1. Inicia la aplicación desde tu IDE de desarrollo o ejecutando el archivo binario generado.
2. Abre tu navegador web y visita la URL http://localhost:port, donde port es el número de puerto en el que se ejecuta la aplicación (por defecto, 5000).
3. Serás redirigido a la página principal de la aplicación, donde verás una lista de contactos existentes (si los hay).
4. Para crear un nuevo contacto, haz clic en el botón "Agregar Contacto" y completa los campos requeridos (nombre, teléfono, celular y correo electrónico). Luego, haz clic en "Guardar".
5. Para editar un contacto existente, haz clic en el enlace "Editar" junto al contacto que deseas modificar. Actualiza los campos necesarios y haz clic en "Guardar" para aplicar los cambios.
6. Para eliminar un contacto, haz clic en el enlace "Borrar" junto al contacto que deseas eliminar. Se mostrará un mensaje de confirmación y, si confirmas, el contacto se eliminará de la lista.
7. Puedes buscar contactos por nombre utilizando el campo de búsqueda en la parte superior de la página. Escribe el nombre del contacto que deseas buscar y presiona Enter para ver los resultados filtrados.
8. Puedes ordenar la lista de contactos haciendo clic en los encabezados de las columnas. Haz clic una vez para ordenar de forma ascendente y haz clic nuevamente para ordenar de forma descendente.
9. Para cerrar la aplicación, simplemente cierra la ventana del navegador o detén la ejecución del programa desde tu IDE.
