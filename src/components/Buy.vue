<template>
  <div
    id="buy"
    class="ss-buy"
  >
    <div class="container">
      <div class="row align-items-center justify-content-between py-5 py-md-10">
        <div class="col-12 col-lg-4 text-center">
          <div class="ss-buy-box">
            <img
              class="ss-buy-image"
              :src="image1"
            >
            <h3 class="ss-buy-title">
              {{ $t('option1title') }}
            </h3>
            <ul class="ss-buy-description text-left pl-5 pr-5">
              <li>{{ $t('option1item1') }}</li>
              <li>{{ $t('option1item2') }}</li>
              <li>{{ $t('option1item3') }}</li>
              <li>{{ $t('option1item4') }}</li>
            </ul>
            <p class="ss-buy-price">
              {{ $t('option1price') }}
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-4 text-center">
          <div class="ss-buy-box">
            <img
              class="ss-buy-image"
              :src="image2"
            >
            <h3 class="ss-buy-title">
              {{ $t('option2title') }}
            </h3>
            <ul class="ss-buy-description text-left pl-5 pr-5">
              <li>{{ $t('option2item1') }}</li>
              <li>{{ $t('option2item2') }}</li>
              <li>{{ $t('option2item3') }}</li>
              <li>{{ $t('option2item4') }}</li>
            </ul>
            <p class="ss-buy-price">
              {{ $t('option2price') }}
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-4 text-center">
          <div class="ss-buy-box">
            <img
              class="ss-buy-image"
              :src="image3"
            >
            <h3 class="ss-buy-title">
              {{ $t('option3title') }}
            </h3>
            <ul class="ss-buy-description text-left pl-5 pr-5">
              <li>{{ $t('option3item1') }}</li>
              <li>{{ $t('option3item2') }}</li>
              <li>{{ $t('option3item3') }}</li>
              <li>{{ $t('option3item4') }}</li>
            </ul>
            <p class="ss-buy-price">
              {{ $t('option3price') }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<i18n>
{
  "en": {
    "option1title": "Saver",
    "option1item1": "Access basic financial courses",
    "option1item2": "Automatic Savings Tool",
    "option1item3": "Set your Financial Goals",
    "option1item4": "Start saving from $200 pesos",
    "option1price": "Free",
    "option2title": "Smart Saver",
    "option2item1": "Access all financial courses",
    "option2item2": "Automatic Investment Tools",
    "option2item3": "Start Investing from $ 200 pesos",
    "option2item4": "Access to Investments in Portfolios designed by Experts",
    "option2price": "$25 pesos / month or $ 250 pesos a year",
    "option3title": "Investor",
    "option3item1": "All Smart Saver features",
    "option3item2": "Investments above $ 30 thousand pesos",
    "option3item3": "Permanent consultations with our experts",
    "option3item4": "Tailor-made investment strategies for you",
    "option3price": "1% of the Average Balance of your Investment"
  },
  "es": {
    "option1title": "Saver",
    "option1item1": "Accede a los cursos básicos de educación financiera",
    "option1item2": "Herramientas de ahorro automático",
    "option1item3": "Herramientas para metas de ahorro",
    "option1item4": "Empieza a ahorrar desde $200 pesos",
    "option1price": "Free",
    "option2item1": "Accede a todos los cursos de educación financiera",
    "option2item2": "Herramientas de inversión automática",
    "option2item3": "Empieza a invertir desde $200 pesos",
    "option2item4": "Acceso a inversiones en portafolios de inversión diseñados por expertos",
    "option2price": "$25 pesos al Mes o $250 pesos al año",
    "option3title": "Investor",
    "option3item1": "Todas las funciones de Smart Saver",
    "option3item2": "Inversiones desde $30 mil pesos",
    "option3item3": "Consultas permanentes con nuestros expertos",
    "option3item4": "Diseño de tus estrategias de inversión a la medida",
    "option3price": "1% del Saldo Promedio de tu Inversión"
  }
}
</i18n>

<script>
export default {
  name: 'Buy',
  components: {},
  props: {},
  data: function () {
    return {
      image1: require('../assets/sapling.png'),
      image2: require('../assets/leaf.png'),
      image3: require('../assets/tree.png'),
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="sass">
.ss-buy
  background-color: $ss-bg-color
  padding-top: 2rem
.ss-buy-box
  background-color: $ss-bg-color-white
  box-shadow: 0 4px 10px 0 rgba(0, 0, 0, 0.1)
  padding: 0 0 2rem 0
  margin: 1rem
.ss-buy-image
  width: 70%
.ss-buy-title
  font-size: 1.75rem
  margin: 1rem
  font-weight: 700
  font-family: $ss-font-family-special
.ss-buy-description
  font-size: 1rem
  min-height: 13rem
.ss-buy-price
  font-family: $ss-font-family-special
  font-weight: 600
  font-size: 1rem
  margin: 1rem
  min-height: 5rem
</style>
