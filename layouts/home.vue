<template>
<div>
<!-- Main container -->
<Nav />

<nuxt />


<footer class="footer has-background-black">
<div class="container is-fluid">
 <Logo />

 <div class="columns">
  <div class="column is-two-thirds">
 <div class="content is-large ">

 <p class="has-text-grey is-size-1">
   offers a selection of upholstered and refinished furnitures, providing long-lasting pieces with characters since 2010.
 </p>
 </div>
</div>
</div>

 <div class="columns">
  <div class="column is-half">
 <div class="content is-medium">

 <p class="has-text-grey-light">
5333 cahuenga blvd. north hollywood, ca 91601<br/>
+1.818.509.3050<br/>
hello@midcenturyla.com<br/>
instagram.com/midcenturyla<br/>
</p>
 </div>
</div>


  <div class="column is-half">
 <div class="content">
<img src="map.png">
 </div>
</div>


</div>
</div>
</footer>

    
  </div>
</template>
<script>
import Logo from '~/components/Logo.vue'
import Nav from '~/components/Nav.vue'

export default {
  components: {
    Logo,
    Nav
  }
}

</script>
<style lang="scss">

@import '~assets/main.scss';
.navbar-link::after {
    border: 2px solid transparent !important;
    border-radius: 2px !important;
    border-right: 0!important;
    border-top: 0 !important;
    border-color: #fff !important;
    height: .4em !important;
    width: .4em !important;
}
.navbar-link:not(.is-arrowless) {
    padding-right: 1.8em;
}
.small-nav {padding-top:18px}
.small-nav a{padding-left: 12px;font-size: .85rem !important}
.navbar {min-height: 60px;}
.navbar.is-fixed-top {top: 30px}
.VueToNuxtLogo {width: 220px}
.navbar-item img {max-height:220px !important}

* {
  font-family: aktiv-grotesk, sans-serif;
  font-weight: 400;
  font-style: normal;
}

h2.is-h2 {
  font-weight: 400;
}

</style>
