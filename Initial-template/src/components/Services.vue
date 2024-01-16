<template>
    <section class="c-services">
      <h2>Naše Služby</h2>
      <div class="c-services__list">
        <!-- Zde budou jednotlivé služby s popisem a ikonami -->
        <!-- Například: -->
        <div class="c-services__item">
          <img src="@/assets/img/img/img__services--web.png" alt="Ikonka Služby">
          <h3>Webový Vývoj</h3>
          <p>Poskytujeme kompletní vývoj webových stránek od konceptu po nasazení. Naše řešení jsou přizpůsobená, rychlá a optimalizovaná pro všechna zařízení.</p>
        </div>
        <div class="c-services__item">
          <img src="@/assets/img/img/img__services--design.png" alt="Ikonka Služby">
          <h3>Grafický design</h3>
          <p>Vytváříme vizuálně poutavé a uživatelsky přívětivé designy, které zvyšují značkovou identitu a zapojení uživatelů.</p>
        </div>
        <div class="c-services__item">
          <img src="@/assets/img/img/img__services--seo.png" alt="Ikonka Služby">
          <h3>SEO Optimalizace</h3>
          <p>Zlepšujeme viditelnost vašeho webu na vyhledávačích pomocí nejnovějších technik SEO a obsahové strategie.</p>
        </div>
        <div class="c-services__item">
          <img src="@/assets/img/img/img__services--cms.png" alt="Ikonka Služby">
          <h3>Správa Obsahu (CMS)</h3>
          <p>Nabízíme řešení pro správu obsahu, které vám umožní snadno spravovat a aktualizovat váš web bez potřeby technických znalostí.</p>
        </div>
        <div class="c-services__item">
          <img src="@/assets/img/img/img__services--marketing.png" alt="Ikonka Služby">
          <h3>Digitální Marketing</h3>
          <p>Pomáháme rozšířit dosah vaší značky pomocí cílených digitálních marketingových kampaní a strategií sociálních médií.</p>
        </div>
        <!-- Opakovat pro každou službu -->
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'Services'
    // Zde můžete přidat jakoukoliv logiku komponenty, pokud je to potřeba
  }
  </script>
  
  <style lang="scss">
  .c-services {
    // Základní styly pro sekci "Služby"
  
    &__list {
      // Styly pro seznam služeb
  
      &__item {
        // Styly pro jednotlivé položky
      }
    }
  }
  </style>
  