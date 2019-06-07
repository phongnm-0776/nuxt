<template>
  <div>
    <v-layout
    justify-center
    align-center
    row wrap
  >
    <v-flex  class="abc">
      <v-layout row wrap>
        <v-flex xs12 lg4 class="flex-slide">
          <slide-text data-aos="fade-down"
          data-aos-delay="300"></slide-text>
        
        </v-flex>
    
      <v-flex d-flex xs12 lg6>
        <v-flex
        xs3 lg5
        >
          <v-img
          class="mobile"
          data-aos="fade-down"
          data-aos-delay="100"
          src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-gojek@2x.png?key=4fd22b5d4d8999bccb9fac9999a3b6278d683435'
          v-if="show">
          </v-img>
          <v-img
          class="mobile"
          data-aos="fade-right"
          data-aos-delay="300"
          src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-carousell@2x.png?key=9c7fcb390274a52c75da4c74e72700617200d22f'
          v-if="show">
          </v-img>
        </v-flex>
        <v-flex
        xs3 lg5
        >
          <v-img
          class="mobile"
          data-aos="fade-down"
          data-aos-delay="300"
          src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-traveloka@2x.png?key=ed8f3a062bb66e7c009ae6deb882fffcc42677d3'
          v-if="show">
          </v-img>

          <v-img
          class="mobile"
          data-aos="fade-up"
          data-aos-delay="500"
          src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-reddit@2x.png?key=ed8f3a062bb66e7c009ae6deb882fffcc42677d3'
          v-if="show">
          </v-img>
        </v-flex>
        <v-flex
         lg10
        >
          <v-img
          data-aos="fade-up"
          data-aos-delay="500"
          src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-ssg@2x.png?key=46ccaedfea37447fefaf2f0915da8ff8626b8b7a'
         >
          </v-img>
          <v-flex  lg12 d-flex>
            <v-flex xs6 lg8 class="asd">
              <v-img
              class="mobile"
              data-aos="fade-up"
              data-aos-delay="700"
              src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-virgin@2x.png?key=cb00a0804be60ecc78a2cd03e15d0964b3a1acde'
              v-if="show">
              </v-img>
            </v-flex>
            <v-flex xs6 lg8 class="asd">
              <v-img
              class="mobile"
              data-aos="fade-up"
              data-aos-delay="900"
              src='https://dxstmhyqfqr1o.cloudfront.net/sbcom/img-main-live@2x.png?key=cb00a0804be60ecc78a2cd03e15d0964b3a1acde'
              v-if="show">
              </v-img>
            </v-flex>
          </v-flex>
        </v-flex>
      </v-flex>
      
    </v-layout>
    </v-flex>
      
  </v-layout>

  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'
import SlideText from '~/components/SlideText.vue'
export default {
  components: {
    Logo,
    VuetifyLogo,
    SlideText
  },
  mounted () {
    this.show = true
  },
  data () {
    return {
      show: false
    }
  }
}
</script>
<style>
@media (max-width: 990px) {
      .asd {
     min-width: 200px;
   }
   .mobile {
     min-width: 200px;
   }

}
@media (min-width: 1000px) {
   .asd {
     min-width: 200px;
   }
   .mobile {
     min-width: 200px;
   }
}


</style>
