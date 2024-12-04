# **Índice**

1. [Análisis de Requisitos y Objetivos del Proyecto](#análisis-de-requisitos-y-objetivos-del-proyecto)  
2. [Planificación del Proyecto (Wireframe y Estructura HTML)](#planificación-del-proyecto-wireframe-y-estructura-html)  
3. [Diseño y Desarrollo del Frontend (HTML y CSS)](#diseño-y-desarrollo-del-frontend-html-y-css)  
4. [Implementación y Validación del Código](#implementación-y-validación-del-código)  
5. [Presentación del Proyecto (Videotutorial)](#presentación-del-proyecto-videotutorial)  

---

## **Planificación del Proyecto (Wireframe y Estructura HTML)**  

### **1. Objetivos de la Aplicación Web**

#### **1.1. Objetivo General**  
El objetivo principal del proyecto es desarrollar una tienda en línea de instrumentos musicales que permita a los usuarios explorar categorías de productos, visualizar detalles específicos y añadir artículos a un carrito de compras. La aplicación estará construida utilizando HTML y CSS para garantizar una organización clara del contenido y un diseño atractivo. Además, se han empleado herramientas como Git, GitHub y Balsamiq para facilitar el desarrollo colaborativo y la planificación visual del proyecto.  

#### **1.2. Objetivos Específicos**  
- **Navegación clara y accesible:** Crear una estructura de navegación intuitiva que permita a los usuarios explorar categorías, subcategorías y detalles de productos sin complicaciones.  
- **Diseño visual atractivo y funcional:** Utilizar CSS para diseñar un sitio web moderno, limpio y visualmente atractivo, que cumpla con los principios de accesibilidad.  
- **Optimización para dispositivos móviles:** Implementar diseño responsivo para ofrecer una experiencia de usuario fluida y consistente en computadoras de escritorio, tabletas y móviles.  
- **Gestión eficiente del proyecto:** Usar Git y GitHub para controlar versiones, trabajar en equipo y documentar el progreso del desarrollo.  
- **Planificación visual efectiva:** Emplear Balsamiq para prototipar wireframes y garantizar que la estructura y el diseño del sitio estén bien definidos antes de la implementación.  

---

### **2. Requisitos del Proyecto**

#### **2.1. Requisitos Funcionales**  
- Estructura clara de las páginas, incluyendo:  
  - Página de inicio que destaque las categorías principales.  
  - Páginas para categorías, subcategorías y productos individuales.  
  - Carrito de compras para visualizar los productos añadidos.  
  - Formularios para registro e inicio de sesión del usuario.  
- Información completa en la página de cada producto: imágenes, precio, descripción y características detalladas.  
- Navegación funcional entre categorías, subcategorías y productos relacionados.  

#### **2.2. Requisitos No Funcionales**  
- **Usabilidad:**  
  - Interfaz intuitiva y accesible, con diseño limpio y estructurado.  
  - Tipografía legible y adecuada para una tienda en línea.  
- **Rendimiento:**  
  - Optimización de diseño y carga rápida, utilizando imágenes comprimidas y código eficiente.  
- **Compatibilidad y Responsividad:**  
  - Diseño responsivo adaptado a diferentes tamaños de pantalla.  
  - Compatibilidad probada en navegadores principales (Chrome, Firefox, Safari, Edge).  

---

### **3. Tecnologías Utilizadas y Justificación**

#### **HTML5**  
La estructura del sitio web está construida completamente en HTML5 debido a su capacidad para organizar el contenido de manera semántica y accesible. Las etiquetas como `<header>`, `<nav>`, `<section>` y `<article>` permiten que el código sea fácil de leer y entender tanto para los desarrolladores como para los navegadores. Esta elección asegura un desarrollo estructurado, facilitando futuras ampliaciones o integraciones.  

#### **CSS3**  
Para el diseño visual y la maquetación, se ha utilizado CSS3, que ofrece herramientas avanzadas como flexbox y grid para organizar los elementos de manera eficiente. Estas propiedades permiten crear un diseño limpio, moderno y adaptado a diferentes dispositivos mediante Media Queries. Además, CSS garantiza un control detallado sobre la apariencia de las páginas, permitiendo personalizar tipografías, colores y estilos de manera precisa, lo cual es crucial para lograr un diseño atractivo y profesional.  

#### **Git y GitHub**  
El uso de Git y GitHub ha sido fundamental para gestionar el proyecto de manera eficiente. Git se ha utilizado como herramienta de control de versiones, permitiendo rastrear cambios en el código y revertir errores. GitHub ha servido como una plataforma para alojar el proyecto y documentar el progreso mediante commits. Estas tecnologías no solo mejoran la productividad, sino que aseguran la transparencia y el seguimiento continuo del desarrollo.  

#### **Balsamiq**  
Antes de iniciar la implementación, se diseñaron wireframes en Balsamiq para planificar visualmente la estructura y diseño del sitio. Esta herramienta permite prototipar interfaces de usuario de manera rápida, asegurando que todos los elementos esenciales sean considerados desde el inicio. Los wireframes proporcionaron una base sólida para el desarrollo y ayudaron a garantizar que el diseño cumpliera con las expectativas del usuario y los objetivos del proyecto.  

---

### **4. Desarrollo del Proyecto y Estructura de Páginas**

El sitio web se compone de las siguientes páginas clave:  

- **Página de Inicio:** Ofrece una vista general de las categorías de productos con imágenes representativas. Cada categoría tiene un enlace a sus respectivas subcategorías.  
- **Páginas de Categorías y Subcategorías:** Organizan los productos de forma jerárquica, mostrando imágenes, descripciones breves y enlaces para acceder a los detalles.  
- **Página de Producto:** Presenta información detallada, como imágenes, precio, descripción y características.  
- **Carrito de Compras:** Muestra los artículos añadidos con un resumen de precios y cantidades.  
- **Página de Perfil de Usuario:** Visualiza los datos del usuario registrado.  
- **Páginas de Registro e Inicio de Sesión:** Incluyen formularios HTML diseñados para capturar información del usuario.  

---

### **5. Conclusión**

El desarrollo de este proyecto de tienda en línea ha priorizado el uso de tecnologías sólidas y bien establecidas, como HTML5 y CSS3, para garantizar una experiencia de usuario fluida y una estructura funcional. La incorporación de herramientas como Git, GitHub y Balsamiq permitió planificar y gestionar el proyecto de manera eficiente.  

La implementación de un diseño responsivo asegura que el sitio sea accesible en una amplia variedad de dispositivos, mientras que el enfoque en la validación y optimización del código asegura que el proyecto cumpla con los estándares modernos de desarrollo web. Este proyecto no solo cumple con los requisitos funcionales y no funcionales establecidos, sino que también sienta una base sólida para futuras mejoras, como la integración de backend o funcionalidades dinámicas.    

## **Diseño y Desarrollo del Frontend (HTML y CSS)**  

## 1. Configuración del Entorno de Desarrollo

### 1.1. Estructuración del Proyecto
El proyecto ha sido estructurado de forma lógica y eficiente, lo cual facilita tanto el desarrollo como el mantenimiento a largo plazo. La raíz del proyecto contiene las carpetas necesarias para una correcta distribución de los recursos y archivos:

- **assets**: Carpeta principal para todos los recursos multimedia y archivos relacionados con la interfaz visual del sitio.
  - **css**: Contiene los archivos CSS organizados en subcarpetas, como **components** para los estilos reutilizables de elementos, y el archivo principal **styles.css** que agrupa las reglas generales de la aplicación.
  - **icons**: Almacena los íconos utilizados en diversas secciones del sitio.
  - **images**: Contiene las imágenes de la web, que se encuentran optimizadas para asegurar una carga rápida.
  - **js**: Guarda los archivos JavaScript, que pueden ser utilizados para funcionalidades dinámicas o interactivas (aunque no se han implementado funciones JavaScript en este proyecto).
  - **docs**: Carpeta para la documentación del proyecto, que incluye detalles técnicos, planificación y otros informes relevantes.

### 1.2. Configuración del Editor de Código
Se ha utilizado **VSCode** como editor de código, con **Live Server** activado para permitir la previsualización en tiempo real de los cambios realizados en el código. Esta configuración facilita el flujo de trabajo, eliminando la necesidad de recargar manualmente la página para ver los resultados de las modificaciones. Además, se ha configurado con extensiones útiles como **Emmet** para autocompletado de código HTML y **Prettier** para formateo automático del código, lo que garantiza un código limpio y bien estructurado.

---

## 2. Desarrollo de la Estructura HTML (al menos 7 páginas HTML)

### 2.1. Estructuración del HTML
A lo largo de todo el proyecto, se ha mantenido una estructura HTML semántica y adecuada, que favorece tanto la accesibilidad como la optimización del código. Se han utilizado etiquetas semánticas como `<header>`, `<nav>`, `<section>`, `<article>`, y `<footer>`, lo que organiza claramente los contenidos y mejora la comprensión tanto para los desarrolladores como para los motores de búsqueda.

- Se ha diseñado y desarrollado una página de inicio que incluye el menú de navegación principal y enlaces a otras secciones clave del sitio.
- Además, se han creado páginas secundarias como una página de categorías, un perfil de usuario, una página de login, y otras secciones adicionales como la página de producto o carrito.
- La correcta interrelación entre las páginas se ha logrado mediante el uso de enlaces en el menú de navegación y enlaces contextuales dentro de los textos de las páginas.

### 2.2. Enlazado entre Páginas
Los enlaces dentro del código HTML han sido gestionados eficientemente, asegurando que los usuarios puedan navegar de manera intuitiva entre las diferentes secciones del sitio. Cada sección está conectada a través de enlaces organizados en el menú de navegación y otras áreas relevantes, como el pie de página.

---

## 3. Aplicación de Hojas de Estilo CSS

### 3.1. Organización de los Estilos
El archivo CSS se ha organizado de manera modular, separando los estilos generales de la aplicación en el archivo principal, mientras que los estilos específicos de componentes reutilizables se encuentran en subcarpetas dentro de la carpeta **components**. Esta estructura facilita el mantenimiento del código y permite la reutilización de componentes visuales en diversas partes del sitio.

### 3.2. Estilización
Se han definido estilos globales para garantizar la coherencia visual en todo el sitio. Los estilos incluyen la tipografía, los colores y los espaciados, lo que asegura una apariencia limpia y moderna en cada página del sitio. Las reglas de estilo se aplican en los elementos comunes a todas las páginas, como los menús de navegación, los botones, las tarjetas de contenido y los formularios.

- La tipografía y los colores (blancos, grises y negros) han sido cuidadosamente seleccionados para mantener una apariencia atractiva y profesional.
- Se han utilizado propiedades CSS como **gap**, **padding**, **font-size** y **color** para estructurar y diseñar los elementos de manera coherente.

### 3.3. Efectos y Transiciones en CSS
Para mejorar la experiencia del usuario, se han aplicado efectos de hover en los enlaces, botones y otros elementos interactivos. Las transiciones suaves se implementan mediante la propiedad **transition**, lo que permite que los elementos cambien de estado (por ejemplo, el color de fondo o del texto) de forma fluida y agradable para el usuario.

---

## 4. Aplicación de Diseño Responsive

### 4.1. Estructura Semántica y Adaptabilidad
El diseño ha sido desarrollado con un enfoque en la adaptabilidad, asegurando que el sitio se visualice correctamente en una amplia variedad de dispositivos, desde pantallas grandes de escritorio hasta dispositivos móviles. Se ha utilizado un diseño flexible con **Flexbox** y **CSS Grid**, tecnologías que permiten organizar los elementos de forma que se ajusten automáticamente al tamaño de la pantalla disponible.

- **Flexbox** y **CSS Grid** son fundamentales para permitir que los contenedores y sus elementos secundarios se adapten y se organicen según el tamaño de la pantalla. Por ejemplo, las secciones que están dispuestas en columnas en pantallas grandes pueden reorganizarse en una sola columna en pantallas más pequeñas.

### 4.2. Puntos de Ruptura (Media Queries)
El proyecto está completamente adaptado a diferentes tamaños de pantalla mediante el uso de **media queries**. Se han implementado diferentes puntos de ruptura dependiendo del contenido de las páginas, ajustando propiedades como el tamaño de fuente, los espaciados y la disposición de los elementos para garantizar que el diseño se mantenga funcional y atractivo en todas las resoluciones.

---

## 5. Diseño de Componentes Específicos

### 5.1. Estilización de Componentes Funcionales
Se han creado y estilizado componentes clave del sitio, como formularios, botones y menús desplegables, para garantizar una experiencia de usuario consistente y clara. Por ejemplo:

- Los formularios de contacto tienen un diseño limpio y claro, con campos de entrada bien definidos y márgenes adecuados para facilitar la interacción.
- Los botones tienen un diseño coherente con la paleta de colores general del sitio y se destacan para facilitar la interacción.
- Los menús de navegación son flexibles y pueden incluir submenús o elementos adicionales, adaptándose a diferentes tamaños de pantalla.

---

## 6. Inserción de Imágenes y Vídeos

### 6.1. Optimización de Contenidos Multimedia
Las imágenes se han optimizado para asegurar que se carguen rápidamente, mejorando el rendimiento del sitio. Se utilizan clases específicas, como **.order-top img** y **.opinion-image**, para garantizar que las imágenes se ajusten de forma dinámica y consistente dentro de sus contenedores, manteniendo una presentación visual coherente en todo el diseño.

Además, se ha seguido una estrategia de optimización de imágenes, utilizando formatos adecuados que aseguran una carga rápida sin comprometer la calidad visual. Todas las imágenes incluyen atributos **alt** para cumplir con las buenas prácticas de accesibilidad, lo que garantiza que el contenido sea accesible para usuarios con discapacidades visuales.

---

## Producto Final
El código desarrollado establece una estructura sólida para un sitio web completo, visualmente atractivo y funcional, que se adapta a diferentes dispositivos. La correcta organización de los recursos, el uso de tecnologías modernas de **CSS** y la implementación de un diseño **responsive** aseguran que el sitio sea fácil de mantener y escalar en el futuro. La experiencia de usuario se ve mejorada mediante la integración de transiciones suaves, interactividad en los enlaces y una disposición limpia y lógica de los elementos.

## **Implementación y Validación del Código**  

# Fase 3: Implementación y Validación del Código

## 1. Validación del Código HTML

1.1. Una vez completado el desarrollo de la estructura HTML, se procedió a la validación del código para asegurar que cumple con los estándares de calidad y las reglas sintácticas correctas. Para ello, se utilizó el **Validador HTML de W3C**, que permite detectar errores como etiquetas mal cerradas, atributos incorrectos o la falta de etiquetas obligatorias.

1.2. El código HTML fue validado utilizando la herramienta mencionada y se generó un informe con el estado del código. A partir de este informe, se realizaron las correcciones necesarias, como el cierre adecuado de algunas etiquetas y la inclusión de atributos faltantes.

### Producto:
- **Informe de validación de HTML**, que incluye los errores encontrados y las correcciones aplicadas.

## 2. Validación del Código CSS

2.1. Para asegurar que el código CSS esté optimizado y siga las mejores prácticas, se utilizó el **Validador CSS de W3C**. Esta herramienta analiza el archivo CSS, detectando errores como propiedades incorrectas, valores no válidos, o reglas redundantes que pueden afectar el rendimiento o la consistencia visual.

2.2. Después de ejecutar la validación, se generó un informe que mostraba los errores y advertencias. Se corrigieron aspectos como propiedades obsoletas y se aseguraron de que las reglas de estilo estuvieran aplicadas correctamente.

### Producto:
- **Informe de validación de CSS**, que documenta los problemas detectados y las correcciones realizadas.

## 3. Optimización y Comprobación de Accesibilidad y Usabilidad

# Fase 3: Implementación y Validación del Código

## 1. Validación del Código HTML

1.1. Una vez completado el desarrollo de la estructura HTML, se procedió a la validación del código para asegurar que cumple con los estándares de calidad y las reglas sintácticas correctas. Para ello, se utilizó el **Validador HTML de W3C**, que permite detectar errores como etiquetas mal cerradas, atributos incorrectos o la falta de etiquetas obligatorias.

1.2. El código HTML fue validado utilizando la herramienta mencionada y se generó un informe con el estado del código. A partir de este informe, se realizaron las correcciones necesarias, como el cierre adecuado de algunas etiquetas y la inclusión de atributos faltantes.

### Producto:
- **Informe de validación de HTML**, que incluye los errores encontrados y las correcciones aplicadas.

## 2. Validación del Código CSS

2.1. Para asegurar que el código CSS esté optimizado y siga las mejores prácticas, se utilizó el **Validador CSS de W3C**. Esta herramienta analiza el archivo CSS, detectando errores como propiedades incorrectas, valores no válidos, o reglas redundantes que pueden afectar el rendimiento o la consistencia visual.

2.2. Después de ejecutar la validación, se generó un informe que mostraba los errores y advertencias. Se corrigieron aspectos como propiedades obsoletas y se aseguraron de que las reglas de estilo estuvieran aplicadas correctamente.

### Producto:
- **Informe de validación de CSS**, que documenta los problemas detectados y las correcciones realizadas.

## 3. Optimización y Comprobación de Accesibilidad y Usabilidad

### 3.1. Optimización de Rendimiento

3.1.1. **Minimización del archivo CSS**: Se optimizó el archivo CSS para mejorar el rendimiento del sitio. Para ello, se eliminaron los espacios en blanco y los comentarios innecesarios, reduciendo el tamaño del archivo sin afectar su funcionalidad. Esta optimización ayuda a que la página se cargue más rápidamente.

3.1.2. **Compresión de imágenes sin pérdida de calidad**: Se procedió a la optimización de las imágenes, asegurándose de que se comprimieran sin perder calidad visual. Se utilizaron herramientas de compresión de imágenes, lo que reduce el tamaño de los archivos y mejora el tiempo de carga de la página.

### Producto:
- **Informe de optimización**, que incluye detalles sobre la minimización del CSS y la compresión de imágenes.

### 3.2. Pruebas de Usabilidad

3.2.1. Se realizaron pruebas de usabilidad en varios dispositivos y navegadores (Chrome, Firefox, Edge, dispositivos móviles) para asegurar que la página se visualiza correctamente y funciona de manera coherente en diferentes entornos.

3.2.2. Se utilizaron herramientas como **Lighthouse** y **Wave** para evaluar la accesibilidad del sitio web. Estas herramientas proporcionaron recomendaciones para mejorar la accesibilidad, como el uso de texto alternativo en imágenes y mejorar la visibilidad de los elementos interactivos.

3.2.3. Basado en los informes obtenidos, se implementaron las mejoras sugeridas, como la adición de descripciones más claras en los enlaces y el ajuste de contraste para mejorar la legibilidad.

### Producto:
- https://pagespeed.web.dev/analysis/https-falbmun0906-github-io-Proyecto_LMYSGI_FAM-index-html/rjvfc6npj6?form_factor=desktop&category=performance&category=accessibility&category=best-practices&category=seo&hl=es&utm_source=lh-chrome-ext


## **Presentación del Proyecto (Videotutorial)**  
_(Resumen del contenido del videotutorial, puntos clave presentados y justificación del diseño.)_  
