---
layout: default
title: Linda Catalina Correa Lozano
permalink: /
---

<section class="hero" aria-labelledby="nombre">
  <div class="hero-copy">
    <p class="eyebrow">Ingeniería Ambiental · Portafolio académico</p>
    <h1 id="nombre">Linda Catalina<br><span>Correa Lozano</span></h1>
    <p class="hero-lead">Datos para entender el agua, el clima y el territorio.</p>
    <p class="hero-description">Soy estudiante de la Universidad Nacional de Colombia, sede Medellín. Combino mi formación ambiental con programación y análisis geográfico para convertir información compleja en resultados claros y verificables.</p>
    <div class="hero-actions">
      <a class="button primary" href="#proyectos">Explorar proyectos <span aria-hidden="true">↗</span></a>
      <a class="button secondary" href="assets/docs/CV_Linda_Catalina_Correa_Lozano.pdf" download>Descargar hoja de vida <span aria-hidden="true">↓</span></a>
    </div>
    <p class="availability"><span class="status-dot" aria-hidden="true"></span>Habilitada para práctica académica · Medellín, Colombia</p>
  </div>
  <aside class="approach" aria-labelledby="forma-trabajo">
    <p class="eyebrow">Mi forma de trabajar</p>
    <h2 id="forma-trabajo">Del dato<br>al resultado.</h2>
    <ol class="workflow">
      <li><span class="step-number" aria-hidden="true">01</span><div><strong>Integrar y validar</strong><p>Revisar las fuentes y la calidad de la información.</p></div></li>
      <li><span class="step-number" aria-hidden="true">02</span><div><strong>Modelar y comparar</strong><p>Explorar patrones, escenarios y sus límites.</p></div></li>
      <li><span class="step-number" aria-hidden="true">03</span><div><strong>Comunicar y documentar</strong><p>Explicar los resultados y cómo se obtuvieron.</p></div></li>
    </ol>
  </aside>
</section>

<section id="proyectos" class="section-block" aria-labelledby="titulo-proyectos">
  <div class="section-heading">
    <div><p class="eyebrow">01 / Trabajo realizado</p><h2 id="titulo-proyectos">Cuatro proyectos, una base común.</h2></div>
    <p>Aplicar datos y conocimiento ambiental a preguntas concretas.</p>
  </div>
  <p class="collaboration">Proyectos académicos desarrollados junto a <a href="https://github.com/CamiloBedoyaC">Juan Camilo Bedoya Carmona</a>, en un equipo de dos personas.</p>

  <div class="project-grid">
    <article class="project-card" aria-labelledby="titulo-hidrologia">
      <div class="project-topline"><span>Hidrología</span><span>2026-I</span></div>
      <h3 id="titulo-hidrologia">Simulación hidrológica<br>de una cuenca</h3>
      <p class="project-summary">Un modelo en Python para estudiar cómo responde una cuenca a la lluvia y comparar los caudales simulados con los observados.</p>
      <p class="project-evidence"><strong>12.784</strong> registros diarios de CAMELS-US</p>
      <a class="figure-link dark-figure" href="assets/img/hidrologia.png" aria-label="Ampliar figura: caudal observado y simulado en la cuenca Sopchoppy">
        <img src="assets/img/hidrologia.png" width="3300" height="1760" alt="Hidrograma con precipitación y comparación entre caudal observado y simulado en Sopchoppy." loading="lazy" decoding="async">
        <span class="image-caption">Caudales observados y simulados <span aria-hidden="true">↗</span></span>
      </a>
      <details class="project-details"><summary>Método y resultados</summary><div class="details-body">
        <p>Integramos datos diarios, límites de cuenca y estaciones. Calibramos y validamos un modelo de lluvia y escorrentía, y generamos mapas interactivos y reportes automáticos.</p>
        <p>La mejor combinación alcanzó un <strong>NSE de 0,603 en validación</strong>, una medida del ajuste de los caudales simulados. El análisis también muestra las dificultades del modelo para representar las crecidas.</p>
        <p class="technical-note"><strong>Herramientas:</strong> Python, SciPy, Leaflet y Plotly.</p>
        <a class="inline-link" href="/assets/docs/reporte-hidrologico.html">Abrir el informe interactivo <span aria-hidden="true">↗</span></a>
      </div></details>
      <a class="project-link" href="https://github.com/CamiloBedoyaC/modelo-hidrologico">Ver código, metodología y resultados <span aria-hidden="true">↗</span></a>
    </article>

    <article class="project-card" aria-labelledby="titulo-precipitacion">
      <div class="project-topline"><span>Calidad de datos</span><span>2025-II</span></div>
      <h3 id="titulo-precipitacion">Análisis de precipitación<br>con SIATA y NOAA</h3>
      <p class="project-summary">Procesamiento de observaciones de lluvia de Santa Elena, Antioquia, para estudiar las gotas y su relación con las condiciones atmosféricas.</p>
      <p class="project-evidence"><strong>167,3 millones</strong> de partículas válidas analizadas</p>
      <a class="figure-link dark-figure" href="assets/img/precipitacion.png" aria-label="Ampliar figura: tamaño y velocidad de caída de las gotas">
        <img src="assets/img/precipitacion.png" width="1800" height="1400" alt="Distribución conjunta del diámetro y la velocidad de caída de las gotas medidas por SIATA." loading="lazy" decoding="async">
        <span class="image-caption">Tamaño y velocidad de las gotas <span aria-hidden="true">↗</span></span>
      </a>
      <details class="project-details"><summary>Método y resultados</summary><div class="details-body">
        <p>Procesamos <strong>5,28 GB de datos por bloques</strong> para evitar cargar todo el histórico en memoria. Aplicamos controles de calidad e integramos variables atmosféricas de NOAA.</p>
        <p>Generamos 14 figuras, tablas de resultados y pruebas automatizadas. Las relaciones con las variables atmosféricas fueron débiles y se presentan como asociaciones exploratorias.</p>
        <p class="technical-note"><strong>Herramientas:</strong> Python, pandas, NumPy y Matplotlib.</p>
      </div></details>
      <a class="project-link" href="https://github.com/LindaCatalina/siata-disdrometer-rainfall-microphysics">Ver código, metodología y resultados <span aria-hidden="true">↗</span></a>
    </article>

    <article class="project-card" aria-labelledby="titulo-eolica">
      <div class="project-topline"><span>Clima y energía</span><span>2025-II</span></div>
      <h3 id="titulo-eolica">Riesgo climático para<br>la generación eólica</h3>
      <p class="project-summary">Evaluación de posibles cambios en el potencial de una planta eólica virtual en La Guajira, considerando distintos escenarios climáticos.</p>
      <p class="project-evidence"><strong>12 modelos</strong> climáticos · 3 escenarios futuros</p>
      <a class="figure-link wind-figure" href="assets/img/eolica.png" aria-label="Ampliar figura: cambios del factor de planta en los escenarios climáticos">
        <img src="assets/img/eolica.png" width="2773" height="1374" alt="Cambios proyectados del factor de planta y dispersión entre modelos en tres escenarios climáticos." loading="lazy" decoding="async">
        <span class="image-caption">Escenarios y rangos de incertidumbre <span aria-hidden="true">↗</span></span>
      </a>
      <details class="project-details"><summary>Método y resultados</summary><div class="details-body">
        <p>Integramos ERA5-Land y proyecciones de CMIP6, corregimos diferencias sistemáticas y estimamos cambios en el factor de planta.</p>
        <p>El conjunto de modelos no muestra una disminución común a los tres escenarios. La dispersión entre modelos y la sensibilidad al método son importantes para interpretar el riesgo.</p>
        <p class="technical-note"><strong>Herramientas:</strong> Python, pandas, xarray y Matplotlib. Es un caso académico inspirado en Jemeiwaa Ka'I.</p>
      </div></details>
      <a class="project-link" href="https://github.com/LindaCatalina/jemeiwaa-wind-energy-climate-risk">Ver código, metodología y resultados <span aria-hidden="true">↗</span></a>
    </article>

    <article class="project-card" aria-labelledby="titulo-mjo">
      <div class="project-topline"><span>Climatología</span><span>2025-II</span></div>
      <h3 id="titulo-mjo">Estabilidad atmosférica<br>durante la MJO</h3>
      <p class="project-summary">Estudio de cómo cambia la estabilidad de la atmósfera en Palau y Chuuk durante las fases de la oscilación de Madden-Julian.</p>
      <p class="project-evidence"><strong>33.096</strong> registros diarios · 2 estaciones</p>
      <a class="figure-link dark-figure" href="assets/img/mjo.png" aria-label="Ampliar figura: anomalías de estabilidad de Palau y Chuuk durante la fase cuatro de la MJO">
        <img src="assets/img/mjo.png" width="2392" height="877" alt="Mapa esquemático de la fase cuatro de la MJO y anomalías calculadas para Palau y Chuuk." loading="lazy" decoding="async">
        <span class="image-caption">Fase 4: esquema y resultados por estación <span aria-hidden="true">↗</span></span>
      </a>
      <details class="project-details"><summary>Método y resultados</summary><div class="details-body">
        <p>Integramos radiosondeos de NOAA de 1980 a 2025 y el índice de la MJO. Calculamos promedios históricos y anomalías, y generamos tablas y visualizaciones interactivas.</p>
        <p>Encontramos anomalías negativas en las fases 1–2 y positivas en las fases 4–6, con diferencias entre estaciones. El resultado describe una asociación, no una prueba de causalidad ni un pronóstico.</p>
        <p class="technical-note"><strong>Herramientas:</strong> Python, análisis de series, CSV/Parquet y visualización interactiva.</p>
        <a class="inline-link" href="https://camilobedoyac.github.io/mjo-atmospheric-stability/hist-unificado-site/hist_unificado.html">Explorar la visualización interactiva <span aria-hidden="true">↗</span></a>
      </div></details>
      <a class="project-link" href="https://github.com/CamiloBedoyaC/mjo-atmospheric-stability">Ver código, metodología y resultados <span aria-hidden="true">↗</span></a>
    </article>
  </div>
</section>

<section id="competencias" class="section-block" aria-labelledby="titulo-competencias">
  <div class="section-heading"><div><p class="eyebrow">02 / Capacidades</p><h2 id="titulo-competencias">Herramientas con un propósito.</h2></div></div>
  <div class="skills-grid">
    <div class="skill-group"><h3>Datos y modelos</h3><p>Integración, control de calidad, análisis estadístico y simulación.</p><p class="tool-list">Python · R · pandas · NumPy · xarray · SciPy</p></div>
    <div class="skill-group"><h3>Mapas y visualización</h3><p>Análisis espacial y presentación de resultados para facilitar su interpretación.</p><p class="tool-list">QGIS · Google Earth Engine · Cartopy · Leaflet · Matplotlib · Plotly</p></div>
    <div class="skill-group"><h3>Desarrollo y documentación</h3><p>Organización del código, automatización y reportes que pueden revisarse.</p><p class="tool-list">Git · GitHub · Jupyter · VS Code · LaTeX · Excel</p></div>
  </div>
  <p class="working-note"><strong>En equipo:</strong> comparto conocimientos y escucho otros puntos de vista. Ante una dificultad, investigo, pruebo alternativas y busco apoyo cuando es necesario.</p>
</section>

<section id="formacion" class="section-block formation" aria-labelledby="titulo-formacion">
  <div class="formation-copy">
    <p class="eyebrow">03 / Aprendizaje</p>
    <h2 id="titulo-formacion">Formación que acompaña<br>la práctica.</h2>
    <p>Complemento la ingeniería ambiental con análisis de datos, climatología y herramientas geográficas.</p>
    <div class="credential-row"><span>Promedio: <strong>4,3/5,0</strong></span><span>Inglés: <strong>C1 · EF SET</strong></span></div>
  </div>
  <div class="formation-details">
    <h3>Asignaturas de posgrado</h3>
    <p>Analítica descriptiva y visualización de datos · Analítica predictiva · Producto de datos · Climatología.</p>
    <h3>Curso realizado</h3>
    <p>Geoanalítica: transforma datos en decisiones — Esri, 2026.</p>
    <details class="learning-details"><summary>Formación y certificaciones en progreso</summary><div class="details-body">
      <ul>
        <li><strong>Python:</strong> CS50P — Harvard.</li>
        <li><strong>SQL y bases de datos:</strong> CS50 SQL — Harvard.</li>
        <li><strong>Ciencia de datos y aprendizaje automático:</strong> Kaggle y Google ML Crash Course.</li>
        <li><strong>Ingeniería de datos:</strong> DataTalks.Club e IBM Data Engineering.</li>
        <li><strong>Análisis geoespacial:</strong> GeoPython y cursos MOOC de Esri.</li>
        <li><strong>Teledetección:</strong> NASA ARSET.</li>
        <li><strong>Nube y despliegue:</strong> AWS.</li>
      </ul>
    </div></details>
  </div>
</section>

<section id="contacto" class="contact-section" aria-labelledby="titulo-contacto">
  <div><p class="eyebrow">04 / Conversemos</p><h2 id="titulo-contacto">Hablemos de nuevas<br>oportunidades.</h2><p>Busco una práctica en análisis de datos o gestión ambiental, con especial interés en energía, recursos hídricos e infraestructura.</p></div>
  <div class="contact-links"><a class="contact-email" href="mailto:licorrea@unal.edu.co">licorrea@unal.edu.co <span aria-hidden="true">↗</span></a><a class="contact-email" href="mailto:linda8.catalina@gmail.com">linda8.catalina@gmail.com <span aria-hidden="true">↗</span></a><a href="https://github.com/LindaCatalina">Explorar mi GitHub <span aria-hidden="true">↗</span></a></div>
</section>
