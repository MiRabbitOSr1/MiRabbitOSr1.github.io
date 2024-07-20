---
layout: page
---

<style>
  .flex-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center; /* Centers the flex children horizontally */
  }
  .flex-child {
    flex: 1;
    min-width: 250px; /* Ensures the text doesn't get too narrow */
    margin: 10px;
    display: flex;
    justify-content: center; /* Centers the video within the flex child */
  }
  .flex-child video {
    width: 30%; /* Reduces the video size to 30% of its original size */
    height: auto;
    pointer-events: none; /* Prevents interaction with the video */
  }
  @media (max-width: 768px) {
    .flex-child {
      flex: 100%;
      margin: 10px 0;
    }
    .flex-child video {
      max-width: 90%;
      width: auto; /* Adjusts width to be more responsive on smaller screens */
    }
  }
</style>

<div class="flex-container">
  <div class="flex-child">
    <a href="https://community.rabbit.tech/t/r1-en-espana">
      <video autoplay loop muted>
        <source src="assets/videos/rabbit-idle.mp4" type="video/mp4">
      </video>
    </a>
  </div>
</div>

<br/>

<p>Somos un grupo de apasionados por Rabbit R1, siempre buscando aprender más y colaborar en la evolución de la comunidad. Únete a nuestro <a href="https://t.me/mirabbitosr1_es" target="_blank"><img src="https://img.shields.io/badge/Telegram-¡Únete!-ff4d00" alt="Canal de Telegram"></a> para participar en la conversación. Haz clic en el botón <span style="color: #ff4d00;">`Únete`</span> para ser parte de nuestra comunidad y mantenerte al tanto de todo lo relacionado con Rabbit R1. (¡Este paso es opcional, pero te hará una persona genial! 😁)</p>

<p>Además, te invitamos a explorar nuestro <a href="https://mirabbitosr1.github.io/archivo" target="_blank"><img src="https://img.shields.io/badge/Blog-Archivo-blue" alt="Blog Archivo"></a> donde encontrarás artículos interesantes y más información sobre el Rabbit R1. Este recurso es una excelente manera de profundizar tus conocimientos y mantenerte actualizado sobre este apasionante tema. (¡No te lo pierdas!)</p>

<br/>

<br/>