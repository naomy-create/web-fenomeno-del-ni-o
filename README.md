# web-fenomeno-del-ni-o
página

HTML:
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Fenómeno El Niño: Guía e Información</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header class="navbar">
        <div class="logo">El Niño Informa</div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#causas">Causas</a></li>
                <li><a href="#consecuencias">Consecuencias</a></li>
                <li><a href="#prevencion">Prevención</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <div class="hero-content">
            <h1>Comprendiendo el Fenómeno El Niño</h1>
            <p>Descubre sus causas, impactos en el planeta y cómo podemos prepararnos mejor.</p>
            <a href="#causas" class="btn">Saber más</a>
        </div>
    </section>

    <section id="causas" class="container">
        <h2>Causas del Fenómeno</h2>
        <div class="card-grid">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&w=600&q=80" alt="Océano y clima">
                <h3>Debilitamiento de Vientos</h3>
                <p>Los vientos alisios que normalmente mecen el Pacífico se debilitan, permitiendo que el agua cálida fluya hacia el este.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=600&q=80" alt="Calentamiento del agua">
                <h3>Aumento de Temperatura</h3>
                <p>El calentamiento inusual de la superficie del Océano Pacífico altera los patrones de presión atmosférica global.</p>
            </div>
        </div>
    </section>

    <section id="consecuencias" class="bg-light">
        <div class="container">
            <h2>Consecuencias Principales</h2>
            <div class="card-grid">
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1515694346937-94d85e41e6f0?auto=format&fit=crop&w=600&q=80" alt="Lluvias intensas">
                    <h3>Lluvias e Inundaciones</h3>
                    <p>En ciertas regiones se producen precipitaciones extremas que originan desbordamientos y deslices de tierra.</p>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1504386106331-3e4e71712b38?auto=format&fit=crop&w=600&q=80" alt="Sequía">
                    <h3>Sequías Extremas</h3>
                    <p>Mientras unas zonas sufren lluvias inundantes, otras experimentan falta severa de agua, afectando cultivos.</p>
                </div>
                <div class="card">
                    <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&fit=crop&w=600&q=80" alt="Ecosistemas marinos">
                    <h3>Impacto Marino</h3>
                    <p>La alteración de la temperatura causa la migración o pérdida de especies marinas esenciales para la pesca.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="prevencion" class="container">
        <h2>Medidas de Prevención</h2>
        <ul class="prevention-list">
            <li><strong>Limpieza de cauces:</strong> Mantener limpios los drenajes, ríos y quebradas para evitar desbordes.</li>
            <li><strong>Refuerzo de techos:</strong> Asegurar y reparar viviendas antes de las temporadas de lluvia.</li>
            <li><strong>Almacenamiento responsable:</strong> Reservar agua limpia y alimentos no perecederos.</li>
            <li><strong>Mochila de emergencia:</strong> Contar con suministros básicos como linternas, botiquín y radio a pilas.</li>
        </ul>
        <button id="btn-alerta" class="btn">Activar recordatorio de prevención</button>
    </section>

    <footer>
        <p>&copy; 2026 - Conciencia Climática y Prevención. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

