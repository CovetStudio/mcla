<template>
  <section>
    <div
      class="container is-marginless is-fullhd p-4 main-banner"
      style="background-image: url('/MCLA2498.png');"
    ></div>

    <div class="columns home-columns is-marginless">
      <div class="column p-2" style="background-image: url('/MCLA2478.png');">
        <h2 class="title is-h2 has-text-white is-size-1">
          showroom
          <font-awesome-icon :icon="['fas', 'arrow-right']" />
        </h2>
        <h5 class="subtitle is-h5 has-text-white is-size-6">
          360° virtual tour of
          <br />mcla showroom
        </h5>
      </div>
      <div class="column p-2" style="background-image: url('/newly.png');">
        <h2 class="title is-h2 has-text-white is-size-1">
          newly arrived
          <font-awesome-icon :icon="['fas', 'arrow-right']" />
        </h2>
        <h5 class="subtitle is-h5 has-text-white is-size-6">
          latest collection
          <br />of furnitures and objects
        </h5>
      </div>
    </div>

    <div
      class="container is-marginless is-fullhd p-2 main-break"
      style="background-image: url('/lookbook.png');"
    >
      <h2 class="title is-h2 has-text-white is-size-1">
        <nuxt-link class="has-text-white" to="lookbook">
          lookbook
          <font-awesome-icon :icon="['fas', 'arrow-right']" />
        </nuxt-link>
      </h2>
      <h5 class="subtitle is-h5 has-text-white is-size-6">
        our handpicked collection
        <br />of furnitures and objects
      </h5>
    </div>

    <div class="columns home-columns is-marginless">
      <div class="column p-2" style="background-image: url('/restor.png');">
        <h2 class="title is-h2 has-text-white is-size-1">
          restoration
          <font-awesome-icon :icon="['fas', 'arrow-right']" />
        </h2>
        <h5 class="subtitle is-h5 has-text-white is-size-6">
          360° virtual tour of
          <br />mcla showroom
        </h5>
      </div>
      <div class="column p-2" style="background-image: url('/care.png');">
        <h2 class="title is-h2 has-text-white is-size-1">
          care manual
          <font-awesome-icon :icon="['fas', 'arrow-right']" />
        </h2>
        <h5 class="subtitle is-h5 has-text-white is-size-6">
          latest collection
          <br />of furnitures and objects
        </h5>
      </div>
    </div>
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";

export default {
  layout: "home",
  components: {
    Logo
  }
};
</script>


<style>

.nuxt-link-active {
  opacity: .7;
}

img {
  width: 100%;
  height: auto;
}

body {
  color: #999
}
.title {
  font-weight: 400
}
.main-banner {
  height: 60vw;
}
.main-break {
  height: 43vw;
}

.home-columns .column {
  height: 42vw;
}
.title svg.svg-inline--fa {
  width: 0.23em;
}

.pt-small{
  padding-top: .5rem;
}
.pb-small{
  padding-bottom: .5rem;
}
.py-1 {
  padding-top: 2rem;
  padding-bottom:2rem;
}

.p-1 {
  padding: 2em;
}
.p-2 {
  padding: 4rem;
}
.p-3 {
  padding: 8rem;
}
.p-4 {
  padding: 16rem;
}
.p-5 {
  padding: 32rem;
}
.pb-1 {
  padding-bottom: 1rem;
}
.pb-3 {
  padding-bottom: 3rem;
}
.pb-4 {
  padding-bottom: 8rem;
}
.pb-5 {
  padding-bottom: 16rem;
}
.pb-6 {
  padding-bottom: 32rem;
}
.pr-1 {
  padding-right: 24px;
}

.home-columns .column,
.main-banner,
.inner-banner,
.main-break {
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}</style>
