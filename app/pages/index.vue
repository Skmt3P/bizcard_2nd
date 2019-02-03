<template>
  <div class="main content-center" >
    <div class="container">
      <section
        id="card" 
        class="flex rounded shadow-lg overflow-scroll bg-image">
        <div 
          id="line1" 
          class="sm:flex md:inline-flex lg:inline-flex xl:inline-flex">
          <div class="flex-box">
            <br><h1 class="overflow-scroll">Sakamoto-san / Skmt3P's BizCard</h1><br>
            <img 
              id="img"
              class="content overflow-hidden"
              src="~/assets/image/icon.png" 
              alt="Sakamoto-san's photo">
            <span class="content text-grey-darker text-base">
              <br>I'm a Frontend Engineer from Japan.<br><br>
            </span>
            <a href="https://scrapbox.io/skmt3p/001.RESUME-Who-is-Skmt3P">
              <button class="content bg-red hover:bg-red-dark text-white font-bold py-1 px-3 rounded">
                <i class="fas fa-history" /> View My RESUME
              </button>
            </a>
            <a href="https://scrapbox.io/skmt3p/002.ABOUT-What-is-OUTPUT">
              <button class="content bg-yellow-dark hover:bg-yellow-darker text-white font-bold py-1 px-3 rounded">
                <i class="fas fa-file" /> View My OUTPUT
              </button>
            </a>
            <br>
            <a href="https://twitter.com/skmt3p">
              <button class="content bg-blue hover:bg-blue-dark text-white font-bold py-1 px-3 rounded">
                <i class="fab fa-twitter" /> Contact by Twitter
              </button>
            </a>
            <a href="https://www.linkedin.com/in/san-sakamoto-91957152">
              <button class="content bg-green hover:bg-green-dark text-white font-bold py-1 px-3 rounded">
                <i class="fab fa-linkedin" /> Contact by LinkedIn
              </button>
            </a>
            <p><br></p>
          </div>
          <div class="flex-box sm:max-w-3/4 md:max-w-1/2 lg:max-w-1/2 xl:max-w-1/2">
            <br><h3><b>Tags</b></h3><br>
            <div class="content">
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Vue.js</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Nuxt</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Nodejs</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#Angular</span>
              <span class="tags inline-block bg-grey-lighter rounded-full px-3 py-1 text-sm font-semibold text-grey-darker">#nestjs</span>
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
            <br><h3><b>Signature</b></h3><br>
            <img 
              id="img"
              class="content overflow-hidden"
              src="~/assets/image/sign.png" 
              alt="Sakamoto-san's signature"
              style="width:75%; height:75%">
          </div>
          <br>
        </div>
      </section>
      <!-- <div class = "w-1/6"/> -->
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      titleTemplate: null,
      title: "Skmt3P's BizCard"
    }
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
  margin-bottom: 1%;
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
