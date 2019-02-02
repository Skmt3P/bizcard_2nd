<template>
  <div class="content-center">
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
    <div class="container w-full max-h-screen">
      <section
        id="card" 
        class="flex rounded overflow-hidden shadow-lg">
        <div 
          id="line1" 
          class="sm:flex md:inline-flex lg:inline-flex xl:inline-flex">
          <div class="flex-box">
            <img 
              id="img"
              class="content"
              src="https://tailwindcss.com/img/card-top.jpg" 
              alt="Sunset in the mountains">
          </div>
          <div class="flex-box">
            <div class="content font-bold text-xl mb-2">The Coldest Sunset</div>
            <p class="content text-grey-darker text-base">
              Lorem ipsum dolor sit amet, <br>consectetur adipisicing elit. <br>Voluptatibus quia, nulla! Maiores et perferendis eaque, <br>exercitationem praesentium nihil.
            </p>
            <span class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2">#photography</span>
            <span class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker mr-2">#travel</span>
            <span class="inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#winter</span>
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
#card {
  margin: 10vh;
  height: 90vh;
}

.container {
  min-height: 100%;
  min-width: 100%;
  display: center;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: auto;
}

.flex-box {
  margin: 0.5em;
}

.content {
  margin: auto;
  position: center;
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
