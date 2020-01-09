<template>
  <div class="container">
    <section class="container__section">
      <h1 class="p-title p-title--light">Endereço</h1>
      <address>
        <p class="p-text p-text--light">Rua Rosa Barbieri Paioti</p>
        <p class="p-text p-text--light">São José dos Campos - SP</p>
      </address>
    </section>
    <section class="container__section">
      <h1 class="p-title p-title--light">Nos conheça melhor</h1>
      <div class="social-media">
        <InstagramLogo class="social-media__logo" />
        <span class="p-text p-text--light">@praontem</span>
      </div>
      <div class="social-media">
        <FacebookLogo class="social-media__logo" />
        <span class="p-text p-text--light">facebook.com/praontem</span>
      </div>
    </section>
  </div>
</template>

<style lang="sass" scoped>
@import '@/assets/sass/elements/p-text.sass'
@import '@/assets/sass/elements/p-title.sass'
@import './footer.sass'
</style>

<script>
import InstagramLogo from '@/assets/svg/i-instagram.svg'
import FacebookLogo from '@/assets/svg/i-facebook.svg'

export default {
  name: 'Footer',
  components: {
    InstagramLogo,
    FacebookLogo,
  }
}
</script>