
Proyecto: apiRESTCheckUsuarioTADS

Materia: Taller Avanzado de Desarrollo de software

Estudiante: Christopher Alejandro Perfecto Diaz

Endpoints Disponibles

1. Insertar Usuario

Ruta: POST /tads/usuario/spinsusuario

Descripción: Permite el registro e inserción de nuevos usuarios en el sistema.

2. Validar Acceso

Ruta: POST /tads/usuario/spvalidaracceso

Descripción: Valida las credenciales de un usuario para permitir su ingreso.

3. Reporte de Usuarios

Ruta: GET /tads/usuario/vwrptusuario

Filtros opcionales (Query Params):

nombre

apPaterno

apMaterno

usuario

Descripción: Retorna la lista de usuarios. Permite aplicar búsquedas con filtros en los parámetros indicados.

4. Consultar Tipos de Usuario

Ruta: GET /tads/usuario/vwtipousuario

Descripción: Muestra los tipos de usuario registrados en la base de datos.

Pruebas

Las pruebas de la API fueron ejecutadas en POSTMAN. El archivo de exportación JSON comprimido .zip/.rar se adjunta en la entrega correspondiente.