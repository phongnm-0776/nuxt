<template>
  <div id="app">
    <v-responsive
    max-height=800 >
      <v-carousel
            
            class="ok"
            hide-controls
            interval="2000"
            v-model="test"
            hide-delimiters
        >
          <v-carousel-item >
            <h1>Propel user engagement, retention, and conversion with chat and messaging</h1>
          </v-carousel-item>
                <v-carousel-item>
                  <h1>White-label chat solution for your app</h1>
          </v-carousel-item>
          <v-carousel-item>
            <h1>White-label chat solution for your app</h1>
          </v-carousel-item>

      </v-carousel>
      <p data-aos="fade-down"
            data-aos-delay="100">A complete chat platform for your mobile apps and 
  websites: Chat and Messaging SDKs and API, and a fully managed chat infrastructure.</p>
    </v-responsive>
</div>
</template>

<script>
export default {
  data() {
    return {
      test: 1,
      clipped: false,
      drawer: false,
      fixed: false,
      items: [
        {
          icon: 'apps',
          title: 'Welcome',
          to: '/'
        },
        {
          icon: 'bubble_chart',
          title: 'Inspire',
          to: '/inspire'
        }
      ],
      miniVariant: false,
      right: true,
      rightDrawer: false,
      title: 'Vuetify.js'
    }
  },

}
</script>
<style>
.v-carousel {
  box-shadow: none;
}

h1 {
  position: absolute;
   bottom: 20px;
   right: 0;
}
</style>
