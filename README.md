# Monroe - Sistema de Ventas de Productos
Monroe es un sistema web diseñado para gestionar de manera eficiente la venta de productos, desde el registro de ventas hasta el control de inventarios. Su objetivo es automatizar el proceso de ventas, mejorar el control de stock y facilitar la administración de productos en tiempo real.
## Enlaces
-   **Deploy** https://niclovich.github.io/Monroe/
-  **Deploy en Servidor** https://monroe-hazel.vercel.app/
-   **Repositorio** https://github.com/niclovich/monroe.git

  
## Objetivos
El sistema Monroe tiene como objetivo:
- **Gestión de ventas**: Facilitar la realización de ventas de productos a través de una interfaz sencilla y eficiente.
- **Control de inventario**: Mantener un registro actualizado de los productos disponibles, gestionando las entradas y salidas del inventario de manera automática.
- **Generación de reportes**: Ofrecer reportes detallados sobre ventas, productos más vendidos, ingresos, entre otros.
- **Integración de pagos**: Facilitar la integración con pasarelas de pago para gestionar transacciones online.
- **Accesibilidad remota**: Permitir a los administradores y vendedores acceder al sistema desde cualquier dispositivo con conexión a Internet.
## Componentes del Sistema
El sistema Monroe está compuesto por los siguientes módulos:
- **Gestión de Productos**: Permite registrar, actualizar y eliminar productos. Además, gestiona la información detallada de cada producto (nombre, descripción, precio, stock, etc.).
- **Gestión de Ventas**: Facilita la realización de ventas a través de una interfaz intuitiva, con opciones de pago y generación de facturas.
- **Inventario**: Realiza un seguimiento del stock de productos, gestionando las entradas y salidas automáticamente al realizar ventas o recibir nuevos productos.
- **Reportes**: Genera reportes de ventas, productos más vendidos, ingresos por día, semana o mes, y otros aspectos clave de las operaciones comerciales.
- **Usuarios y Roles**: Administra diferentes roles dentro del sistema, como administradores, vendedores y gerentes, asignando permisos según el perfil de cada uno.
## Tecnologías Utilizadas (A Futuro)
El sistema Monroe está desarrollado utilizando las siguientes tecnologías:
- **Backend**:
  - **Node.js**: Entorno de ejecución para JavaScript que permite construir aplicaciones backend rápidas y escalables.
  - **JWT (JSON Web Tokens)**: Para autenticación y autorización de usuarios de forma segura.
- **Frontend**:
  - **React**: Biblioteca JavaScript para construir interfaces de usuario dinámicas y reactivas.
  - **Redux**: Para gestionar el estado global de la aplicación de manera predecible.
  - **CSS/SCSS**: Para la estilización de la interfaz de usuario.
  - **Bootstrap**: Framework CSS para el diseño de una interfaz moderna y responsiva.
## Descripción de las Páginas HTML
1. **index.html**:
   - Esta es la página principal del sistema y actúa como punto de entrada para los usuarios. En ella se presentan productos destacados, promociones, ofertas y accesos rápidos a otras secciones del sitio.
   - Utiliza **CSS puro**, **Flexbox**, **CSS Grid** y **Media query** para organizar los productos y otros elementos de manera responsiva. Los usuarios pueden ver las promociones y categorías principales de productos, y la disposición se adapta a diferentes tamaños de pantalla, asegurando una experiencia de navegación fluida tanto en dispositivos móviles como de escritorio.
2. **acerca-de.html**:
   - Esta página proporciona información sobre  Monroe, su misión, visión. También incluye preguntas frecuentes para resolver dudas comunes de los usuarios.
   - Se utiliza **Bootstrap** para organizar el contenido de forma clara y estructurada, aprovechando las clases de **row** y **column** para distribuir la información de manera eficiente en pantallas de cualquier tamaño.
3. **productos.html**:
   - Esta página muestra un catálogo completo de productos disponibles, donde los usuarios pueden ver opciones, agregar productos al carrito y explorar diferentes categorías.
   - Utiliza **CSS puro**, **Flexbox**, **CSS Grid** y **Media querys** para una presentación atractiva y adaptada a diferentes dispositivos. Los productos se muestran de forma organizada y fluida, con un diseño que se ajusta a pantallas de diferentes tamaños, garantizando una navegación óptima tanto en dispositivos móviles como en escritorios.
4. **carrito.html**:
   - En esta página se gestiona el proceso de compra, donde los usuarios pueden ver los productos añadidos al carrito, modificar cantidades, eliminar productos y proceder con el pago.
   - Se emplean **CSS puro**, **Flexbox**, **CSS Grid** y **Media query** para organizar los elementos de manera clara y accesible, brindando una experiencia de compra fluida y responsiva. La disposición se adapta tanto a pantallas grandes como pequeñas, asegurando una interfaz fácil de usar en cualquier dispositivo.
5. **contacto.html**:
   - En esta página los usuarios pueden ponerse en contacto con el equipo de Monroe. Se incluye un formulario de contacto donde los usuarios pueden enviar consultas, además de información de contacto como teléfono y correo electrónico.
   - Utiliza **Bootstrap** con **row** y **column** para organizar el formulario de contacto y los campos de entrada de forma eficiente, garantizando que los usuarios puedan interactuar fácilmente y enviar sus consultas. La interfaz es completamente responsiva, adaptándose sin problemas a diferentes dispositivos.
## Instalación
Para instalar y ejecutar el sistema Monroe localmente, sigue estos pasos:
  git clone https://github.com/niclovich/monroe.git
