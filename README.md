<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Bella Italia — Cocina Italiana</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>

<header class="topbar">
  <div class="brand">
    <div class="brand-mark">BI</div>
    <div class="brand-text">
      <span class="brand-title">Bella Italia</span>
      <span class="brand-subtitle">Cucina autentica dal cuore</span>
    </div>
  </div>

  <nav class="nav">
    <a href="#inicio">Inicio</a>
    <a href="#especialidades">Especialidades</a>
    <a href="#galeria">Galería</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#reservaciones">Reservaciones</a>
  </nav>

  <a class="cta-whatsapp" href="https://wa.me/527770000000?text=Hola%2C%20quiero%20reservar%20en%20Bella%20Italia." target="_blank" rel="noopener">
    Reserva por WhatsApp
  </a>
</header>

<main>
  <!-- HERO -->
  <section id="inicio" class="hero">
    <div class="hero-content">
      <p class="hero-tag">Experiencia italiana en cada plato</p>
      <h1>Pastas artesanales, pizzas al horno de piedra y vinos seleccionados.</h1>
      <p class="hero-text">
        Un rincón de Italia en tu ciudad. Ingredientes frescos, recetas tradicionales y un ambiente cálido
        para compartir en pareja, con amigos o en familia.
      </p>
      <div class="hero-actions">
        <a href="#especialidades" class="btn btn-primary">Ver especialidades</a>
        <a href="#reservaciones" class="btn btn-ghost">Reservar mesa</a>
      </div>
      <div class="hero-highlights">
        <span>🍝 Pasta hecha a mano</span>
        <span>🍕 Pizzas napolitanas</span>
        <span>🍷 Carta de vinos italianos</span>
      </div>
    </div>
    <div class="hero-image-card">
      <img src="https://source.unsplash.com/800x600/?italian,restaurant" alt="Mesa con comida italiana">
      <div class="hero-image-label">
        Noche italiana · Menú degustación desde $399
      </div>
    </div>
  </section>

  <!-- ESPECIALIDADES -->
  <section id="especialidades" class="section section-especialidades">
    <header class="section-header">
      <h2>Especialidades de la casa</h2>
      <p>Platos icónicos de la cocina italiana preparados al momento.</p>
    </header>

    <div class="cards-grid">
      <article class="card">
        <div class="card-image">
          <img src="https://source.unsplash.com/600x400/?pasta,italian" alt="Plato de pasta italiana">
        </div>
        <div class="card-body">
          <h3>Tagliatelle al pesto</h3>
          <p>Pasta fresca con pesto de albahaca, piñones tostados y queso parmesano.</p>
          <div class="card-footer">
            <span class="price">$185 MXN</span>
            <span class="tag">Vegetariano</span>
          </div>
        </div>
      </article>

      <article class="card">
        <div class="card-image">
          <img src="https://source.unsplash.com/600x400/?pizza,margherita" alt="Pizza margherita italiana">
        </div>
        <div class="card-body">
          <h3>Pizza Margherita</h3>
          <p>Masa madre, salsa de tomate San Marzano, mozzarella fresca y hojas de albahaca.</p>
          <div class="card-footer">
            <span class="price">$210 MXN</span>
            <span class="tag">Horno de piedra</span>
          </div>
        </div>
      </article>

      <article class="card">
        <div class="card-image">
          <img src="https://source.unsplash.com/600x400/?italian,dessert" alt="Postre tiramisú italiano">
        </div>
        <div class="card-body">
          <h3>Tiramisú clásico</h3>
          <p>Capas de mascarpone, café espresso y cacao, el final perfecto para tu comida.</p>
          <div class="card-footer">
            <span class="price">$115 MXN</span>
            <span class="tag">Postre estrella</span>
          </div>
        </div>
      </article>

      <article class="card">
        <div class="card-image">
          <img src="https://source.unsplash.com/600x400/?risotto,italian" alt="Plato de risotto italiano">
        </div>
        <div class="card-body">
          <h3>Risotto ai funghi</h3>
          <p>Arroz arborio cremoso con mezcla de hongos, vino blanco y parmesano.</p>
          <div class="card-footer">
            <span class="price">$195 MXN</span>
            <span class="tag">Recomendado del chef</span>
          </div>
        </div>
      </article>
    </div>
  </section>

  <!-- GALERÍA -->
  <section id="galeria" class="section section-galeria">
    <header class="section-header">
      <h2>Galería de sabores</h2>
      <p>Un vistazo visual a lo que te espera en Bella Italia.</p>
    </header>

    <div class="gallery-grid">
      <figure class="gallery-item">
        <img src="https://source.unsplash.com/500x400/?italian,pasta" alt="Pasta italiana">
        <figcaption>Pasta fresca con salsa de tomate y albahaca.</figcaption>
      </figure>
      <figure class="gallery-item">
        <img src="https://source.unsplash.com/500x400/?italian,antipasto" alt="Antipasto italiano">
        <figcaption>Antipasto con quesos, aceitunas y embutidos.</figcaption>
      </figure>
      <figure class="gallery-item">
        <img src="https://source.unsplash.com/500x400/?italian,wine" alt="Vinos italianos">
        <figcaption>Selección de vinos italianos para maridar tu experiencia.</figcaption>
      </figure>
      <figure class="gallery-item">
        <img src="https://source.unsplash.com/500x400/?italian,restaurant,table" alt="Restaurante italiano">
        <figcaption>Ambiente acogedor para cenas especiales.</figcaption>
      </figure>
    </div>
  </section>

  <!-- NOSOTROS -->
  <section id="nosotros" class="section section-nosotros">
    <div class="nosotros-text">
      <h2>Un pedacito de Italia en tu ciudad</h2>
      <p>
        Bella Italia nace de una familia con raíces italianas que llegó a México con una maleta llena de recetas
        y tradición. Creemos en la cocina lenta, en el pan recién horneado y en esa mesa larga donde siempre cabe uno más.
      </p>
      <p>
        Nuestro equipo cuida cada detalle: desde la selección de los ingredientes hasta la música que te acompaña
        mientras disfrutas de tu plato favorito.
      </p>
      <ul class="nosotros-list">
        <li>Ingredientes frescos y de temporada.</li>
        <li>Opciones vegetarianas y sin gluten.</li>
        <li>Menú especial para grupos y eventos.</li>
      </ul>
    </div>
    <div class="nosotros-card">
      <h3>Horarios</h3>
      <p>Lunes a jueves · 1:00 pm – 10:00 pm</p>
      <p>Viernes y sábado · 1:00 pm – 11:30 pm</p>
      <p>Domingo · 2:00 pm – 9:00 pm</p>
      <hr>
      <h3>Ubicación</h3>
      <p>Calle Italia #123, Col. Centro<br>Cuernavaca, Morelos</p>
      <p class="nosotros-note">Estacionamiento y terraza al aire libre.</p>
    </div>
  </section>

  <!-- RESERVACIONES -->
  <section id="reservaciones" class="section section-reservaciones">
    <header class="section-header">
      <h2>Reservaciones</h2>
      <p>Déjanos tus datos y confirmaremos tu mesa por WhatsApp o correo.</p>
    </header>

    <div class="reservaciones-grid">
      <form class="form-reserva">
        <div class="field-group">
          <label>
            Nombre completo
            <input type="text" name="nombre" placeholder="Tu nombre">
          </label>
          <label>
            Teléfono
            <input type="tel" name="telefono" placeholder="777 000 0000">
          </label>
        </div>

        <div class="field-group">
          <label>
            Correo electrónico
            <input type="email" name="correo" placeholder="tucorreo@ejemplo.com">
          </label>
          <label>
            Número de personas
            <select name="personas">
              <option value="">Selecciona</option>
              <option value="2">2 personas</option>
              <option value="3">3 personas</option>
              <option value="4">4 personas</option>
              <option value="5">5 personas</option>
              <option value="6">6 personas</option>
              <option value="7+">7 o más</option>
            </select>
          </label>
        </div>

        <div class="field-group">
          <label>
            Fecha
            <input type="date" name="fecha">
          </label>
          <label>
            Hora aproximada
            <input type="time" name="hora">
          </label>
        </div>

        <label class="field-full">
          Comentarios
          <textarea name="comentarios" rows="4" placeholder="¿Alguna ocasión especial, alergias o petición especial?"></textarea>
        </label>

        <button type="submit" class="btn btn-primary full">
          Enviar solicitud de reserva
        </button>
        <p class="form-note">
          *Este formulario es demostrativo. En un sitio real se conectaría a tu sistema de reservas o correo.
        </p>
      </form>

      <div class="reservaciones-info">
        <div class="info-card">
          <h3>Reserva rápida por WhatsApp</h3>
          <p>Si prefieres, mándanos mensaje directo:</p>
          <a class="cta-whatsapp-large" href="https://wa.me/527770000000?text=Hola%2C%20quiero%20reservar%20una%20mesa%20en%20Bella%20Italia." target="_blank" rel="noopener">
            Abrir WhatsApp
          </a>
        </div>

        <div class="info-card">
          <h3>Recomendaciones</h3>
          <ul>
            <li>Para grupos de más de 6 personas, reserva con al menos 24 horas de anticipación.</li>
            <li>Menciona si celebras cumpleaños o aniversario para prepararte una sorpresa.</li>
            <li>Pregunta por nuestro menú degustación italiano.</li>
          </ul>
        </div>
      </div>
    </div>
  </section>
</main>

<footer class="footer">
  <div class="footer-content">
    <p>&copy; 2025 Bella Italia. Todos los derechos reservados.</p>
    <p class="footer-links">
      <a href="#inicio">Inicio</a>
      <span>·</span>
      <a href="#especialidades">Menú</a>
      <span>·</span>
      <a href="#reservaciones">Reservar</a>
    </p>
  </div>
</footer>

</body>
</html>
