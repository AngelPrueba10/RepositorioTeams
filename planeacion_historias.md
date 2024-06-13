¡# Planeación del Proyecto

## Objetivo

Desarrollar una tienda virtual que permita a la empresa de artículos para mascotas distribuir sus productos a una mayor escala, proporcionando una plataforma fácil de usar para la gestión de productos y la realización de compras por parte de los clientes.

## Requerimientos Generales

1. **Interfaz de Usuario Intuitiva**
   - Diseñar una interfaz que sea fácil de navegar para los usuarios.
   - Incluir menús claros y categorización de productos.

2. **Gestión de Productos**
   - Permitir la adición, actualización, eliminación y búsqueda de productos.
   - Soportar la asignación de categorías a los productos.

3. **Carrito de Compras**
   - Facilitar la adición de productos al carrito.
   - Permitir la modificación de cantidades y eliminación de productos del carrito.

4. **Proceso de Pago**
   - Implementar un proceso de pago seguro y eficiente.
   - Soportar múltiples métodos de pago.

5. **Gestión de Usuarios**
   - Permitir a los usuarios registrarse e iniciar sesión.
   - Implementar un sistema de control de acceso y gestión de sesiones.

6. **Base de Datos**
   - Diseñar una base de datos que almacene la información de los productos, usuarios y transacciones.

7. **Seguridad**
   - Implementar medidas de seguridad para proteger la información del usuario y las transacciones.

## Historias de Usuario

### Historia de Usuario 1: Administrador de BD

- **Nombre historia:** Configuración de Base de Datos para Almacenar Datos
- **Prioridad en negocio:** Alta
- **Riesgo en desarrollo:** Baja
- **Puntos estimados:** 20
- **Iteración asignada:** 1
- **Programador responsable:** Equipo
- **Descripción:**
  - **Subtareas:**
    1. Diseñar la Estructura de la Base de Datos
    2. Crear las Tablas Necesarias
    3. Definir los Tipos de Datos y Restricciones
    4. Implementar Restricciones de Clave Primaria y Secundaria
    5. Configurar Reglas de Validación de Datos
    6. Programar Rutinas de Respaldo de la Base de Datos
    7. Establecer Procedimientos de Mantenimiento y Monitoreo
    8. Documentar la Estructura y Funcionamiento de la Base de Datos

### Historia de Usuario 2: Administradores y vendedores

- **Nombre historia:** Identificación y Control de Inicio de Sesión
- **Prioridad en negocio:** Alta
- **Riesgo en desarrollo:** Medio
- **Puntos estimados:** 27
- **Iteración asignada:** 1
- **Programador responsable:** Equipo
- **Descripción:**
  - **Subtareas:**
    1. Diseñar la Interfaz de Inicio de Sesión
    2. Implementar la Funcionalidad de Verificación de Credenciales en la Base de Datos
    3. Desarrollar la Lógica de Control de Acceso para Determinar los Permisos del Usuario
    4. Configurar la Encriptación de Contraseñas para Garantizar la Seguridad de las Credenciales
    5. Establecer Políticas de Bloqueo de Cuenta y Gestión de Sesiones para Proteger contra Intentos de Acceso No Autorizados
    6. Diseñar la Estructura de Datos para Almacenar Información sobre las Sesiones de Usuario
    7. Implementar Mecanismos para Registrar el Inicio y Cierre de Sesión de los Usuarios
    8. Desarrollar la Funcionalidad para Verificar la Validez de las Sesiones Activas
    9. Configurar Políticas de Expiración de Sesiones para Cerrar Automáticamente las Sesiones Inactivas
    10. Establecer Procedimientos de Auditoría para Registrar Actividades y Detectar Posibles Infracciones de Seguridad

### Historia de Usuario 3: Administradores y vendedores

- **Nombre historia:** Gestión de Productos en el Sistema
- **Prioridad en negocio:** Alta
- **Riesgo en desarrollo:** Baja
- **Puntos estimados:** 55
- **Iteración asignada:** 1
- **Programador responsable:** Equipo
- **Descripción:**
  - **Subtareas:**
    1. Implementar la Funcionalidad para Agregar un Nuevo Producto al Inventario
    2. Desarrollar la Opción de Actualizar la Información de un Producto Existente
    3. Configurar la Funcionalidad para Eliminar un Producto del Catálogo
    4. Implementar la Opción de Limpiar los Campos de Entrada para Agregar un Nuevo Producto
    5. Desarrollar la Funcionalidad para Asignar Categorías a los Productos
    6. Configurar la Opción de Búsqueda de Productos
    7. Implementar la Funcionalidad de Filtrado por Categoría
    8. Desarrollar la Opción de Exportar e Importar Datos de Productos
    9. Configurar la Generación de Informes y Estadísticas sobre el Inventario de Productos
