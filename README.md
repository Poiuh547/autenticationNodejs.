# autenticationNodejs.

Este programa realiza la autenticación de Usuarios y un proceso de acceso a cuentas, primero se hace el registro del usuario, y seguido,
el usuario podrá acceder en una pestaña Login y Register. 

Se utiliza Mysql como base de datos que se encarga de guardar los usuarios registrados, y a través de una consulta select, se busca al momento
del login.

Las sesiones en PHP permiten persistir o que es lo mismo almacenar información temporalmente entre peticiones 
(a lo largo de varias páginas) a través de un ID único, para esto se utiliza la variable global $_SESSION,
 esta variable funciona como array, que permite ya sea obtener o asignar una variable de sesión.
