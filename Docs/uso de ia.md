IA utilizada: gemini 3.6 flash

prompt: Necesito que me ayudes a generar el código de mi portafolio web personal basado en el diseño de Brittany Chiang, escrito en HTML5 semántico y CSS3. No incluyas nada de JavaScript por ahora.

Mi información personal para el contenido es la siguiente:

Nombre: Matías Nail

Título/Rol: Estudiante de Bachiller en Ciencias y Humanidades - Ingeniería Civil Informática en la UCT

Enfoque: Construyo soluciones de software accesibles, eficientes y enfocadas en bases de datos.

Correo institucional: mnail2026@alu.uct.cl
GitHub: https://github.com/MatiasNail

Por favor, asegúrate de cumplir con la siguiente estructura:

Diseño e Integración: Debe ser un layout de 2 columnas en pantallas grandes (con la columna izquierda fija de tipo sidebar y la columna derecha escroleable), y de 1 columna responsiva en pantallas móviles.

Las 5 secciones obligatorias: Debe incluir tanto en la barra de navegación como en el área de contenido principal las 5 secciones requeridas: Inicio, Sobre mí, Proyectos, Habilidades y Contacto.


Contenido de Secciones:

Inicio: Presentación de tipo Hero con el rol y enfoque.

Sobre mí: Breve párrafo sobre la carrera en la UCT y el gusto por bases de datos y arquitectura de software.

Proyectos: Una tarjeta con un proyecto académico con descripción y etiquetas para tecnologías como MySQL, SQL y Git.

Habilidades: Lista o etiquetas con el stack técnico (MySQL/SQL, Modelado MER/MR, HTML5/CSS3, JavaScript, Git & GitHub).

Contacto: Mensaje breve con un botón directo mailto: hacia mi correo institucional y enlace a GitHub. Sin redes sociales extra como X o Twitter.

Formato de Entrega: Entrega el código 100% funcional y sin omitir partes dentro de dos bloques separados: uno para index.html y otro para style.css.

OUTPUT:

HTML: <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Portafolio profesional de Matías Nail, estudiante de Ingeniería Civil Informática en la UCT.">
    <title>Matías Nail — Student & Software Developer</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Enlace de accesibilidad directo para teclado -->
    <a href="#main-content" class="skip-link">Saltar al contenido principal</a>

    <div class="layout-container">
        
        <!-- COLUMNA IZQUIERDA (Sidebar fija con navegación de 5 secciones) -->
        <header class="sidebar">
            <div>
                <h1 class="name"><a href="#inicio">Matías Nail</a></h1>
                <h2 class="role">Estudiante de Ingeniería Civil Informática</h2>
                <p class="tagline">Construyo soluciones de software accesibles, eficientes y enfocadas en bases de datos.</p>
                
                <!-- Navegación con las 5 secciones requeridas -->
                <nav class="nav-menu" aria-label="Navegación principal">
                    <ul>
                        <li><a href="#inicio" class="active"><span class="nav-line"></span><span class="nav-text">INICIO</span></a></li>
                        <li><a href="#sobre-mi"><span class="nav-line"></span><span class="nav-text">SOBRE MÍ</span></a></li>
                        <li><a href="#proyectos"><span class="nav-line"></span><span class="nav-text">PROYECTOS</span></a></li>
                        <li><a href="#habilidades"><span class="nav-line"></span><span class="nav-text">HABILIDADES</span></a></li>
                        <li><a href="#contacto"><span class="nav-line"></span><span class="nav-text">CONTACTO</span></a></li>
                    </ul>
                </nav>
            </div>

            <!-- Contacto directo y GitHub -->
            <ul class="social-links" aria-label="Enlaces de contacto">
                <li><a href="https://github.com/MatiasNail" target="_blank" rel="noopener" aria-label="Perfil de GitHub">GitHub</a></li>
                <li><a href="mailto:mnail2026@alu.uct.cl" aria-label="Enviar correo a mnail2026@alu.uct.cl">Correo UCT</a></li>
            </ul>
        </header>

        <!-- COLUMNA DERECHA (Contenido principal) -->
        <main id="main-content" class="content">
            
            <!-- 1. INICIO -->
            <section id="inicio" class="section" aria-labelledby="inicio-heading">
                <h2 id="inicio-heading" class="mobile-section-title">Inicio</h2>
                <div class="hero-box">
                    <p class="hero-intro">Hola, mi nombre es</p>
                    <h3 class="hero-name">Matías Nail.</h3>
                    <p class="hero-text">
                        Estudiante de la Universidad Católica de Temuco. Desarrollo proyectos enfocados en la resolución de problemas mediante modelado de datos, SQL y desarrollo web estático.
                    </p>
                </div>
            </section>

            <!-- 2. SOBRE MÍ -->
            <section id="sobre-mi" class="section" aria-labelledby="sobre-mi-heading">
                <h2 id="sobre-mi-heading" class="section-title-desktop">Sobre mí</h2>
                <p>
                    Actualmente me encuentro cursando la carrera de <strong>Ingeniería Civil Informática en la UCT</strong>. Me apasiona la arquitectura de software, el diseño de bases de datos relacionales y el aprendizaje continuo de nuevas herramientas.
                </p>
            </section>

            <!-- 3. PROYECTOS -->
            <section id="proyectos" class="section" aria-labelledby="proyectos-heading">
                <h2 id="proyectos-heading" class="section-title-desktop">Proyectos</h2>
                
                <article class="project-card">
                    <div class="project-year">2026</div>
                    <div class="project-info">
                        <h3 class="project-title">Sistema de Gestión de Base de Datos — UCT</h3>
                        <p class="project-desc">
                            Diseño integral desde el Modelado Entidad-Relación (MER) hasta la migración al Modelo Relacional y la ejecución de scripts con restricciones avanzadas y consultas SQL.
                        </p>
                        <ul class="tags" aria-label="Tecnologías utilizadas">
                            <li>MySQL</li>
                            <li>SQL</li>
                            <li>Draw.io</li>
                            <li>Git</li>
                        </ul>
                    </div>
                </article>
            </section>

            <!-- 4. HABILIDADES -->
            <section id="habilidades" class="section" aria-labelledby="habilidades-heading">
                <h2 id="habilidades-heading" class="section-title-desktop">Habilidades</h2>
                <ul class="tags" aria-label="Stack Técnico">
                    <li>MySQL / SQL</li>
                    <li>Modelado MER / MR</li>
                    <li>HTML5 / CSS3</li>
                    <li>JavaScript</li>
                    <li>Git & GitHub</li>
                </ul>
            </section>

            <!-- 5. CONTACTO -->
            <section id="contacto" class="section" aria-labelledby="contacto-heading">
                <h2 id="contacto-heading" class="section-title-desktop">Contacto</h2>
                <p class="contact-text">
                    ¿Tienes alguna consulta o propuesta de proyecto académico? Puedes escribirme directamente a mi correo institucional o revisar mis repositorios en GitHub.
                </p>
                <div class="contact-actions">
                    <a href="mailto:mnail2026@alu.uct.cl" class="contact-btn">Enviar correo</a>
                </div>
            </section>

        </main>
    </div>

</body>
</html>

CSS: 

html {
    scroll-behavior: smooth;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    background-color: #0f172a;
    color: #94a3b8;
    line-height: 1.6;
    overflow-x: hidden;
}

/* Skip link accesibilidad (oculto fuera de pantalla hasta presionar Tab) */
.skip-link {
    position: absolute;
    top: -100px;
    left: 16px;
    background: #5eead4;
    color: #0f172a;
    padding: 8px 16px;
    font-weight: bold;
    border-radius: 4px;
    z-index: 1000;
    transition: top 0.2s ease;
    text-decoration: none;
}

.skip-link:focus {
    top: 16px;
}

/* Contenedor Principal (Flexbox 2 columnas) */
.layout-container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 24px;
    display: flex;
    flex-direction: column;
}

@media (min-width: 1024px) {
    .layout-container {
        flex-direction: row;
        justify-content: space-between;
        gap: 64px;
        padding: 0 64px;
    }

    .sidebar {
        position: sticky;
        top: 0;
        height: 100vh;
        width: 45%;
        padding: 80px 0;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .content {
        width: 55%;
        padding: 80px 0;
    }

    .mobile-section-title { 
        display: none; 
    }
}

/* Sidebar e Identidad */
.name a {
    font-size: 2.5rem;
    font-weight: 700;
    color: #f8fafc;
    text-decoration: none;
    letter-spacing: -0.025em;
}

.role {
    font-size: 1.1rem;
    font-weight: 500;
    color: #e2e8f0;
    margin-top: 8px;
}

.tagline {
    margin-top: 16px;
    max-width: 320px;
    font-size: 0.95rem;
    color: #94a3b8;
}

/* Menú de Navegación */
.nav-menu {
    margin-top: 48px;
}

.nav-menu ul {
    list-style: none;
}

.nav-menu li {
    margin-bottom: 16px;
}

.nav-menu a {
    display: flex;
    align-items: center;
    text-decoration: none;
    color: #64748b;
    font-size: 0.8rem;
    font-weight: 700;
    letter-spacing: 0.15em;
    transition: all 0.2s ease;
}

.nav-line {
    width: 32px;
    height: 1px;
    background-color: #64748b;
    margin-right: 16px;
    transition: all 0.2s ease;
}

.nav-menu a:hover, 
.nav-menu a.active {
    color: #f8fafc;
}

.nav-menu a:hover .nav-line, 
.nav-menu a.active .nav-line {
    width: 64px;
    background-color: #f8fafc;
}

/* Secciones del Contenido */
.section {
    margin-bottom: 80px;
}

.section p {
    color: #94a3b8;
    font-size: 0.98rem;
}

.section p strong {
    color: #e2e8f0;
}

.section-title-desktop, 
.mobile-section-title {
    font-size: 0.875rem;
    text-transform: uppercase;
    letter-spacing: 0.1em;
    color: #f8fafc;
    margin-bottom: 24px;
    font-weight: 700;
}

/* Sección 1: Inicio / Hero */
.hero-intro {
    color: #5eead4;
    font-size: 0.9rem;
    font-family: monospace;
    margin-bottom: 8px;
}

.hero-name {
    font-size: 2rem;
    color: #f8fafc;
    margin-bottom: 12px;
}

.hero-text {
    font-size: 1rem;
    line-height: 1.6;
}

/* Tarjetas de Proyectos */
.project-card {
    display: flex;
    gap: 16px;
    padding: 20px;
    border-radius: 8px;
    background-color: rgba(255, 255, 255, 0.02);
    border: 1px solid rgba(255, 255, 255, 0.05);
}

.project-year {
    font-size: 0.75rem;
    font-weight: 600;
    color: #64748b;
    min-width: 50px;
}

.project-title {
    font-size: 1rem;
    color: #f8fafc;
    margin-bottom: 8px;
}

.project-desc {
    font-size: 0.9rem;
    margin-bottom: 16px;
}

/* Etiquetas (Tags) */
.tags {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    list-style: none;
}

.tags li {
    font-size: 0.75rem;
    background-color: rgba(45, 212, 191, 0.1);
    color: #5eead4;
    padding: 4px 12px;
    border-radius: 9999px;
    font-weight: 500;
}

/* Redes y Enlaces */
.social-links {
    display: flex;
    gap: 16px;
    list-style: none;
    align-items: center;
    margin-top: 32px;
}

.social-links a {
    color: #94a3b8;
    text-decoration: none;
    font-size: 0.9rem;
    transition: color 0.2s ease;
}

.social-links a:hover {
    color: #5eead4;
}

/* Botón de Contacto */
.contact-actions {
    margin-top: 20px;
}

.contact-btn {
    display: inline-block;
    padding: 10px 20px;
    border: 1px solid #5eead4;
    color: #5eead4;
    border-radius: 4px;
    text-decoration: none;
    font-size: 0.85rem;
    font-weight: 600;
    transition: all 0.2s ease;
}

.contact-btn:hover {
    background-color: rgba(94, 234, 212, 0.1);
}