<template>
  <section class="container">
    <div class="container__section">
      <h1 class="p-title p-title--jumbo">
        É pra ontem?
      </h1>
      <h3 class="p-title p-title--giant p-title--center p-title--thin">
        Onde vendedores desesperados encontram compradores inteligentes
      </h3>
      <button>Ver produtos</button>
    </div>
  </section>
</template>

<style scoped lang="sass">
@import '@/assets/sass/elements/p-title.sass'
@import '@/assets/sass/variables.sass'

.container
  flex: 1
  padding-top: 12vh
  padding-right: $space-small
  padding-left: $space-small
  padding-bottom: $space-small
  display: flex
  flex-direction: column
  justify-content: center
  align-items: center
  // position: relative
  // &:before
  //   content: ''
  //   position: absolute
  //   top: 0
  //   left: 0
  //   width: 100%
  //   height: 100%
  //   background: url('../assets/images/home.jpg')
  //   background-position: center
  //   filter: blur(2px)
  //   z-index: $z-base
  &__section
    display: flex
    flex-direction: column
    justify-content: space-between
    align-items: center
    padding: 0 15%
    height: 240px
  
</style>
