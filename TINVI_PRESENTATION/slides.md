---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://getwallpapers.com/wallpaper/full/a/0/7/669898.jpg
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# TrashGAM

### Ingeniería En Tecnologías De La Información Y Comunicaciones.

#### Diciembre 2022
#### Jonatan Morales - Uriel Torres

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/Johnmorales26" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# Agenda

<div class="container-column">
<div class="container-cards">
  <div class="card">
  <div class="container">
    <h4><b>01</b></h4>
    <p>Introducción</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>02</b></h4>
    <p>Objetivo</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>03</b></h4>
    <p>Marco Teorico</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>04</b></h4>
    <p>Métodos</p>
  </div>
</div>
</div>
<div class="container-cards">
  <div class="card">
  <div class="container">
    <h4><b>05</b></h4>
    <p>Experimentos</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>06</b></h4>
    <p>Resultados</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>07</b></h4>
    <p>Conclusiones</p>
  </div>
</div>
<div class="card">
  <div class="container">
    <h4><b>08</b></h4>
    <p>Preguntas</p>
  </div>
</div>
</div>
</div>

<center>
<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>
</center>

---

# Introducción

<div class="card_information">
  <div class="container">
  <h2>¿Que es la inteligencia artificial?</h2>
    <p>El  concepto  de  Inteligencia  Artificial  (IA)  fue  acuñado  en  el  año  1956  por  el  informático  John McCarthy y lo definió como ‘La ciencia e ingenio de hacer máquinas inteligentes’, específicamente hablando  de  programas  de  cómputo.</p>
  </div>
  </div>
<center>
<img src="https://img.blogs.es/anexom/wp-content/uploads/2019/06/inteligenciaartificial.jpg" class="m-40 h-40 rounded shadow" />
</center>

---

# Introducción

<div class="card_information">
  <div class="container">
    <p>Motivados a desarrollar  una  aplicación  para  dispositivos  móviles  de  bajos  recursos.  Usando  un clasificador de imágenes el cual nos permitirá categorizar nuestros residuos  de basura y así de este mismo  modo  ayudarnos  a  poder  organizar  mejor  nuestros  desechos  orgánicos  e  inorgánicos  y  así poder ayudar a combatir mejor la contaminación ambiental.</p>
  </div>
  </div>
<center>
<img src="https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2018/11/inteligencia-artificial-huawei.jpg" class="m-40 h-40 rounded shadow" />
</center>

---

# Objetivos

<div class="card_information">
  <div class="container">
  <ul>
  <li>Diseñar  e  implementar un  sistema  inteligente  que  permita la  correcta clasificación  de  los residuos sólidos que  son depositados  en  los  contenedores  de  basura  al  exterior  de  las unidades académicas del Instituto Tecnológico de Gustavo A. Madero.</li>
  </ul>
  </div>
  </div>
<center>
<img src="https://larepublica.pe/resizer/roeLbjwVq9nYr9pMJfWO7OR9ato=/1200x660/top/arc-anglerfish-arc2-prod-gruporepublica.s3.amazonaws.com/public/T7JRQIDJD5EXTPUTV7LXS46GGM.jpg" class="m-40 h-40 rounded shadow" />
</center>

---

# Marco Teorico

<div class="card_information">
  <div class="container">
  <ul>
  <li>Ingeligencia Artificial: Dispositivos  con  inteligencia  artificial  puede  ejecutar  diferentes  procesos,  algo  asícomocomportamiento humano, como regresar respuesta para cada entrada (algo así comoseres  sintientes),  buscando  un  estado  entre  los  seres  sintientes  puede  depender  de  laacción o resolución del problema a través de la lógica formal.</li>
  <li>Machine Learning: Es una rama de la Inteligencia Artificial que se encarga de generar algoritmos que tienen la capacidad de aprender y no tener que programarlos de manera explícita. El desarrollador no  tendrá  que  sentarse  a  programar  por  horas  tomando  en  cuenta  todos  los  escenarios posibles ni todas las excepciones posibles.</li>
  <li>Visión Artificial: La visión artificial (CV: Computer Vision) es un campo que procesa la adquisición, procesar y extraer información de imágenes. La visión artificial es un campo muy diversa, utilizando  técnicas  e  ideas  de  las  más  diversas  disciplinas  científicas.</li>
  </ul>
  </div>
  </div> 

---


<style>
.card_information {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  transition: 0.3s;
  margin: 8px;
}

  .card {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  width: 200px;
  height: 150px;
  transition: 0.3s;
  margin: 8px;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
}

/* Add some padding inside the card container */
.container {
  padding: 2px 16px;
}

.container-cards {
  max-width: 100%;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  flex-wrap: no-wrap;
  align-items: center;
  align-content: space-between;
}

.container-column {
  max-width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  flex-wrap: no-wrap;
  align-items: center;
  align-content: space-between;
}
</style>