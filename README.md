# shopping-cart

API para la gestión de Carrito de Compras.

> <p>#jpa #java #spring-boot </p>

---

## Tabla de Contenido

- [Descripción](#descripción)
- [Construido con](#construido-con)
- [Desarrollo](#desarrollo)
- [Endpoints](#endpoints)
- [Autor y contacto](#autor-y-contacto)

---

## Descripción

API's que permiten la gestión de un carrito de compras.

---

## Construido con

El código se encuentra implementado con Java y Gradle usando las siguientes librerías:

- Lombok - Para simplificar la creación de los medios de acceso a datos de un objeto
- Spring Data JPA - Gestion de los datos en la Base de Datos PostgreSQL
- Log4j - Para escribir mensajes de registro

---

## Desarrollo
1. Abrir el documento: [Instrucciones_Instalacion_Ejecucion_ShoppingCart_Indra.pdf](https://github.com/JonEchev/shopping-cart/blob/main/deliverables/Instrucciones_Instalacion_Ejecucion_ShoppingCart_Indra.pdf)
2. Instale Java 17 y un IDE de desarrollo como IntelliJ.
3. Clone este repositorio desde GitHub: https://github.com/JonEchev/shopping-cart.
4. Valide los datos de configuración de la BD en PostgreSQL mediante el archivo: application.yaml
5. Permita la construcción del proyecto con gradle.
6. Inicialice el proyecto, ejecutando la clase: CarApplication.java

Para ejecutar las pruebas unitarias:
1. Ejecute el proyecto desde test en gradle.

## Endpoints

- **LOCAL**
    - API (POST): http://localhost:80/shopping/api/cart/crear
    - API (POST): http://localhost:80/shopping/api/cart/agregar/:cartId
    - API (GET): http://localhost:80/shopping/api/cart/:cartId
    - API (DELETE): http://localhost:80/shopping/api/cart/eliminar/:cartId/:productId
    - API (PUT): http://localhost:80/shopping/api/cart/actualizar/:cartId
    - API (POST): http://localhost:80/shopping/api/cart/aplicar-cupon/:cartId?codeCoupon=DESC15

## Autor y contacto

- **Nombre**: Jonatan Echeverry
- **Correo electrónico**: jonechev1@gmail.com
- **GitHub**: [@JonEchev](https://github.com/JonEchev)
- **LinkedIn**: [jonatan-echeverry](https://www.linkedin.com/in/jonatan-echeverry-7130251a0/)