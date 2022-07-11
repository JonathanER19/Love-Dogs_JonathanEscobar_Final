# Love-and-Dogs

# Arquitectura - Diseño Proyecto

### :open_file_folder:Client → FrontEnd 
### (HTML, CSS, JS) - React

### :open_file_folder:Server → BackEnd 
### NodeJS - Electron

### :oil_drum:MySQL - Database

# Descripción - Core Proyecto

Este proyecto consiste en un sistema web para la adopcion de perros. La parte logica esta en ciertas
validaciones que se encuentran en un formulario de adopción las cuales deben cumplirse para que cierto 
usuario pueda adoptar un perro.

# Documentación revisada para poder desarrollar este proyecto
Para desarrollar este proyecto me base en tutoriales de React y Node.js
Para el deploy de este proyecto busque información y videos sobre AWS

### React, Node.js
https://www.youtube.com/watch?v=VxRXlUrV6y0
https://www.youtube.com/watch?v=iHqa6ojKnHI

### AWS
https://aws.amazon.com/es/
https://www.youtube.com/watch?v=JZPyVmbDRbo&t=652s
https://www.youtube.com/watch?v=df7soTJ9vW0

# Proyecto Deployado

http://54.164.224.159:3000/

# Flujo del proyecto deployado

### USUARIOS
El sistema contará con un control de usuarios por eso ofrece dos roles a seleccionar:
-Admin (Sera el encargado de administrar el sistema, crear usuarios internamente, registrar mascotas, ver las solicitudes de adopción)
-Cliente (Podra ver el listado de mascotas y adoptar mediante un formulario)

### INICIO DE SESION Y REGISTRO
Como pantalla principal se muestra un login el cual permite iniciar sesión con el rol que haya sido creado. Por otra parte tambien cuenta
con la funcionalidad de registrarse la cual permite crear un usuario unicamente con el rol de cliente.

Para poder iniciar sesión con el rol de administrador ingrese las siguientes credenciales:
Usuario: ### admin@gmail.com
Password: ### 12345

Para iniciar sesíon con el rol cliente se puede registrar en una nueva cuenta en la pantalla principal de login o a su vez se pueda entrar
con las siguientes credenciales:
Usuario: ### vivi@gmail.com
Password: ### 12345

### USUARIO ADMIN
El usuario admin contará con 4 funcionalidades:
1) Registro de mascota: Permite como tal el registro de la mascota (en el campo de imagen solo se maneja por enlaces de imagenes en internet 
asi que se debe pegar la direccion de la imagen ejemplo: https://estag.fimagenes.com/img/2/2/p/n/2pn_900.jpg)
3) Registro admin: Permite como tal el registro de usuarios con el rol de clientes o admin.
4) Listado de mascota: El usuario admin puede ver, modificar y eliminar los perros que se muestran en la lista.  
5) Solicitudes: El usuario admin puede ver las solicitudes que se generan a la hora que un usuario cliente adopta una mascota.

### USUARIO CLIENTE 
El usuario admin contara con una sola funcionalidad:
1) Adoptar un perro de la lista de perros disponibles.


### FUNCION DEL FORMULARIO
Cuando un usuario quiera adpotar un perro y este de clic en adoptar se le abrira un formulario el cual validara lo siguiente:
1) Que su edad este en el rango de 18-80 años.
2) Validacion del tipo de vivienda, si el perro es grande, el usuario a adoptar debera 
  vivir en una casa o finca.
3) Si un usuario adpoto un perro debera espera 3 meses para volver adoptar.
4) Si la ubicacion que se registra en la mascota y la ubicacion del usuario es diferente se le mostrara un mensaje de que la mascota
  no se encuentra en su misma ciudad.
  ### Si el usuario cumple con todos esos requisitos del formulario el usuario podra adoptar sin ningun problema y esa solicitud de adopción
  ### la podra ver el usuario admin.

# Contacto
jonathanes317@gmail.com

0994778946







