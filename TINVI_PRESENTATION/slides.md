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
<img src="https://img.blogs.es/anexom/wp-content/uploads/2019/06/inteligenciaartificial.jpg" class="m-10 h-40 rounded shadow" />
</center>

---

# Introducción

<div class="card_information">
  <div class="container">
    <p>Motivados a desarrollar  una  aplicación  para  dispositivos  móviles  de  bajos  recursos.  Usando  un clasificador de imágenes el cual nos permitirá categorizar nuestros residuos  de basura y así de este mismo  modo  ayudarnos  a  poder  organizar  mejor  nuestros  desechos  orgánicos  e  inorgánicos  y  así poder ayudar a combatir mejor la contaminación ambiental.</p>
  </div>
  </div>
<center>
<img src="https://cdn.computerhoy.com/sites/navi.axelspringer.es/public/media/image/2018/11/inteligencia-artificial-huawei.jpg" class="m-10 h-40 rounded shadow" />
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
<img src="https://larepublica.pe/resizer/roeLbjwVq9nYr9pMJfWO7OR9ato=/1200x660/top/arc-anglerfish-arc2-prod-gruporepublica.s3.amazonaws.com/public/T7JRQIDJD5EXTPUTV7LXS46GGM.jpg" class="img-size m-10 rounded shadow" />
</center>

---

# Marco Teorico

<div class="card_information">
  <div class="container">
  <ul>
  <li>Ingeligencia Artificial: Dispositivos  con  inteligencia artificial puede ejecutar diferentes  procesos,  algo  así comocomportamiento humano, como regresar respuesta para cada entrada (algo así comoseres  sintientes), buscando  un  estado  entre  los  seres sintientes puede  depender de la acción o resolución del problema a través de la lógica formal.</li>
  <li>Machine Learning: Es una rama de la Inteligencia Artificial que se encarga de generar algoritmos que tienen la capacidad de aprender y no tener que programarlos de manera explícita. El desarrollador no  tendrá que sentarse a  programar  por  horas  tomando  en  cuenta  todos los escenarios posibles ni todas las excepciones posibles.</li>
  </ul>
  </div>
  </div> 

---

# Marco Teorico

<div class="card_information">
  <div class="container">
  <ul>
  <li>Visión Artificial: La visión artificial (CV: Computer Vision) es un campo que procesa la adquisición, procesar y extraer información de imágenes. La visión artificial es un campo muy diversa, utilizando  técnicas  e  ideas  de  las  más  diversas  disciplinas  científicas.</li>
  </ul>
  </div>
  </div> 

  <center>
<img src="https://blogthinkbig.com/wp-content/uploads/sites/4/2018/03/eye-2286601_1920.jpg?fit=1920%2C1004" class="img-size m-10 rounded shadow" />
</center>

---

# ¿Por qué Aplicación nativa y no aplicación multiplataforma?
## Aplicaciones Multiplataforma

<table class="table">
 <tr>
    <th>Ventajas</th>
    <th>Desventajas</th>
  </tr>
  <tr>
    <td>El código se crea una sola vez por lo que es más simple de construir y probar.</td>
    <td rowspan=2>Algunas funciones no estarán disponibles cuando no haya conexión a internet</td>
  </tr>
  <tr>
    <td>Los cambios y actualizaciones se mantienen simultáneamente en todas las plataformas.</td>
  </tr>
</table>

---

# ¿Por qué Aplicación nativa y no aplicación multiplataforma?
## Aplicaciones Nativas

<table class="table">
 <tr>
    <th>Ventajas</th>
    <th>Desventajas</th>
  </tr>
  <tr>
    <td>Tienen acceso rápido a la cámara, GPS, calendario, micrófono y otras funciones del dispositivo.</td>
    <td rowspan=2>Necesitan más tiempo para desarrollarse en comparación con las aplicaciones híbridas.</td>
  </tr>
  <tr>
    <td>Optimizada para cada sistema operativo, tiene mayor rendimiento y velocidad.</td>
  </tr>
</table>

---

# Métodos
## Algoritmo Con Python

<center>
<img src="/img/download_image_process.png" class="img-size-diagram_one m-10 rounded shadow" />
</center>

---

# Métodos
## Techeable Machine

<div class="container-column">
<div class="container-cards">

<div class="card-images">
  <div class="container">
    <center>
<img src="/img/trash_organic.png" class="img-size rounded shadow" />
</center>
  </div>
</div>

<div class="card-images">
  <div class="container">
    <center>
<img src="/img/trash_inorganic.png" class="img-size rounded shadow" />
</center>
  </div>
</div>

</div>

</div>

---

# Métodos
## Techeable Machine

<div class="container-column">
<div class="container-cards">

<div class="card-images">
  <div class="container">
    <center>
<img src="/img/trash_plastic.png" class="img-size rounded shadow" />
</center>
  </div>
</div>

<div class="card-images">
  <div class="container">
    <center>
<img src="/img/trash_biodegradable.png" class="img-size rounded shadow" />
</center>
  </div>
</div>

</div>

</div>

---

# Métodos
## Preparación del modelo

<center>
<img src="/img/model_preparation.png" class="img-size_vertical rounded shadow" />
</center>

---

# Métodos
## Exortación del modelo

<center>
<img src="/img/model_export.png" class="img-size_vertical_large rounded shadow" />
</center>

---

# Métodos
## Funcionamiento de la aplicación

<center>
<div class="container-cards">
<img src="/img/example_one.png" class="img-size_vertical rounded shadow" />
<img src="/img/example_two.png" class="img-size_vertical rounded shadow" />
<img src="/img/parameters_configuration.png" class="img-size_vertical rounded shadow" />
</div>
</center>

---

# Resultados

<center>
<div class="container-cards">
<img src="/img/example_result_one.png" class="img-size_vertical rounded shadow" />
<img src="/img/example_result_two.png" class="img-size_vertical rounded shadow" />
<img src="/img/example_result_three.png" class="img-size_vertical rounded shadow" />
<img src="/img/example_result_four.png" class="img-size_vertical rounded shadow" />
</div>
</center>

---

# Conclusiones

<p>En esta tesis se mostro el desarrollo de una aplicación móvil la cual tiene embebida dentro de la  misma  un modelo  de  inteligencia  artificial  el  cual  fue  desarrollado  dentro de la  plataforma de Teachable Machine, dicha aplicación cuenta con la capacidad de poder ordenar la basura dentro de nuestro ITGAM. El funcionamiento del aplicativo ha sido demostrado utilizando diferentes ejemplos de desechos que pudiesen ser originados dentro del Instituto, medimos la eficacia de nuestro aplicativo cuando el score de dicho elemento llega a mas del 60%, una vez obteniendo ese resultado podemos decir que nuestro algoritmo y nuestra IA están funcionando de forma correcta dentro de nuestro dispositivo móvil. </p>

---

# Conclusiones
<p>En un futuro se planea que la aplicación pueda migrar sus interfaces a una pantalla mas grande como bien puede ser la de una Tablet. Además pudimos satisfacer el objetivo principal de nuestro proyecto que es la correcta separación de residuos con el uso de una IA y a la vez lograr que este proyecto este relacionado con los objetivos de  desarrollo sustentable de  la  ONU,  logrando  así  poner  nuestro  grano de  arena  para  llevar  una correcta metodología que ayude al objetivo número 13 de los mismos. Aún así cabe recalcar que la eficacia de la aplicación puede que no sea del 100% puesto que no solo se  ve  involucrada  la  parte  tecnológica  si  no  también  la  humana  y  queda  al  libre  albedrio  de  las personas  el  utilizar  o  no  la  aplicación  siendo  esta  solamente  un  apoyo  y  no  una  obligación, concluyendo el desarrollo de esta de manera satisfactoria.</p>

---

# Gracias

<div class="container-column">
<div class="container-cards">

<div class="card_contact">
  <div class="container">
  <center>
<img src="/img/picture_profile_john.png" class="img-size_profile rounded shadow" />
    <h4><b>Morales Tavera Jonatan Arturo</b></h4>
    <p>johnta2610@hotmail.com</p>
    </center>
  </div>
</div>

<div class="card_contact">
  <div class="container">
  <center>
<img src="/img/picture_profile_uriel.png" class="img-size_profile rounded shadow" />
    <h4><b>Torres Garcia Uriel Abisai</b></h4>
    <p>uriel09890@gmail.com</p>
</center>
  </div>
</div>

</div>
</div>

---


<style>
  @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Mende+Kikakui&display=swap');


* {
  font-family: 'Noto Sans Mende Kikakui', sans-serif;
}

li {
  text-align: justify;
}

img {
  border-radius: 20px;
  border: 1px solid black;
}

p {
  text-align: justify;
}

.img-size_profile {
  width: 200px;
  height: 200px;
}

.img-size {
  width: 400px;
  height: 250px;
}

.img-size_vertical {
  width: 250px;
  height: 380px;
}

.img-size_vertical_large {
  width: 500px;
  height: 380px;
}

.img-size-diagram_one {
  width: 450px;
  height: 320px;
}

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

.card_contact {
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  width: 450px;
  height: 350px;
  transition: 0.3s;
  margin: 8px;
}

  .card-images {
  /* Add shadows to create the "card" effect */
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
  width: 500px;
  height: 300px;
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