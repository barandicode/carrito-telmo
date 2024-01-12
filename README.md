Carrito de Compras - Vue.js
===========================

Características
---------------

-   Vue.js: La aplicación utiliza Vue.js, un marco de JavaScript progresivo para construir interfaces de usuario interactivas.


-   Carrito Sidebar: Un sidebar fijo en el lado derecho muestra los productos agregados al carrito, con la opción de realizar la compra.

Instrucciones de Uso
--------------------

1.  Explorar Productos:

    -   Los productos se muestran en la sección principal de la página.
    -   Cada producto incluye nombre, imagen, precio y una entrada para seleccionar la cantidad.
    -   Puedes añadir productos al carrito haciendo clic en el botón "Añadir al carrito".
2.  Carrito de Compras:

    -   El carrito de compras se encuentra en un sidebar fijo en el lado derecho.
    -   Muestra la imagen, nombre, precio y cantidad de los productos agregados al carrito.
3.  Realizar Compra:

    -   Una vez que hayas agregado productos al carrito, puedes hacer clic en el botón "Comprar" en el sidebar.
    -   Se mostrará una alerta indicando que la compra ha sido realizada con éxito.

Estructura del Código
---------------------

-   HTML: La estructura básica del documento HTML con enlaces a Vue.js y estilos.

-   CSS: Estilos que definen la apariencia de la página, incluyendo el diseño responsivo y estilos del carrito.

-   Vue.js: Configuración de Vue.js con la instancia principal que gestiona el estado (`data`) y los métodos para agregar productos al carrito y realizar compras.

Datos de Ejemplo
----------------

-   La aplicación incluye datos de ejemplo en la sección `productos` con nombre, imagen (ruta relativa), precio y cantidad.

-   Se utiliza un objeto `carrito` para almacenar los productos seleccionados por el usuario.
