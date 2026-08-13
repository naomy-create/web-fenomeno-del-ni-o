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

CSS:
/* Reset básico */
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

:root {
    --verde-oscuro: #1b4332;
    --verde-medio: #2d6a4f;
    --verde-claro: #52b788;
    --verde-suave: #d8f3dc;
    --blanco: #ffffff;
    --gris-fondo: #f8f9fa;
    --texto: #212529;
}

body {
    color: var(--texto);
    background-color: var(--blanco);
    line-height: 1.6;
}

/* Navegación */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: var(--verde-oscuro);
    padding: 1rem 2rem;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar .logo {
    color: var(--blanco);
    font-weight: bold;
    font-size: 1.4rem;
}

.navbar ul {
    display: flex;
    list-style: none;
}

.navbar ul li a {
    color: var(--blanco);
    text-decoration: none;
    margin-left: 1.5rem;
    transition: color 0.3s;
}

.navbar ul li a:hover {
    color: var(--verde-claro);
}

/* Hero section */
.hero {
    background: linear-gradient(rgba(27, 67, 50, 0.75), rgba(45, 106, 79, 0.75)), 
                url('https://images.unsplash.com/photo-1518837695005-2083093ee35b?auto=format&fit=crop&w=1200&q=80') center/cover;
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: var(--blanco);
    padding: 0 1rem;
}

.hero h1 {
    font-size: 2.8rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
}

/* Botones */
.btn {
    display: inline-block;
    background-color: var(--verde-claro);
    color: var(--verde-oscuro);
    padding: 0.8rem 1.5rem;
    border: none;
    border-radius: 25px;
    font-weight: bold;
    cursor: pointer;
    text-decoration: none;
    transition: background-color 0.3s, transform 0.2s;
}

.btn:hover {
    background-color: var(--verde-suave);
    transform: translateY(-2px);
}

/* Secciones y Contenedores */
.container {
    padding: 4rem 2rem;
    max-width: 1200px;
    margin: 0 auto;
}

.bg-light {
    background-color: var(--verde-suave);
}

h2 {
    text-align: center;
    color: var(--verde-oscuro);
    font-size: 2rem;
    margin-bottom: 2.5rem;
}

/* Tarjetas (Cards) */
.card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 2rem;
}

.card {
    background-color: var(--blanco);
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 4px 15px rgba(0,0,0,0.08);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card img {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.card h3 {
    color: var(--verde-medio);
    padding: 1rem 1rem 0.5rem;
}

.card p {
    padding: 0 1rem 1.5rem;
    color: #555;
    font-size: 0.95rem;
}

/* Lista de prevención */
.prevention-list {
    list-style: none;
    max-width: 800px;
    margin: 0 auto 2rem auto;
}

.prevention-list li {
    background-color: var(--gris-fondo);
    border-left: 5px solid var(--verde-medio);
    padding: 1rem;
    margin-bottom: 1rem;
    border-radius: 0 8px 8px 0;
}

#btn-alerta {
    display: block;
    margin: 0 auto;
}

/* Footer */
footer {
    background-color: var(--verde-oscuro);
    color: var(--blanco);
    text-align: center;
    padding: 1.5rem;
    font-size: 0.9rem;
}

/* Diseño responsivo */
@media (max-width: 768px) {
    .navbar {
        flex-direction: column;
        gap: 1rem;
    }
    
    .hero h1 {
        font-size: 2rem;
    }
}
