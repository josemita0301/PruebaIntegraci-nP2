# Guía de Ejecución de los Proyectos

## Requisitos Previos
1. **Base de Datos**: Asegúrese de tener un servidor de base de datos SQL configurado.
2. **Scripts SQL**: Ejecute los scripts proporcionados para crear las tablas y datos iniciales.
3. **Configuración de Conexión**: Modifique el archivo `appsettings.json` en cada proyecto para apuntar a su servidor de base de datos.

---

## Proyecto 1: HotelSOAP
### Descripción
Este proyecto maneja las **consultas de disponibilidad de habitaciones** a través de un **Servicio Web SOAP**.

### Pasos para Ejecutar
1. Modifique el archivo `appsettings.json` y configure el string de conexión.
2. Asegúrese de haber ejecutado el script de base de datos correspondiente.
3. Compile y ejecute el proyecto desde su entorno de desarrollo (Visual Studio, Rider, etc.).

---

## Proyecto 2: HotelApiRest
### Descripción
Este proyecto gestiona las **reservas** mediante una **API REST**.

### Pasos para Ejecutar
1. Modifique el archivo `appsettings.json` y configure el string de conexión.
2. Asegúrese de haber ejecutado el script de base de datos correspondiente.
3. Compile y ejecute el proyecto desde su entorno de desarrollo.

---

## Proyecto 3: HotelMicroservicio
### Descripción
Este proyecto maneja la **gestión del inventario de habitaciones**.

### Pasos para Ejecutar
1. Modifique el archivo `appsettings.json` y configure el string de conexión.
2. Asegúrese de haber ejecutado el script de base de datos correspondiente.
3. Compile y ejecute el proyecto desde su entorno de desarrollo.

---

## Notas Finales
- Verifique que los tres proyectos se ejecuten sin conflictos.
- Cada proyecto utiliza su propia base de datos o esquema independiente.
- Si tiene problemas de conexión, revise los permisos y configuraciones de su servidor de base de datos.

---

¡Listo! Ahora puede probar cada uno de los servicios individualmente.
