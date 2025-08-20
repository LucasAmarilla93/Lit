# Proyecto de Gestion de Libros y Autores
La aplicación organiza libros y autores en una base de datos local y también permite buscar información de libros específicos consultando una API externa.

---

## Funcionalidades Principales

### 1. **Gestíon de Autores**
- **Crear Autores**: Permite agregar autores a la base de datos con atributos como nombre, fecha de nacimiento y fecha de fallecimiento.
- **Listar Autores por Año**: Busca y muestra los autores que estaban vivos en un año específico.
- **Mostrar Todos los Autores**: Lista todos los autores disponibles en la base de datos.

### 2. **Gestíon de Libros**
- **Buscar Libros por Título**: Consulta una API externa para encontrar libros y autores según el título.
- **Guardar Libro en la Base de Datos**: Al encontrar un libro a través de la API, se puede guardar junto con su autor en la base de datos.
- **Mostrar Todos los Libros**: Lista todos los libros registrados en la base de datos.

### 3. **Interacción con una API Externa**
- La aplicación se conecta a una API externa para buscar información de libros usando el título como criterio de búsqueda.
- Los datos obtenidos se serializan utilizando **records** en Java.

---

## Tecnologías Utilizadas

- **Java 22**
- **Spring Boot**: Framework para simplificar el desarrollo de aplicaciones Java.
- **Spring Data JPA**: Simplifica el acceso y gestión de la base de datos.
- **H2 Database**: Base de datos en memoria para desarrollo y pruebas.
- **Gson**: Para parsear datos JSON obtenidos desde la API externa.
- **API Externa**: Se conecta a una API de libros para realizar búsquedas de información.

---

## Requisitos Previos

- **Java 22**
- **Spring Boot**
- IDE como IntelliJ IDEA, Eclipse o NetBeans.
- Conexión a Internet para consumir la API externa.

## Ejecución del Proyecto

1. Clona el repositorio:
   ```bash
   git clone <URL-del-repositorio>
   ```
2. Abre el proyecto en tu IDE.
3. Ejecuta la clase principal `DemoApplication.java`.
4. Interactúa con la aplicación desde la consola:
   - Selecciona las opciones del menú para buscar, listar o guardar autores/libros.
