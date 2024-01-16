<template>
    <section class="c-about-us">
      <div class="c-about-us__content">
        <h2>O nás</h2>
        <p>Vítejte v našem digitálním světě! Jsme Patrik a Martin, dva třicátníci s vášní pro webový design a vývoj. Naše cesty se spojily díky společnému snu - vytvářet webové stránky, které nejen vypadají skvěle, ale jsou i funkční a uživatelsky přívětivé.</p>
        <p>Patrik, kodér s očima upřenýma na nejnovější technologie, je mozkomyslným inženýrem našich projektů. Jeho kód je čistý jako švýcarské hodinky a funkční jako dobře promazaný stroj.</p>
        <p>Martin, náš kreativní génius, je mužem za nádhernými designy, které oživují každý projekt. Jeho smysl pro estetiku a detail přináší do každé práce jedinečný umělecký dotek.</p>
        <p>Společně tvoříme tým, který překlenuje propast mezi technologií a kreativitou. Pro nás není jen o vytváření webových stránek - je to o vytváření zážitků, které zůstanou v paměti. Připojte se k nám na této cestě a převeďme vaše digitální sny v realitu!</p>
      </div>
      <figure class="c-about-us__images">
        <img src="@/assets/img/img/img__about.png" alt=""> 
      </figure>
    </section>
  </template>
  
  <script>
  export default {
    name: 'AboutUs'
    // Zde můžete přidat jakoukoliv logiku komponenty, pokud je to potřeba
  }
  </script>
  
  <style lang="scss">
  .c-about-us {
    // Základní styly pro sekci "O nás"
  
    &__content {
      // Styly pro textovou část
  
      h2 {
        // Styly pro nadpis
      }
  
      p {
        // Styly pro odstavce
      }
    }
  
    &__images {
      // Styly pro obrázkovou část
    }
  }
  </style>
  