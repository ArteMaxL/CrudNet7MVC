## Documentaci�n de la Aplicaci�n de Contactos

### Descripci�n
La Aplicaci�n de Contactos es una aplicaci�n web desarrollada en .NET 7 utilizando el patr�n de dise�o Modelo-Vista-Controlador (MVC). Permite al usuario gestionar una lista de contactos, realizar operaciones de creaci�n, lectura, actualizaci�n y eliminaci�n de contactos, y mantener informaci�n detallada como nombre, tel�fono, celular y correo electr�nico para cada contacto.

### Requisitos del Sistema
-** Windows 10 o versi�n posterior
-** .NET 7 Runtime instalado
- **Navegador web moderno (Chrome, Firefox, Edge, etc.)
- **Tecnolog�as Utilizadas
- **.NET 7
- **ASP.NET Core MVC
- **Entity Framework Core
- **HTML5
- **CSS3
- **C#
- **SQL Server (opcional, se puede usar otro proveedor de bases de datos compatible con Entity Framework Core)

### Instalaci�n
1. Descarga el archivo de la aplicaci�n desde [enlace de descarga] e extrae el contenido en tu directorio de trabajo preferido.
2. Abre el proyecto en tu IDE de desarrollo favorito (por ejemplo, Visual Studio 2022).
3. Restaura las dependencias y paquetes de NuGet utilizados en el proyecto.
4. Configura la conexi�n a la base de datos en el archivo appsettings.json si est�s utilizando SQL Server o en el archivo de configuraci�n correspondiente a tu proveedor de bases de datos elegido.
5. Compila la aplicaci�n para asegurarte de que no hay errores.

### Configuraci�n
La aplicaci�n no requiere configuraci�n adicional. Sin embargo, aseg�rate de que la cadena de conexi�n a la base de datos sea correcta y de que la base de datos est� creada antes de ejecutar la aplicaci�n.

### Uso
1. Inicia la aplicaci�n desde tu IDE de desarrollo o ejecutando el archivo binario generado.
2. Abre tu navegador web y visita la URL http://localhost:port, donde port es el n�mero de puerto en el que se ejecuta la aplicaci�n (por defecto, 5000).
3. Ser�s redirigido a la p�gina principal de la aplicaci�n, donde ver�s una lista de contactos existentes (si los hay).
4. Para crear un nuevo contacto, haz clic en el bot�n "Agregar Contacto" y completa los campos requeridos (nombre, tel�fono, celular y correo electr�nico). Luego, haz clic en "Guardar".
5. Para editar un contacto existente, haz clic en el enlace "Editar" junto al contacto que deseas modificar. Actualiza los campos necesarios y haz clic en "Guardar" para aplicar los cambios.
6. Para eliminar un contacto, haz clic en el enlace "Borrar" junto al contacto que deseas eliminar. Se mostrar� un mensaje de confirmaci�n y, si confirmas, el contacto se eliminar� de la lista.
7. Puedes buscar contactos por nombre utilizando el campo de b�squeda en la parte superior de la p�gina. Escribe el nombre del contacto que deseas buscar y presiona Enter para ver los resultados filtrados.
8. Puedes ordenar la lista de contactos haciendo clic en los encabezados de las columnas. Haz clic una vez para ordenar de forma ascendente y haz clic nuevamente para ordenar de forma descendente.
9. Para cerrar la aplicaci�n, simplemente cierra la ventana del navegador o det�n la ejecuci�n del programa desde tu IDE.
