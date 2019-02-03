<template>
  <div class="main content-center" >
    <!-- <logo/>
      <h1 class="title">
        bizcard_2nd
      </h1>
      <h2 class="subtitle">
        bizcard of sakamoto-san / skmt3p
      </h2>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="button--green">Documentation</a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="button--grey">GitHub</a> -->
    <div class="container">
      <section
        id="card" 
        class="flex rounded shadow-lg overflow-scroll bg-image">
        <div 
          id="line1" 
          class="sm:flex md:inline-flex lg:inline-flex xl:inline-flex">
          <div class="flex-box">
            <img 
              id="img"
              class="content overflow-hidden"
              src="~/assets/image/icon.png" 
              alt="Sakamoto-san's photo">
          </div>
          <div class="flex-box sm:max-w-3/4 md:max-w-1/2 lg:max-w-1/2 xl:max-w-1/2">
            <h1 class="overflow-scroll">Sakamoto-san / Skmt3P's BizCard</h1>
            <img 
              id="img"
              class="content overflow-hidden"
              src="~/assets/image/sign.png" 
              alt="Sakamoto-san's photo"
              style="width:80%; height:80%">
            <p class="content text-grey-darker text-base">
              <br>I'm a Frontend Engineer from Japan.<br>
              My output is <a href="https://scrapbox.io/skmt3p/">HERE</a>!!<br>
              Contact me by these Social Media!!<br><br>
            </p>
            <div class="contenrt">
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Vue.js</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#nuxt</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Angular</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#extjs</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#php</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Python</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Docker</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Firebase</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#CircleCI</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#git</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#SQL</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#MongoDB</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#RESTfulAPI</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#sketch</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#SAP ERP</span>
            </div>
            <p><br></p>
          </div>
        </div>
      </section>
      <!-- <div class = "w-1/6"/> -->
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
html {
  background-image: url('../assets/image/bg-wood.png');
  /* background-color: red; */
}

section {
  /* background-image: ('~/assets/image/bg-wood.png'); */
  background-color: white;
}

.main {
  height: 100%;
  box-sizing: border-box;
  margin: 0;
  padding: 5vh;
}

.container {
  min-height: 90%;
  min-width: 90%;
  display: center;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: auto;
}

#card {
  margin: 0;
  height: auto;
  max-height: 90vh;
  width: auto;
  max-width: 90vw;
  display: flex;
  justify-content: space-between;
}

#line1 {
  width: 95%;
}

.flex-box {
  margin: auto;
  min-width: 50%;
}

.content {
  margin: auto;
}

.tags {
  margin: 1%;
  justify-content: center;
  align-items: center;
  text-align: center;
}

/* .title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
} */

/* .subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
} */

/* .links {
  padding-top: 15px;
} */
</style>
