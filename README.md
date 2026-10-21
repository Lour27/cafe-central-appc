<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Café Central - Bienvenidos</title>
    <link rel="stylesheet" href="../static/css/estilos.css">
</head>
<body>
    <!-- NAVBAR -->
    <header>
        <nav class="navbar">
            <h1 class="logo">☕ Café Central</h1>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#menu">Menú</a></li>
                <li><a href="/registro" class="btn-registro">Registrarse</a></li>
            </ul>
        </nav>
    </header>

    <!-- PORTADA PRINCIPAL -->
    <section id="inicio" class="hero">
        <div class="hero-text">
            <h2>El mejor café de la ciudad, ahora en línea</h2>
            <p>Pide tu café favorito, regístrate y sigue tu pedido en tiempo real.</p>
            <div class="botones">
                <a href="/registro" class="btn-primary">Crear mi cuenta</a>
                <a href="#menu" class="btn-secundario">Ver menú</a>
            </div>
            <small>¿Ya tienes cuenta? <a href="/login">Inicia sesión aquí</a></small>
        </div>
        <div class="hero-img">
            <img src="https://images.unsplash.com/photo-1445116572660-236099ec97a0" alt="Taza de café">
        </div>
    </section>

    <!-- CÓMO FUNCIONA - DONDE REGISTRARSE -->
    <section class="pasos">
        <h3>¿Cómo pedir?</h3>
        <div class="pasos-contenedor">
            <div class="paso">
                <span>1</span>
                <h4>Regístrate</h4>
                <p>Crea tu cuenta en 30 segundos con tu nombre y correo.</p>
            </div>
            <div class="paso">
                <span>2</span>
                <h4>Elige tu café</h4>
                <p>Consulta nuestro menú con precios y fotos.</p>
            </div>
            <div class="paso">
                <span>3</span>
                <h4>Realiza tu pedido</h4>
                <p>Y consulta el estado de tu pedido cuando quieras.</p>
            </div>
        </div>
    </section>

    <!-- MENÚ RÁPIDO -->
    <section id="menu" class="menu-preview">
        <h3>Nuestros favoritos</h3>
        <div class="cards">
            <div class="card"><h4>Americano</h4><p>$35</p></div>
            <div class="card"><h4>Capuchino</h4><p>$45</p></div>
            <div class="card"><h4>Latte Vainilla</h4><p>$50</p></div>
        </div>
    </section>

    <footer>
        <p>© 2026 Café Central - Proyecto Metodologías Ágiles</p>
    </footer>
</body>
</html>
