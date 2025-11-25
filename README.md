[index haeri.html](https://github.com/user-attachments/files/23737743/index.haeri.html)
 <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>El Futuro Hídrico | Agua Sostenible y Limpia</title>
    <style>
       
:root {
    --primary-green: 	#10597d; 
    --dark-green: #0b2b3b;  
    --text-color: black ;      
    --background-color:  #8fb8cd ; 
    --hero-blue: #6a9cde;     
    }

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: var(--text-color);
    background-color: white;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
}

h2 {
    font-size: 2.5em;
    color: var(--dark-green);
    text-align: center;
    margin-bottom: 20px;
    font-weight: 700;
}


.hero-section {
    background-image: 
        linear-gradient(rgba(0, 0, 0, 0.4), rgba(0, 0, 0, 0.4)), 
        url('agua.png'); 
    color: white;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 150px 0 100px 0;
    min-height: 60vh; 
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 50px;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    background-color: rgba(0, 0, 0, 0.1);
}

.logo img {
    height: 40px; 
    width: auto; 
    filter: brightness(1.5); 
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 25px;
}

.nav-links a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: var(--primary-green);
}

.cart-icon img {
    height: 25px; 
    filter: invert(100%); 
}

.hero-content {
    text-align: left;
    max-width: 700px;
    margin-left: 50px;
    margin-top: 80px; 
}

.hero-content h1 {
    font-size: 3.5em;
    color: white;
    margin-bottom: 15px;
    line-height: 1.2;
}

.hero-content p {
    font-size: 1.2em;
    color: #e0e0e0;
    margin-bottom: 30px;
    max-width: 500px;
}


.btn {
    padding: 12px 30px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    transition: background-color 0.3s ease, border-color 0.3s ease;
}

.btn-primary {
    background-color: var(--primary-green);
    color: white;
}

.btn-primary:hover {
    background-color: #cadffb;
}

.btn-secondary {
    background-color: transparent;
    color: white;
    border: 2px solid white;
    margin-left: 15px;
}

.btn-secondary:hover {
    background-color: rgba(255, 255, 255, 0.15);
}

.about-section {
    text-align: center;
    padding: 80px 20px;
}

.about-content {
    max-width: 900px;
    margin: 0 auto;
    text-align: justify;
    font-size: 1.1em;
    line-height: 1.6;
}

.products-section {
    background-color: var(--background-color);
    padding: 80px 0; 
    text-align: center;
}

.products-section .container {
    display: block; 
    max-width: 1000px; 
    margin: 0 auto;
}

.product-grid-full {
    display: grid;
    grid-template-columns: repeat(3, 1fr); 
    gap: 30px;
    margin-top: 40px;
}

.product-card {
    border: 1px solid #ddd;
    padding: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    text-align: center; 
}

.product-card img {
    width: 100%;
    height: auto;
    max-height: 180px;
    object-fit: contain;
    margin-bottom: 15px;
}

.product-card h4 {
    color: var(--dark-green);
    font-size: 1.3em;
    margin-bottom: 8px;
}

.product-card p {
    font-size: 0.9em;
    min-height: 50px; 
}

.product-card .price {
    font-weight: bold;
    color: var(--primary-green);
    font-size: 1.4em; 
    margin: 10px 0 0 0; 
}

.campana-section {
    background-color: var(--dark-green); 
    color: white;
    padding: 80px 20px;
    text-align: center;
}

.campana-section h2 {
    color: var(--primary-green); 
    font-size: 2.5em;
    margin-bottom: 10px;
}

.campana-section h3 {
    font-weight: 300;
    max-width: 900px;
    margin: 0 auto 30px auto;
    font-size: 1.5em;
}

.btn-campana {
    border-color: var(--primary-green);
    color: var(--primary-green);
}

.btn-campana:hover {
    background-color: var(--primary-green);
    color: var(--dark-green);
}

.impact-section {
    padding: 60px 20px;
    text-align: center;
    background-color: white;
}

.impact-grid {
    display: flex;
    justify-content: space-around;
    gap: 30px;
}

.impact-item {
    flex-basis: 30%;
    padding: 20px;
    border-radius: 8px;
    background-color: var(--background-color);
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
}

.impact-item h3 {
    font-size: 2.5em;
    color: var(--primary-green);
    margin-bottom: 5px;
}
.testimonials-section {
    background-color: var(--background-color);
    padding: 80px 20px;
    text-align: center;
}

.testimonial-grid {
    display: flex;
    justify-content: space-between;
    gap: 30px;
    max-width: 1000px;
    margin: 0 auto;
}

.testimonial-card {
    flex-basis: 33%;
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 6px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.testimonial-card:hover {
    transform: translateY(-5px);
}

.testimonial-card .quote {
    font-style: italic;
    color: #555;
    min-height: 100px; 
}

.testimonial-card .author {
    font-weight: bold;
    color: var(--primary-green);
    display: block;
    margin-top: 15px;
}

.faq-section {
    padding: 60px 20px;
    text-align: center;
    max-width: 900px;
    margin: 0 auto;
}

.faq-list {
    text-align: left;
}

.faq-item {
    border-bottom: 1px solid #ccc;
    padding: 20px 0;
}

.faq-item h3 {
    color: var(--dark-green);
    font-size: 1.3em;
    font-weight: 600;
    margin-bottom: 5px;
}

.faq-item p {
    color: #666;
    margin-top: 10px;
}

.contact-section {
    text-align: center;
    padding: 50px 20px;
    max-width: 600px;
    margin: 0 auto;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 30px;
}

.contact-form input, .contact-form textarea {
    padding: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
}

.contact-form textarea {
    resize: vertical;
    min-height: 100px;
}

.contact-form .btn-primary {
    padding: 15px;
    background-color: var(--primary-green); 
}

.main-footer {
    background-color: var(--dark-green);
    color: white;
    padding: 40px 20px 10px 20px;
    font-size: 0.9em;
}

.footer-content {
    display: flex;
    justify-content: space-around;
    max-width: 1000px;
    margin: 0 auto 20px auto;
}

.contact-info, .social-links, .other-links {
    padding: 10px;
}

.social-links a {
    color: var(--primary-green);
    text-decoration: none;
    margin-right: 15px;
    font-size: 1.5em; 
    transition: color 0.3s;
}

.social-links a:hover {
    color: white;
}

.designer-credit {
    text-align: center;
    border-top: 1px solid #333;
    padding-top: 10px;
    margin-top: 10px;
    color: #aaa;
}
    </style>
</head>
<body>

    <header class="hero-section">
        <nav class="navbar">
            <div class="logo">
                <img src="aguavida.png" alt="Logo"> 
            </div>
            <ul class="nav-links">
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#impacto">Impacto</a></li>
                <li><a href="#faq">FAQ</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
            
        </nav>
        <div class="hero-content">
            <h1>El Futuro Hídrico de tu Ciudad<br>Agua Sostenible y Limpia.</h1>
            <p>Innovamos para un futuro donde cada gota cuenta.</p>
            <div class="hero-buttons">
                <a href="#productos" class="btn btn-primary">Ver Productos</a>
                <a href="#contacto" class="btn btn-secondary">Contáctanos</a>
            </div>
        </div>
    </header>

    <section id="nosotros" class="about-section">
        <div class="container">
            <h2>Nosotros</h2>
            <div class="about-content">
                <p>Nuestra misión es proporcionar a las comunidades urbanas acceso a agua potable sana y asequible, 
                    utilizando tecnología innovadora para la recolección y purificación eficiente de recursos hídricos 
                    como el agua de lluvia y lagos. Buscamos establecer un estándar de limpieza, organización y economía 
                    en el suministro de agua para el consumo ciudadano. Creemos que el acceso al agua limpia es un derecho, no un privilegio.</p>
            </div>
        </div>
    </section>
            
     <section id="productos" class="products-section">
        <div class="container">
            <h2>Productos</h2>
            
            <div class="product-grid-full"> 
                <div class="product-card">
                    <img src="Minipurificadora.jpg" alt="Mini purificadora">
                    <h4>Mini Purificadora</h4>
                    <p>Nuestra más reciente innovación, ideal para oficinas y hogares. Compacta y eficiente.</p>
                    <p class="price">$1,500</p>
                    </div>
                <div class="product-card">
                    <img src="purificadoragrande.jpg" alt="Purificadora grande">
                    <h4>Purificadora Grande</h4>
                    <p>Sistema industrial con almacenamiento de 5,000 a 10,000 litros o más. Alto rendimiento para comunidades.</p>
                    <p class="price">$3,000</p>
                    </div>
                <div class="product-card">
                    <img src="Garrafonesreutilizablesecologicos.png" alt="Garrafones reutilizables ecológicos">
                    <h4>Garrafones Ecológicos</h4>
                    <p>Diseñados para transportar agua purificada, reduciendo el impacto ambiental.</p>
                    <p class="price">$700</p>
                    </div>
                <div class="product-card">
                    <img src="BioBottle.avif" alt="BioBottle">
                    <h4>BioBottle</h4>
                    <p>Botella ecológica reutilizable. Pequeñas y medianas. Perfectas para el día a día.</p>
                    <p class="price">$134.44</p>
                    </div>
                    <div class="product-card">
                    <img src="purificadoramediana.jpg" alt="purificadora mediana">
                    <h4>Purificadora mediana</h4>
                    <p>Sistema industrial con almacenamiento de 3,000 a 4,000 litros. Incluye tanque de almacenamiento</p>
                    <p class="price">$2,000</p>
                    </div>
                    <div class="product-card">
                    <img src="purificadorapequeña.avif" alt="purificadora pequeña">
                    <h4>Purificadora pequeña</h4>
                    <p>Sistema industrial con almacenamiento de 1,000 a 3,000 litros. Ideal para venta de garrafones</p>
                    <p class="price">$1,000</p>
                    </div>
            </div>
        </div>
    </section>

     <section id="testimonios" class="testimonials-section">
        <div class="container">
            <h2>Testimonios</h2>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <p class="quote">"Instalamos la purificadora grande y el cambio fue increíble. El sabor del agua es perfecto y el ahorro es notable. ¡Una inversión para el futuro!"</p>
                    <p class="author">— Ana M., Gerente de Comunidad</p>
                </div>
                <div class="testimonial-card">
                    <p class="quote">"La BioBottle es genial para mi familia. Saber que estamos usando agua limpia y reduciendo mi impacto ambiental me da mucha tranquilidad. El servicio fue 10/10."</p>
                    <p class="author">— Luis R., Cliente Satisfecho</p>
                </div>
                <div class="testimonial-card">
                    <p class="quote">"Como pequeña oficina, la Mini purificadora nos salvó. Agua sana sin costos fijos de botellones. Además, el compromiso de la empresa con el mar es inspirador."</p>
                    <p class="author">— Sofía T., Dueña de Negocio</p>
                </div>
            </div>
        </div>
    </section>

    <section id="impacto" class="impact-section">
        <div class="container">
            <h2> Nuestro Impacto Sostenible</h2>
            <div class="impact-grid">
                <div class="impact-item">
                    <h3>-90% Plástico</h3>
                    <p>Reducción en el consumo de botellas plásticas tradicionales por nuestros clientes.</p>
                </div>
                <div class="impact-item">
                    <h3>100% Recolección</h3>
                    <p>El agua utilizada proviene de la lluvia y lagos, reduciendo la dependencia de acueductos.</p>
                </div>
                <div class="impact-item">
                    <h3>+30% Ahorro</h3>
                    <p>Ahorro económico promedio para las familias que utilizan nuestro sistema de purificación.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="campana" class="campana-section">
        <div class="container">
            <h2>Compromiso Azul</h2>
            <h3>Campaña #GotasDeCambio
                 Por Cada Purificadora Vendida, Financiamos la Recolección de 1 Kilo de Plástico Marino.</h3>
            <p>Nuestra visión de agua limpia va más allá de tu ciudad. Tu compra no solo te garantiza agua sostenible y económica, sino que también financia la limpieza activa de nuestros océanos, la fuente de vida del planeta. ¡Sé parte del movimiento!</p>
            <a href="#contacto" class="btn btn-secondary btn-campana">Únete a la Causa</a>
        </div>
    </section>

    <section id="faq" class="faq-section">
        <div class="container">
            <h2>Preguntas Frecuentes</h2>
            <div class="faq-list">
                <div class="faq-item">
                    <h3>¿Qué tan 'sana' es el agua purificada de lluvia?</h3>
                    <p>Nuestros sistemas utilizan múltiples etapas de filtración, incluyendo ósmosis inversa y esterilización UV, eliminando el 99.9% de contaminantes. Cumplimos con los más altos estándares de potabilidad, superando incluso el agua embotellada.</p>
                </div>
                <div class="faq-item">
                    <h3>¿Por qué su sistema es más económico que comprar agua?</h3>
                    <p>Nuestro costo inicial se amortiza rápidamente. Al aprovechar recursos hídricos locales (lluvia/lagos) y eliminar la cadena de distribución, reducimos drásticamente los gastos operativos, traduciéndose en un menor costo por litro para usted.</p>
                </div>
                <div class="faq-item">
                    <h3>¿Se adaptan sus purificadoras al clima de mi ciudad?</h3>
                    <p>Sí. Nuestras máquinas están diseñadas para ser robustas y eficientes en diversos climas. El sistema de recolección de lluvia se optimiza según el índice de precipitación de su región. Contáctenos para un estudio de viabilidad gratuito.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="contact-section">
        <h2>Contáctanos</h2>
        <p>Déjanos tus datos y te contactaremos</p>
        <form class="contact-form">
            <input type="text" placeholder="Escribe tu nombre">
            <input type="email" placeholder="Escribe tu correo">
            <input type="tel" placeholder="Escribe tu teléfono">
            <textarea placeholder="Déjanos un mensaje"></textarea>
            <button type="submit" class="btn btn-primary">Enviar Mensaje</button>
        </form>
    </section>

    <footer class="main-footer">
        <div class="footer-content">
            <div class="contact-info">
                <h4>Contacto</h4>
                <p>info@aguasostenible.com</p>
                <p>(+52) 55 1234 5678</p>
            </div>
            <div class="social-links">
                <h4>Síguenos</h4>
                <p>@AguaSostenibleMX</p>
                <p>@AguaPuraFuturo</p>
                <p>/AguaSostenibleyLimpia</p>
            </div>
            <div class="other-links">
                <h4>Otros enlaces</h4>
                <p>© 2025 Agua Sostenible | Todos los derechos reservados.</p>
                <p>Política de privacidad | Términos de uso</p>
            </div>
        </div>
        <p class="designer-credit"> diseñado por el equipo 2 </p>
    </footer>


</body>
</html>

