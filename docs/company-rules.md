
# Gestión de empresas y flotas — RutaSegura

## Modalidades de usuario

- Usuario independiente.
- Usuario perteneciente a una o varias empresas.

## Roles empresariales

- OWNER: propietario y administrador principal.
- ADMIN: administra miembros y vehículos.
- OPERATOR: consulta vehículos asignados y planifica rutas.

## Gestión de vehículos

- Un vehículo pertenece a un usuario independiente o a una empresa.
- Un vehículo empresarial puede asignarse a operadores.
- Las asignaciones conservan su historial.
- Solo los usuarios autorizados pueden administrar vehículos.

## Historial de rutas

- Cada ruta registra al usuario que la creó.
- Cada ruta registra el vehículo utilizado.
- Los usuarios consultan su propio historial.
- Las rutas no se publican automáticamente.

## Seguridad

- La pertenencia a una empresa se valida en backend.
- Los operadores solo utilizan vehículos asignados.
- Los usuarios no pueden consultar rutas privadas de otros usuarios.
- Las asignaciones finalizadas no se eliminan.
