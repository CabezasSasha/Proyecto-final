# Sistema de Inventario - Proyecto Final Sasha Cabezas

Este proyecto es un sistema de inventario básico desarrollado en Python, utilizando SQLite como base de datos (`inventario.db`). Permite realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) sobre productos.

---

## **Estructura del Proyecto**

- **main.py**: Archivo principal donde se ejecuta el sistema.
- **inventario.db**: Base de datos SQLite que almacena la información de los productos.
- **ProyectoFinalSashaCabezas**: Carpeta que contiene este proyecto.

---

## Requisitos previos
- Python 3.12.8 instalado en tu sistema.
- Biblioteca `sqlite3` (incluida en Python por defecto).

---

## Instalación y ejecución
1. **Clona o descarga este repositorio** en tu máquina local.
   ```bash
   git clone <https://github.com/CabezasSasha/Proyecto-final.git>
   ```
2. **Navega al directorio del proyecto**.
   ```bash
   cd ProyectoFinalSashaCabezas
   ```
3. **Ejecuta el script principal**.
   ```bash
   python main.py
   ```

---

## Funcionalidades principales

### 1. Registrar un producto
- Selecciona la opción `1` en el menú principal.
- Ingresa el nombre, descripción, categoría, precio y stock del producto.
- El producto será guardado en la base de datos.

### 2. Buscar un producto
- Selecciona la opción `2` en el menú principal.
- Puedes buscar un producto por **ID**, **nombre** o **categoría**.
- Los detalles del producto se mostrarán en pantalla.

### 3. Mostrar inventario
- Selecciona la opción `3` en el menú principal.
- Se listarán todos los productos registrados, con su ID, nombre, descripción, categoría, precio y stock.

### 4. Actualizar un producto
- Selecciona la opción `4` en el menú principal.
- Ingresa el ID del producto que deseas actualizar.
- Modifica cualquiera de los datos del producto (o déjalos en blanco para no cambiarlos).

### 5. Eliminar un producto
- Selecciona la opción `5` en el menú principal.
- Ingresa el ID del producto que deseas eliminar.
- El producto será eliminado de la base de datos.

### 6. Generar reporte de bajo stock
- Selecciona la opción `6` en el menú principal.
- Ingresa el límite de stock para generar el reporte.
- Se mostrarán los productos cuyo stock sea igual o inferior al límite.

### 7. Gestionar categorías
- Selecciona la opción `7` en el menú principal.
- **Opciones disponibles:**
  - Agregar una nueva categoría.
  - Editar el nombre de una categoría existente.
  - Eliminar una categoría (solo si no está asociada a ningún producto).

### 8. Salir
- Selecciona la opción `8` para salir del programa.

---

## Estructura del proyecto
- **Base de datos SQLite:**
  - Tabla `productos`: Guarda los detalles de los productos.
  - Tabla `categorias`: Guarda las categorías disponibles.
- **Script principal:** Contiene todas las funciones necesarias para gestionar el inventario y un menú interactivo.

---

## Notas adicionales
- El sistema crea automáticamente la base de datos SQLite (`inventario.db`) si no existe al ejecutar el programa por primera vez.
- Asegúrate de no cerrar el programa inesperadamente para evitar la pérdida de datos no guardados.

---

## Futuras mejoras
- Implementar una interfaz gráfica.
- Añadir soporte para exportar el inventario en formatos como CSV o Excel.
- Integrar un sistema de autenticación de usuarios.

---

## Autor
Este proyecto fue desarrollado por [Sasha Aylén Cabezas Palmeyro]. Si tienes alguna pregunta o sugerencia, no dudes en ponerte en contacto.