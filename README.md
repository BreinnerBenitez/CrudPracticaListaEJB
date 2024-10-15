## Proyecto CRUD de Empleados practica en lista

Este proyecto es un ejemplo de una aplicación web CRUD (Crear, Leer, Actualizar, Borrar) para la gestión de empleados. La particularidad de esta aplicación es que utiliza una **lista en memoria** (`List<String[]>`) para almacenar los datos de los empleados en lugar de una base de datos tradicional. Esto permite realizar operaciones CRUD de manera sencilla y eficiente, aunque los datos no persisten después de que la aplicación se detiene.

### Características del proyecto:

- **Agregar Empleados:** Un formulario para añadir nuevos empleados con código, nombre y cargo.
- **Actualizar Empleados:** La posibilidad de modificar los datos existentes de un empleado.
- **Eliminar Empleados:** Opción para borrar empleados de la lista.
- **Visualización de Empleados:** Los empleados se visualizan en una tabla en la interfaz de usuario.
  
### Tecnologías utilizadas:

- **Java EE** con servlets y JSP para la lógica del servidor.
- **EJB (Enterprise JavaBeans)** para la gestión de la lógica de negocio.
- **Listas en Java** (`List<String[]>`) para almacenar los datos de los empleados.
- **HTML/CSS** para la interfaz de usuario.

### Vista de la aplicación:

A continuación se muestra una captura de pantalla de la página `mostrarDatos.jsp`, donde se visualiza la lista de empleados.

![Captura de pantalla de mostrarDatos.jsp](ruta/a/tu/captura.png)

### Cómo usar este proyecto

1. Clona este repositorio en tu máquina local.
2. Despliega la aplicación en un servidor compatible con Java EE, como **GlassFish**.
3. Abre el navegador web y navega a la URL del proyecto.
