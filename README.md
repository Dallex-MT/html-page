# 🛍️ E-Commerce Web Template 🛒

[![Estado](https://img.shields.io/badge/Estado-Completado-success)](https://github.com/username/html-page)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-blue.svg)](LICENSE)

## 📋 Descripción del Proyecto

**E-Commerce Web Template** es una plantilla frontend completa para tiendas en línea, desarrollada con HTML, CSS y JavaScript puro. Este proyecto proporciona una interfaz de usuario moderna y responsive para sitios de comercio electrónico, sin depender de frameworks o bibliotecas complejas para su funcionamiento básico.

La plantilla incluye todas las páginas esenciales que un sitio e-commerce necesita: página de inicio atractiva, catálogo de productos, carrito de compras funcional, sección de contacto, página "sobre nosotros" y un sistema de login/registro de usuarios. Está diseñada para ser fácilmente personalizable y servir como punto de partida para proyectos de comercio electrónico.

## 🚀 Objetivos del Proyecto

- **Demostrar Habilidades Frontend**: Crear una interfaz de usuario completa y funcional utilizando únicamente tecnologías web estándar (HTML, CSS y JavaScript) para mostrar buenas prácticas de desarrollo frontend.

- **Plantilla Reutilizable**: Proporcionar una base sólida y modular que pueda adaptarse fácilmente a diferentes tipos de tiendas en línea, desde pequeñas boutiques hasta catálogos más extensos.

- **Experiencia de Usuario Optimizada**: Implementar una navegación intuitiva, diseño responsive y elementos interactivos que mejoren la experiencia del usuario en todos los dispositivos.

- **Integración Sencilla**: Facilitar la posterior integración con sistemas backend y bases de datos mediante una estructura clara y separación de responsabilidades en el código.

- **Buenas Prácticas**: Demostrar el uso de semántica HTML correcta, CSS bien estructurado y JavaScript modular para servir como ejemplo educativo.

## 📁 Estructura del Proyecto

```
html-page/
│
├── Paginas/                  # Páginas principales del sitio
│   ├── Carrito.html          # Página del carrito de compras
│   ├── Contacto.html         # Página de contacto
│   ├── index.html            # Página de inicio principal
│   ├── Nosotros.html         # Página "Sobre nosotros"
│   └── Tienda.html           # Catálogo de productos
│
├── Recursos/                 # Recursos estáticos
│   ├── CSS/                  # Hojas de estilo
│   │   ├── Carrusel.css      # Estilos para componentes carousel
│   │   ├── EstilosGenerales.css # Estilos base del sitio
│   │   ├── EstilosNavbar.css # Estilos para la barra de navegación
│   │   ├── Opciones.css      # Estilos para componentes diversos
│   │   └── style.css         # Estilos adicionales
│   │
│   ├── Fuentes/              # Archivos de fuentes personalizadas
│   ├── Imagenes/             # Imágenes y recursos gráficos
│   └── Scroll.js             # Script para efectos de desplazamiento
│
├── comandos.txt              # Comandos útiles para el desarrollo
├── index.html                # Redirección a la página principal
├── login.html                # Página de inicio de sesión/registro
└── README.md                 # Documentación del proyecto
```

## 💻 Tecnologías Utilizadas

- **Lenguajes Base**:
  - HTML5
  - CSS3
  - JavaScript (ES6+)

- **Bibliotecas Externas**:
  - Font Awesome (iconos)
  - Google Fonts (tipografía)
  - Owl Carousel (carruseles de productos)
  - Swiper (componentes deslizables)

- **Técnicas Aplicadas**:
  - Diseño Responsive
  - Flexbox y Grid CSS
  - CSS Variables
  - LocalStorage para persistencia del carrito

## ⚙️ Instalación

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/Dallex-MT/html-page.git
   ```

2. Navega al directorio del proyecto:
   ```bash
   cd html-page
   ```

3. No se requieren dependencias adicionales para ejecutar el proyecto, ya que todas las bibliotecas externas se cargan a través de CDN.

## 🔍 Uso

Para visualizar el sitio web localmente:

1. Abre el archivo `index.html` en tu navegador favorito:
   ```bash
   # En Windows
   start index.html
   
   # En macOS
   open index.html
   
   # En Linux
   xdg-open index.html
   ```

2. Alternativamente, puedes utilizar un servidor local:
   ```bash
   # Si tienes Python instalado
   # Python 3
   python -m http.server
   
   # Python 2
   python -m SimpleHTTPServer
   ```

3. Para probar todas las funcionalidades:
   - Explora las diferentes páginas a través del menú de navegación
   - Prueba a añadir productos al carrito desde la página de tienda
   - Completa el formulario de contacto
   - Prueba el formulario de login/registro

## 🤝 Cómo Contribuir

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un Fork del repositorio
   
2. Crea una rama para tu funcionalidad:
   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```

3. Realiza tus cambios siguiendo estas pautas:
   - Mantén la estructura de archivos existente
   - Sigue el estilo de codificación del proyecto
   - Asegúrate de que tu código es responsive

4. Haz commit de tus cambios:
   ```bash
   git commit -m "Añade: descripción clara del cambio"
   ```

5. Sube los cambios a tu repositorio:
   ```bash
   git push origin feature/nueva-funcionalidad
   ```

6. Crea un Pull Request detallando:
   - Qué cambios has realizado
   - Por qué son necesarios
   - Cómo se pueden probar

## 📝 Historial de Cambios

- **v1.2.0** (15/05/2025):
  - Implementación de LocalStorage para persistencia del carrito
  - Mejora de la responsividad en dispositivos móviles
  - Optimización de imágenes para mejor rendimiento
  - Añadidos efectos de hover en productos

- **v1.1.0** (20/04/2025):
  - Añadida página de carrito de compras con funcionalidad JavaScript
  - Implementado sistema de formulario de contacto
  - Mejorada la navegación en dispositivos móviles
  - Corregidos problemas de estilo en diferentes navegadores

- **v1.0.0** (01/03/2025):
  - Lanzamiento inicial
  - Páginas básicas: inicio, tienda, nosotros, contacto
  - Sistema de login/registro
  - Diseño responsive básico

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Créditos

Desarrollado con ❤️ por **DXM**

---

⭐️ **Nota**: Este proyecto ha sido desarrollado con fines educativos y como demostración de habilidades en desarrollo web frontend. No incluye funcionalidad de backend real. ⭐️

