<template>
    <section class="c-portfolio">
      <h2>Naše Portfolio</h2>
      <div class="c-portfolio__gallery">
        <!-- Zde budou jednotlivé projekty s popisem a snímky -->
        <!-- Například: -->
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--1.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--2.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--3.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--4.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--5.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <div class="c-portfolio__item">
          <img src="@/assets/img/img/img__portfolio--6.jpg" alt="Název Projektu"> 
          <h3>Moderní Webová Prezentace</h3>
          <p>Vytvoření moderního, responzivního webu pro startup ve finančním sektoru. Zaměření na uživatelskou přívětivost a vizuální čistotu, s integrací pokročilých web aplikací</p>
        <p>HTML5, CSS3, Vue.js, Node.js</p>
        </div>
        <!-- Opakovat pro každý projekt -->
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Portfolio'
    // Zde můžete přidat jakoukoliv logiku komponenty, pokud je to potřeba
  }
  </script>
  
  <style lang="scss">
  .c-portfolio {
    // Základní styly pro sekci "Portfolio"
  
    &__gallery {
      // Styly pro galerii projektů
  
      &__item {
        // Styly pro jednotlivé položky
      }
    }
  }
  </style>
  