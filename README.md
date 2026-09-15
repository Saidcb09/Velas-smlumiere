# Velas-smlumiere
Velas hechas con amor
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vela Astronauta con Ramo - S&M Lumière</title>
    <style>
        :root {
            --bg-color: #faf6f0;
            --card-bg: #ffffff;
            --text-color: #433835;
            --accent-color: #8c6d58;
            --accent-light: #f4ede6;
            --whatsapp-color: #25d366;
            --star-color: #e5b842;
            --border-color: #f0e6dd;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
        }

        body {
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            justify-content: center;
            padding: 30px 15px;
            -webkit-font-smoothing: antialiased;
        }

        .container {
            max-width: 440px;
            width: 100%;
            background: var(--card-bg);
            border-radius: 24px;
            box-shadow: 0 15px 35px rgba(140, 109, 88, 0.06);
            padding: 30px 22px;
            border: 1px solid var(--border-color);
        }

        /* Branding minimalista */
        .brand-header {
            text-align: center;
            margin-bottom: 22px;
        }

        .logo {
            width: 96px;
            height: 96px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 10px;
            border: 2px solid var(--border-color);
            padding: 3px;
            background: white;
        }

        .brand-subtitle {
            font-size: 0.75rem;
            letter-spacing: 3px;
            color: var(--accent-color);
            text-transform: uppercase;
            font-weight: 600;
        }

        /* Imagen del Producto */
        .product-image-container {
            text-align: center;
            margin-bottom: 22px;
        }

        .product-image-wrapper {
            display: inline-block;
            padding: 8px;
            background: white;
            border: 1px solid var(--border-color);
            border-radius: 18px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.03);
        }

        .product-image {
            width: 240px;
            height: 240px;
            border-radius: 12px;
            object-fit: cover;
            display: block;
            margin: 0 auto;
        }

        .image-disclaimer {
            font-size: 0.7rem;
            color: #999;
            font-style: italic;
            margin-top: 8px;
            letter-spacing: 0.5px;
        }

        /* Títulos y Secciones */
        .product-title {
            font-size: 1.4rem;
            font-weight: 500;
            margin-bottom: 18px;
            text-align: center;
            letter-spacing: -0.5px;
            color: var(--text-color);
        }

        .section-subtitle {
            font-size: 0.85rem;
            font-weight: 600;
            color: var(--accent-color);
            margin-bottom: 10px;
            margin-top: 22px;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        .details-list {
            list-style: none;
            background: var(--accent-light);
            padding: 16px 18px;
            border-radius: 14px;
            font-size: 0.9rem;
        }

        .details-list li {
            margin-bottom: 10px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .details-list li:last-child {
            margin-bottom: 0;
        }

        .details-label {
            font-weight: 600;
            color: var(--accent-color);
            font-size: 0.85rem;
        }

        .care-text {
            font-size: 0.88rem;
            line-height: 1.6;
            background: var(--accent-light);
            padding: 16px 18px;
            border-radius: 14px;
            color: var(--text-color);
        }

        /* Botón WhatsApp corregido */
        .btn-whatsapp {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            background-color: var(--whatsapp-color);
            color: white;
            text-decoration: none;
            padding: 14px;
            border-radius: 14px;
            font-weight: 600;
            font-size: 0.9rem;
            box-shadow: 0 6px 16px rgba(37, 211, 102, 0.25);
            margin-top: 25px;
            transition: all 0.2s ease;
        }

        .btn-whatsapp:active {
            transform: scale(0.98);
        }

        /* Calificación */
        .rating-section {
            border-top: 1px solid var(--border-color);
            margin-top: 28px;
            padding-top: 20px;
            text-align: center;
        }

        .rating-title {
            font-size: 0.85rem;
            margin-bottom: 12px;
            font-weight: 600;
            color: var(--text-color);
        }

        .stars {
            display: flex;
            justify-content: center;
            direction: rtl;
            gap: 6px;
        }

        .stars input {
            display: none;
        }

        .stars label {
            font-size: 1.6rem;
            color: #e0d4cc;
            cursor: pointer;
            transition: color 0.2s;
        }

        .stars label:hover,
        .stars label:hover ~ label,
        .stars input:checked ~ label {
            color: var(--star-color);
        }

        .rating-thanks {
            display: none;
            font-size: 0.8rem;
            color: var(--accent-color);
            margin-top: 10px;
            font-weight: 500;
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Encabezado con Marca/Logo -->
    <div class="brand-header">
        <img src="58426.jpg" alt="Logo S&M Lumière" class="logo">
        <p class="brand-subtitle">S&M Lumière</p>
    </div>

    <!-- Fotografía del producto -->
    <div class="product-image-container">
        <div class="product-image-wrapper">
            <img src="58500_2.jpg" alt="Vela Astronauta con Ramo" class="product-image">
        </div>
        <p class="image-disclaimer">Vela Astronauta Artesanal</p>
    </div>

    <!-- Título -->
    <h1 class="product-title">Vela Astronauta con Ramo</h1>

    <!-- Características -->
    <h3 class="section-subtitle">Detalles de la pieza</h3>
    <ul class="details-list">
        <li><span class="details-label">Aroma</span> <span>Andalucía</span></li>
        <li><span class="details-label">Duración</span> <span>4 a 6 horas</span></li>
        <li><span class="details-label">Cera</span> <span>100% Soya Artesanal</span></li>
        <li><span class="details-label">Diseño</span> <span>Modelado a mano</span></li>
    </ul>

    <!-- Consejos / Cuidados -->
    <h3 class="section-subtitle">Cuidados</h3>
    <p class="care-text">
        Disfruta de tu pieza recortando la mecha a unos 5 mm antes de cada encendido para asegurar una combustión limpia y prolongada. Evita corrientes de aire.
    </p>

    <!-- Botón de WhatsApp Corregido -->
    <a href="https://wa.me/573189392063?text=¡Hola!%20Tengo%20una%20duda%20sobre%20los%20cuidados%20de%20mi%20Vela%20Astronauta." 
       class="btn-whatsapp" target="_blank">
        <svg width="18" height="18" fill="white" viewBox="0 0 24 24">
            <path d="M12.031 2c-5.514 0-9.999 4.486-9.999 10 0 1.763.46 3.483 1.332 5.004L2 22l5.148-1.348C8.625 21.498 10.312 22 12.031 22c5.515 0 10-4.486 10-10s-4.485-10-10-10zm5.952 14.155c-.252.712-1.463 1.359-2.01 1.417-.502.054-1.144.083-3.327-.818-2.793-1.154-4.577-4.008-4.717-4.195-.14-.187-1.139-1.517-1.139-2.893 0-1.376.712-2.052.966-2.333.253-.28.557-.35.743-.35.187 0 .373.003.535.01.173.007.406-.066.634.48.239.574.815 1.988.887 2.133.072.146.12.316.024.505-.096.188-.144.305-.287.472-.144.167-.302.373-.431.502-.144.143-.294.3-.126.587.168.287.747 1.233 1.603 1.996 1.101.98 2.029 1.285 2.316 1.428.287.143.455.12.623-.072.168-.192.718-.838.911-1.125.192-.287.383-.239.646-.144.264.096 1.674.789 1.961.933.287.144.478.216.55.336.072.12.072.695-.18 1.407z"/>
        </svg>
        Consultar por WhatsApp
    </a>

    <!-- Sistema de Calificación -->
    <div class="rating-section">
        <p class="rating-title">¿Qué te parece este diseño?</p>
        <div class="stars">
            <input type="radio" id="star5" name="rating" value="5" onclick="showThanks()"><label for="star5">★</label>
            <input type="radio" id="star4" name="rating" value="4" onclick="showThanks()"><label for="star4">★</label>
            <input type="radio" id="star3" name="rating" value="3" onclick="showThanks()"><label for="star3">★</label>
            <input type="radio" id="star2" name="rating" value="2" onclick="showThanks()"><label for="star2">★</label>
            <input type="radio" id="star1" name="rating" value="1" onclick="showThanks()"><label for="star1">★</label>
        </div>
        <p id="thanks-msg" class="rating-thanks">¡Gracias por tu valoración! ✨</p>
    </div>
</div>

<script>
    function showThanks() {
        document.getElementById('thanks-msg').style.display = 'block';
    }
</script>

</body>
</html>
