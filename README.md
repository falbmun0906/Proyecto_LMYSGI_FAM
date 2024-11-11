# Proyecto_LMYSGI_FAM

# Análisis de Requisitos y Objetivos del Proyecto

## 1. Objetivos de la Aplicación Web

### 1.1. Objetivo General

El objetivo principal es desarrollar una tienda en línea de instrumentos musicales que permita a los usuarios navegar entre categorías de productos, ver detalles de cada uno y agregar artículos a su carrito de compras. Esta tienda debe ser completamente funcional desde el punto de vista visual y estructural, utilizando solo HTML para la organización del contenido y CSS para el diseño y maquetación de la tienda.

### 1.2. Objetivos Específicos

- **Navegación clara entre categorías y productos**: Crear una estructura de navegación sencilla que permita a los usuarios explorar diferentes tipos de instrumentos musicales (guitarras, teclados, baterías, etc.) y acceder a sus subcategorías.

- **Diseño atractivo y funcional**: Utilizar CSS para crear un diseño visualmente atractivo, que incluya un layout limpio y moderno, con un enfoque en la accesibilidad y la buena presentación de productos.

- **Optimización para diferentes dispositivos**: Implementar un diseño responsivo que permita a los usuarios disfrutar de una experiencia de compra adecuada tanto en computadoras de escritorio como en dispositivos móviles o tabletas.

- **Interactividad básica con el uso de formularios**: Crear formularios de registro, inicio de sesión, y un formulario de contacto sencillo utilizando solo HTML y CSS, sin necesidad de backend ni JavaScript.

## 2. Requisitos del Proyecto

### 2.1. Requisitos Funcionales

#### 2.1.1 Estructura de Páginas

- **Página de Inicio (Home)**: Presentar las categorías de productos (guitarras, teclados, percusión, etc.) de manera destacada, de modo que los usuarios puedan hacer clic en ellas para acceder a las subcategorías o productos específicos. También se incluirán elementos como imágenes destacadas y descripciones breves.

- **Página de Categoría de Instrumentos**: Dentro de cada categoría (por ejemplo, "Guitarras y Bajos"), mostrar productos organizados de manera estructurada. Cada producto tendrá su imagen, nombre y un enlace al detalle del producto.

- **Página de Subcategoría (por ejemplo, "Guitarras Eléctricas")**: Mostrar productos dentro de una subcategoría específica (como guitarras eléctricas), con imágenes de productos y una breve descripción.

- **Página de Producto**: Mostrar información detallada de cada producto, incluyendo imágenes, precio, descripción y especificaciones. El diseño debe ser atractivo y permitir a los usuarios ver detalles completos de cada artículo.

- **Carrito de Compras**: Visualizar los productos que un usuario ha añadido al carrito. Los usuarios deben poder ver una lista de productos, cantidades y un resumen de precios. Aunque no se implementará la funcionalidad dinámica, el diseño del carrito debe ser claro y estructurado.

- **Página de Perfil de Usuario**: Permitir a los usuarios registrados ver y actualizar su perfil (aunque la actualización no se implementará en esta fase). Debería mostrar detalles como el nombre, dirección y historial de compras.

- **Inicio de Sesión y Registro**: Crear formularios para que los usuarios puedan registrarse o iniciar sesión. Aunque no habrá funcionalidad de backend, se puede crear la estructura de los formularios utilizando HTML.

### 2.2. Requisitos No Funcionales

- **Usabilidad**

  - **Interfaz intuitiva**: Se utilizarán principios de diseño sencillo y limpio, con una estructura clara y fácil de navegar. Los usuarios deben ser capaces de encontrar rápidamente lo que buscan, ya sea una categoría de producto o el proceso de registro.

  - **Estilos de texto claros**: La tipografía debe ser legible y adecuada para una tienda en línea (por ejemplo, con títulos destacados y descripciones legibles).

- **Rendimiento**

  - **Optimización del diseño**: Aunque no se implementará JavaScript para interacciones, se asegurará que las páginas se carguen rápidamente, utilizando imágenes optimizadas y un diseño sencillo que permita una carga ágil.

- **Responsividad y compatibilidad**

  - **Diseño responsivo**: Usando CSS Media Queries, se garantizará que la tienda sea accesible y funcional en diferentes tamaños de pantalla, desde computadoras de escritorio hasta dispositivos móviles.

  - **Compatibilidad de navegadores**: El sitio se probará en los principales navegadores (Chrome, Firefox, Safari, Edge) para asegurar que el diseño sea consistente y funcione correctamente.

## 3. Tecnologías Utilizadas

### 3.1. Frontend

- **HTML5**: Se utilizará HTML5 para estructurar el contenido de la tienda en línea, aplicando etiquetas semánticas que faciliten la organización de las categorías, productos, formularios de inicio de sesión y registros, y demás secciones. Utilizaremos listas, enlaces, tablas (para el carrito de compras), y formularios (para inicio de sesión y registro).

- **CSS3**: CSS3 se utilizará para dar estilo a las páginas. Esto incluirá:

  - **Layout y disposición**: Usando propiedades como flexbox o grid para organizar productos en categorías y subcategorías.
  
  - **Estilos visuales**: Se aplicarán estilos a los productos, botones, formularios y enlaces para hacer que la tienda sea visualmente atractiva.
  
  - **Diseño responsivo**: A través de media queries, se adaptará el diseño para que funcione en dispositivos de escritorio, tabletas y móviles.

## 4. Estructura de Páginas

### 4.1. Páginas y Estructura HTML

- **Página de Inicio (Home) - `index.html`**

  - Listado de categorías de productos (Guitarras, Percusión, Teclados, etc.).
  - Diseño limpio con imágenes grandes representativas de cada categoría.
  - Enlaces a cada categoría para su visualización detallada.

- **Página de Categoría de Instrumentos - `categoria_guitarras_bajos.html`**

  - Muestra productos dentro de la categoría de guitarras y bajos.
  - Imágenes de los productos, nombre, descripción breve, enlace al detalle del producto.

- **Página de Subcategoría - `categoria_guitarras_electricas.html`**: Muestra solo productos de guitarras eléctricas.

- **Página de Producto - `producto.html`**: Detalles completos del producto seleccionado (imagen, precio, descripción, características).

- **Carrito de Compras - `carrito.html`**: Listado de productos añadidos al carrito con resumen de precios.

- **Página de Perfil de Usuario - `perfil.html`**: Muestra datos del usuario.

- **Páginas de Inicio de Sesión y Registro - `login.html`, `registro.html`**: Formularios con campos para ingresar datos de usuario (sin backend, solo el diseño).

## 5. Conclusión

Este proyecto de tienda en línea se centrará en la creación de una estructura visualmente atractiva y funcional mediante HTML y CSS. Aunque no se implementarán interacciones dinámicas ni backend, se crearán páginas y formularios con una disposición intuitiva y fácil de usar. El diseño será responsivo, adaptándose a diversos dispositivos, y se seguirá un esquema de maquetación basado en principios de accesibilidad y usabilidad.
