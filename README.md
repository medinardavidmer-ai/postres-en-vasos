
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>🍰 Postres en Vaso - Tu Negocio Desde Casa</title>
<style>
/* RESET Y ESTILOS BASE */
*{margin:0;padding:0;box-sizing:border-box;}
body{font-family:'Arial',sans-serif;line-height:1.6;color:#333;background:#fdf6f0;}
a{text-decoration:none;}
h1,h2,h3,h4,h5,h6{margin-bottom:15px;}

/* ALERTA CUPOS */
.cupos-alert{background: linear-gradient(135deg,#e74c3c,#c0392b);color:white;padding:20px;text-align:center;font-weight:bold;font-size:1.2em;border-radius:10px;margin-bottom:20px;}
.cupos-alert span{font-size:1.5em;}

/* HERO */
.hero{background:linear-gradient(135deg,#ff6b6b,#4ecdc4);color:white;text-align:center;padding:50px 20px;border-radius:15px;margin-bottom:30px;}
.hero h1{font-size:2.5em;margin-bottom:20px;}
.hero p{font-size:1.3em;opacity:0.9;margin-bottom:30px;}
.hero-result{background: rgba(255,255,255,0.15); padding:20px; border-radius:15px; display:inline-block;}
.hero-result h2{margin-bottom:10px;}

/* TESTIMONIOS */
.testimonials{background:#f8f9fa;padding:40px 20px;border-radius:15px;margin-bottom:30px;}
.testimonial{background:white;padding:25px;margin:20px 0;border-radius:15px;box-shadow:0 5px 15px rgba(0,0,0,0.1);border-left:5px solid #4ecdc4;transition:transform 0.3s ease;}
.testimonial:hover{transform:translateY(-5px);}
.testimonial-text{font-style:italic;margin-bottom:15px;color:#555;}
.testimonial-author{font-weight:bold;color:#2c3e50;}
.testimonial-result{background:linear-gradient(135deg,#a8e6cf,#88d8c0);color:#2d3436;padding:10px 15px;border-radius:20px;display:inline-block;margin-top:10px;font-weight:bold;}

/* BENEFICIOS */
.benefits{background:linear-gradient(135deg,#74b9ff,#0984e3);color:white;padding:40px 20px;border-radius:15px;margin-bottom:30px;}
.benefits h2{text-align:center;font-size:2.2em;margin-bottom:30px;text-shadow:0 2px 4px rgba(0,0,0,0.2);}
.benefits-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
.benefit-card{background:rgba(255,255,255,0.15);padding:25px;border-radius:15px;text-align:center;backdrop-filter:blur(10px);transition:transform 0.3s ease;}
.benefit-card:hover{transform:scale(1.05);}
.benefit-icon{font-size:3em;margin-bottom:15px;display:block;}

/* PRICING */
.pricing{background:#2c3e50;color:white;padding:50px 20px;text-align:center;border-radius:15px;margin-bottom:30px;}
.price-container{background:linear-gradient(135deg,#e17055,#f39c12);padding:40px;border-radius:20px;margin:30px auto;max-width:500px;box-shadow:0 15px 30px rgba(0,0,0,0.3);}
.original-price{font-size:1.8em;text-decoration:line-through;opacity:0.7;margin-bottom:10px;}
.current-price{font-size:4em;font-weight:bold;color:#fff;text-shadow:0 2px 4px rgba(0,0,0,0.3);margin-bottom:20px;}
.discount-badge{background:#d63031;color:white;padding:10px 20px;border-radius:25px;display:inline-block;font-weight:bold;margin-bottom:20px;animation:pulse 2s infinite;}
@keyframes pulse{0%,100%{transform:scale(1);}50%{transform:scale(1.05);}}
.cta-button{background:linear-gradient(135deg,#00b894,#00a085);color:white;padding:20px 40px;font-size:1.4em;font-weight:bold;border:none;border-radius:50px;cursor:pointer;display:inline-block;transition:all 0.3s ease;box-shadow:0 5px 15px rgba(0,184,148,0.4);position:relative;overflow:hidden;}
.cta-button:hover{transform:translateY(-3px);box-shadow:0 10px 25px rgba(0,184,148,0.6);}
.cta-text{position:relative;z-index:2;}

/* BONOS */
.bonus-section{background:linear-gradient(135deg,#6c5ce7,#a29bfe);color:white;padding:40px 20px;border-radius:15px;margin-bottom:30px;}
.bonus-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px;}
.bonus-card{background:rgba(255,255,255,0.15);padding:20px;border-radius:15px;text-align:center;backdrop-filter:blur(10px);}
.bonus-value{background:#d63031;color:white;padding:5px 15px;border-radius:20px;font-weight:bold;display:inline-block;margin-top:10px;}

/* INSTRUCCIONES */
.instructions{background:#ecf0f1;padding:30px 20px;border-radius:15px;margin-bottom:30px;}
.instruction-box{background:white;padding:20px;border-radius:10px;margin:20px 0;border-left:4px solid #3498db;box-shadow:0 2px 10px rgba(0,0,0,0.1);}
.instruction-title{font-weight:bold;color:#2c3e50;margin-bottom:10px;font-size:1.1em;}

/* GARANTÍA */
.guarantee{background:#f8f9fa;padding:30px 20px;text-align:center;border-top:5px solid #00b894;border-radius:15px;}
.guarantee-badge{background:linear-gradient(135deg,#fdcb6e,#e17055);color:white;padding:15px 30px;border-radius:50px;display:inline-block;margin-bottom:20px;font-weight:bold;font-size:1.2em;}

/* RESPONSIVE */
@media(max-width:768px){.hero h1{font-size:2em;}.hero p{font-size:1.1em;}.current-price{font-size:3em;}.benefits-grid{grid-template-columns:1fr;}.bonus-grid{grid-template-columns:1fr;}.cta-button{padding:15px 30px;font-size:1.2em;}}
</style>
</head>
<body>

<!-- ALERTA CUPOS -->
<div class="cupos-alert">
    🔥 ¡ÚLTIMOS <span>3</span> CUPOS DISPONIBLES! 🔥<br>¡Esta oferta termina pronto!
</div>

<!-- HERO -->
<div class="hero">
    <h1>🍰 POSTRES EN VASO</h1>
    <p>Convierte tu Pasión por la Repostería en un Negocio Rentable</p>
    <div class="hero-result">
        <h2>💰 Mis Alumnas Ganan +$1000 USD/mes</h2>
        <p>Desde la comodidad de su casa, sin experiencia previa</p>
    </div>
</div>

<!-- TESTIMONIOS -->
<div class="testimonials">
    <h2 style="text-align:center; color:#2c3e50; margin-bottom:30px;">🌟 Lo Que Han Logrado Nuestras +600 Alumnas</h2>
    <div class="testimonial">
        <p class="testimonial-text">"Hace unos meses, nunca habría imaginado que podría convertir mi amor por hornear en un negocio real. He logrado hacer más de 1000 dólares hasta el momento, ¡no me lo puedo creer!"</p>
        <p class="testimonial-author">- Linda, Ecuador</p>
        <span class="testimonial-result">💰 +$1,000 USD ganados</span>
    </div>
    <div class="testimonial">
        <p class="testimonial-text">"En mi primera semana ya había logrado hacer 200 dólares y este mes ya casi llego a los 1000 dólares. ¡Si estás buscando un curso completo que te prepare para triunfar, no busques más!"</p>
        <p class="testimonial-author">- María González, Emprendedora</p>
        <span class="testimonial-result">💰 $200 primera semana → $1,000/mes</span>
    </div>
    <div class="testimonial">
        <p class="testimonial-text">"¡Increíble curso! Gracias a las lecciones detalladas y prácticas, ahora tengo la confianza y el conocimiento para emprender mi propio negocio de postres en vaso."</p>
        <p class="testimonial-author">- Laura Pérez, Medellín</p>
        <span class="testimonial-result">🏆 Negocio Exitoso</span>
    </div>
</div>

<!-- BENEFICIOS -->
<div class="benefits">
    <h2>🎯 ¿Qué Vas a Lograr en Solo 15 Días?</h2>
    <div class="benefits-grid">
        <div class="benefit-card"><span class="benefit-icon">🏠</span><h3>Negocio desde Casa</h3><p>Comienza desde la comodidad de tu hogar sin necesidad de local</p></div>
        <div class="benefit-card"><span class="benefit-icon">🎂</span><h3>+20 Técnicas</h3><p>Domina más de 20 técnicas profesionales de postres en vaso</p></div>
        <div class="benefit-card"><span class="benefit-icon">📱</span><h3>Marketing Digital</h3><p>Aprende a vender como experta en redes sociales</p></div>
        <div class="benefit-card"><span class="benefit-icon">💰</span><h3>Calcula Costos</h3><p>Sistema para calcular precios y maximizar ganancias</p></div>
        <div class="benefit-card"><span class="benefit-icon">⏰</span><h3>Libertad de Tiempo</h3><p>Maneja tu propio horario y disfruta con tu familia</p></div>
        <div class="benefit-card"><span class="benefit-icon">🚀</span><h3>Independencia</h3><p>No trabajes para otros, sé tu propia jefa</p></div>
    </div>
</div>

<!-- PRECIO -->
<div class="pricing">
    <h2 style="margin-bottom:30px;">🔥 OFERTA LIMITADA - 50% DESCUENTO</h2>
    <div class="price-container">
        <div class="discount-badge">🎉 50% DE DESCUENTO</div>
        <div class="original-price">Precio Normal: $99.99</div>
        <div class="current-price">$49.97</div>
        <a href="https://go.hotmart.com/E102000051R?ap=07fc" class="cta-button" target="_blank"><span class="cta-text">🍰 ¡QUIERO MI NEGOCIO AHORA! 🍰</span></a>
    </div>
</div>

<!-- BONOS -->
<div class="bonus-section">
    <h2 style="text-align:center;margin-bottom:30px;">🎁 BONOS INCLUIDOS (Valor +$60 USD)</h2>
    <div class="bonus-grid">
        <div class="bonus-card"><h3>📊 Calculadora de Costos</h3><p>Tabla para obtener costos de manera fácil y rápida</p><div class="bonus-value">VALOR $19.99</div></div>
        <div class="bonus-card"><h3>📱 Marketing en Redes</h3><p>Cómo triplicar ventas en redes sociales</p><div class="bonus-value">VALOR $9.99</div></div>
        <div class="bonus-card"><h3>🍪 Recetas de Galletas</h3><p>Galletas con chispas de chocolate</p><div class="bonus-value">VALOR $9.99</div></div>
        <div class="bonus-card"><h3>🧁 24 Tipos de Rellenos</h3><p>Sabores más vendidos del mercado</p><div class="bonus-value">VALOR $9.99</div></div>
        <div class="bonus-card"><h3>🍦 Curso de Helados</h3><p>Aprende a hacer helados fácil y rápido</p><div class="bonus-value">VALOR $9.99</div></div>
        <div class="bonus-card"><h3>🎨 Diseño Gráfico</h3><p>Crea diseños profesionales gratis</p><div class="bonus-value">VALOR $9.99</div></div>
    </div>
</div>

<!-- INSTRUCCIONES -->
<div class="instructions">
    <h2 style="text-align:center; color:#2c3e50;margin-bottom:30px;">📱 Instrucciones Importantes</h2>
    <div class="instruction-box"><div class="instruction-title">✅ Al Realizar tu Compra:</div><p><strong>IMPORTANTE:</strong> Asegúrate de colocar tu correo electrónico correctamente para recibir el acceso al curso.</p></div>
    <div class="instruction-box"><div class="instruction-title">📱 Acceso Móvil:</div><p>Puedes descargar la aplicación de Hotmart para ver tu curso desde tu teléfono:</p>
    <a href="https://play.google.com/store/apps/details?id=com.hotmart.sparkle" target="_blank">📱 Google Play</a> | 
    <a href="https://apps.apple.com/app/hotmart-sparkle/id1239551240" target="_blank">🍎 App Store</a></div>
    <div class="instruction-box"><div class="instruction-title">🎯 Lo Que Incluye el Curso:</div>
        <ul>
            <li>✅ +40 clases en video paso a paso</li>
            <li>✅ +25 técnicas de postres</li>
            <li>✅ Apoyo personalizado en vivo</li>
            <li>✅ Grupos de apoyo (Facebook y WhatsApp)</li>
            <li>✅ Certificación doble</li>
            <li>✅ Clases semanales por Zoom</li>
            <li>✅ Plantillas de precios</li>
        </ul>
    </div>
</div>

<!-- GARANTÍA -->
<div class="guarantee">
    <div class="guarantee-badge">🛡️ GARANTÍA DE 7 DÍAS</div>
    <h3>Compra Sin Riesgos</h3>
    <p>Si en 7 días el curso no cumple tus expectativas, te devolvemos el <strong>100% de tu dinero</strong>.</p>
</div>

</body>
</html>
