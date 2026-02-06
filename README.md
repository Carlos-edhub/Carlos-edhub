<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=¡Hola!+Soy+Carlos+Cardenas;Programador;Content+Creator;Creador+en+Canva" alt="Título animado" />
</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4FF,50:0066FF,100:0A0B2A&height=200&section=header&text=Transformando+ideas+en+contenido&fontSize=38&fontColor=ffffff&animation=fadeIn&fontAlignY=38" />
</p>

Hola amigos, ¿que tal? Let's coding for a better world together  👋<img width="30" height="30" alt="image" src="https://github.com/user-attachments/assets/680fedf1-0e17-411e-a867-0d61096716a2" />


Bienvenidos a mi mundo 🌏🌌 

Hola mi nombre es Carlos Daniel Cárdenas Beltrán, soy estudiante de último año en Desarrollo de Aplicaciones Multiplataforma (DAM). Aparte del mundo tecnológico soy técnico profesional en Comercio Internacional y Transporte y Logistica. Me apasiona la programación y codificar, llevo inmerso en el mundo tecnológico varios años pero ahora enfocado en la informática. Me gusta crear, innovar y sacarle el máximo provecho al mundo informático y digital en mi día a día. 

<!-- Sección Carrusel -->


### Proyectos Destacados

Estas son algunas de las presentaciones que realizo con el fin de generar contenido educativo en Redes Sociales a través de Canva...
<h2 align="center">Presentaciones educativas</h2>
<div align="center">
  <div style="
    position: relative;
    max-width: 800px;
    margin: 0 auto;
    overflow: hidden;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 212, 255, 0.3);
    border: 2px solid #00D4FF;"
    >
    <div id="contenedor-carrusel" style="display: flex; transtion: transform 0.5s ease;">
      <!-- Las imágenes se añadirán aquí -->
    </div>
    <!-- Flechas -->
  <button onclick="prevSlide()" style="
      position: absolute;
      top:50%;
      left: 10px;
      transform: translateY(-50%);
      background: rgba(10, 11, 42, 0.8);
      border: 2px solid #00D4FF;
      color: white;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      font-size: 24px;
      cursor: pointer;
      z-index: 10;"><</button>

  <button onclick="nextSlide()" style="
      position: absolute;
      top:50%;
      left: 10px;
      transform: translateY(-50%);
      background: rgba(10, 11, 42, 0.8);
      border: 2px solid #00D4FF;
      color: white;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      font-size: 24px;
      cursor: pointer;
      z-index: 10;">></button>

  <div id="indicadores" style="
    position: absolute;
    bottom: 20px;
    left: 0;
    right: 0;
    display: flex;
    justify-content: center;
    gap: 10px;
    "></div>
      
  </div>
  
</div>

<script>
  //Configuramos el carrusel en js
  const images = [
    {
      url: "https://via.placeholder.com/800x450/0A0B2A/00D4FF?text=Presentación+Canva+1",
      title: "Análisis de Datos",
      desc: "Infografía interactiva sobre tendencias"
    },
    {
      url: "https://via.placeholder.com/800x450/0066FF/E0F7FA?text=Presentación+Canva+2",
      title: "Marketing Digital",
      desc: "Estrategias para redes sociales"
    },
    {
      url: "https://via.placeholder.com/800x450/00D4FF/0A0B2A?text=Presentación+Canva+3",
      title: "Educación Online",
      desc: "Metodologías de enseñanza virtual"
    },
    {
      url: "https://via.placeholder.com/800x450/8A2BE2/FFFFFF?text=Presentación+Canva+4",
      title: "Diseño Gráfico",
      desc: "Principios básicos del diseño"
    } 
    ];
  let currentSlide = 0;
  const container = document.getElementById('contenedor-carrusel');
  const indicador = document.getElementById('indicadores');

  //Creamos los slides  
  images.forEach(img, index) => {
    const slide = document.createElement('div');
    slide.style.minWidth ="100%";
    slide.style.textAlign = "center";
    slide.style.padding ="20px";

    slide.innerHTML = `
      <img src="${img.url}"
           alt="${img.title}"
           style="width: 100%; max-width: 700px; border-radius: 10px; margin-bottom: 15px;">
      <h3 style="color: #00D4FF; margin: 10px 0;">${img.title}</h3>
      <p style="color: #E0F7FA; max-width: 600px; margin: 0 auto;">${img.desc}</p>
      `;

    container.appendChild(slide);

    // Creamos indicadores 
    const indicator = document.createElement('div');
    indicator.style.width = "12px";
    indicator.style.height = "12px";
    indicator.style.borderRadius = "50%";
    indicator.style.backgroundColor = index === 0 ? "#00D4FF" : "rgba(255,255,255,0.5)";
    indicator.style.cursor = "pointer";
    indicator.onClick = () => goToSlide(index);
    indicators.appendChild(indicator);
  });

// Funciones del carrusel
function updateCarousel() {
  container.style.transform = `translateX(-${currentSlide * 100}%)`;
  
  // Actualizar indicadores
  document.querySelectorAll('#indicators div').forEach((ind, index) => {
    ind.style.backgroundColor = index === currentSlide ? "#00D4FF" : "rgba(255,255,255,0.5)";
  });
}

function nextSlide() {
  currentSlide = (currentSlide + 1) % images.length;
  updateCarousel();
}

function prevSlide() {
  currentSlide = (currentSlide - 1 + images.length) % images.length;
  updateCarousel();
}

function goToSlide(index) {
  currentSlide = index;
  updateCarousel();
}

// Auto-play cada 5 segundos
setInterval(nextSlide, 5000);

// Inicializar
updateCarousel();

</script>

## Mi primer página web
Tng_shops
<p>https://carlos-edhub.github.io/PaginaWeb/</p>



### ¿Como contactarme?
<ul>
  <li>📲(+34) 663 07 93 12</li>
  <li>📩 carloscardenas.pv@gmail.com</li>
  <li>LinkedIn: www.linkedin.com/in/carlosdanielcardenas</li>
</ul>



