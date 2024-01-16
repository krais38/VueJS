<template>
    <section class="c-intro">
      <div class="c-intro__text">
        <h1>Inovace a Kreativita ve Webovém Designu</h1>
        <h2>Přizpůsobené webové stránky s osobním dotekem</h2>
        <p>Krátký odstavec, který zdůrazňuje vaše zkušenosti a schopnost poskytovat unikátní řešení pro každého klienta, s důrazem na profesionální přístup a individuální potřeby.</p>
      </div>
      <figure class="c-intro__image">
        <img src="@/assets/img/img/img__intro.png" alt="test"> 
      </figure>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Intro'
    // Zde můžete přidat jakoukoliv logiku komponenty, pokud je to potřeba
  }
  </script>
  
  <style lang="scss">
  .c-intro {
    // Základní styly pro intro sekci
  
    &__text {
      // Styly pro textovou část
  
      h1, h2 {
        // Styly pro nadpisy
      }
  
      p {
        // Styly pro odstavec
      }
    }
  
    &__image {
      // Styly pro obrázkovou část
    }
  }
  </style>
  