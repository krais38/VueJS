<template>
    <section class="c-contact">
      <h2>Kontaktujte nás</h2>
      <div class="c-contact__info">
        <p>Email: info@vasedomena.com</p>
        <p>Telefon: +420 123 456 789</p>
        <p>Adresa: Vaše Adresa, Město</p>
        <!-- Sociální média odkazy -->
      </div>
      <form class="c-contact__form">
        <input type="text" name="name" placeholder="Vaše jméno">
        <input type="email" name="email" placeholder="Váš email">
        <input type="text" name="subject" placeholder="Předmět">
        <textarea name="message" placeholder="Vaše zpráva"></textarea>
        <button type="submit">Odeslat</button>
      </form>
      <!-- Zde může být umístění mapy, pokud je potřeba -->
    </section>
  </template>
  
  <script>
  export default {
    name: 'Contact'
    // Zde můžete přidat jakoukoliv logiku komponenty, pokud je to potřeba
  }
  </script>
  
  <style lang="scss">
  .c-contact {
    // Základní styly pro sekci "Kontakty"
  
    &__info {
      // Styly pro kontaktní informace
    }
  
    &__form {
      // Styly pro kontaktní formulář
  
      input, textarea, button {
        // Styly pro formulářové prvky
      }
    }
  }
  </style>
  