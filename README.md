Portafolio Profesional - Matias Nail

*en este repositorio se encuentra el código fuente y toda la estructura de mi Portafolio Web Profesional, el cual fué desarrollado como parte de la evaluación 2 del ramo "Desarrollo de Frontend"



# Links del Portafolio Desplegado:



*GitHub Pages: https://icinf1107-2026.github.io/Web01Matias/


*Vercel: https://web01-matias-mwsnhpek3-matiasnail.vercel.app/


*Render: https://web01matias.onrender.com/


# Público Objetivo y Propósito:


*Principal audiencia esperada: Actualmente dirigído al docente asignado de mi sección así como a Empleadores de desarrollo de frontend


# Fundamentación y Decisiones sobre el Diseño:


-Jerarquía visual y Decisiones de Diseño:

*Versión de escritorio adopta un layout split en donde la barra lateral izquierda permanece fija ('position: sticky')
*Priorización de Información, presentando el orden preciso de interés para reclutadores 


-Diseño Responsivo

*Celular (<640px): adopta un diseño de columna vertical facilitando la visualización en cascada
*Tablet (640-768px): ajuste en margenes y espaciado de tarjetas (padding) así como en tamaños tipográficos
*Escritorio (>1024px): layout de 2 columnas en paralelo ('flex-direction: row')


-Accesibilidad e Inclusividad

*Navegacion por teclado: Se incluyó un enlace para saltar directamente al contenido principal ('skip-link')
*HTML Semántico: uso de tarjetas semánticas para cada sección perteneciente (<header>, <nav>, <main>, <section>, <article> y <footer>)
*Atributos Aria: declaracion de aria-label en navegación y secciones para mejorar la compatibilidad con tecnologías de asistencia
*Contraste y Legibilidad: elección de paleta de colores sobre umn fondo oscuro, asegurando un contraste suficiente y focos de ateción resaltados con tono turquesa


# Tecnologías utilizadas

-HTML5: Estructuración semántica de la página
-CSS3: estilización de la página
-Git y GitHub: Control de versiones
-Vercel y GitHub Pages: para el despliegue de proyectos 



# Estructura del Proyecto

Web01Matias/
├── Assets/
│   ├── Css/
│   │   └── style.css
│   └── Js/
│       └── script.js
├── docs/
├── index.html
└── README.md