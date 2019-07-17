<template>
<div>
<!-- Main container -->

<nav class="navbar is-fixed-top is-transparent">
  <div class="container is-fluid">
  <div class="navbar-brand">
 <logo />
    <div class="navbar-burger burger" data-target="navbarExampleTransparentExample">
      <span></span>
      <span></span>
      <span></span>
    </div>
  </div>

  <div id="navbarExampleTransparentExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item" href="">
         
      </a>
      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link has-text-white is-size-5" href="">
          collection
        </a>
        <div class="navbar-dropdown is-boxed">

        <div class="is-flex is-size-6">
          <a class="navbar-item" href="">
            STORAGE
          </a>
          <a class="navbar-item" href="">
            SEATING
          </a>
          <a class="navbar-item" href="">
            TABLES
          </a>          
        </div>

          <hr class="navbar-divider">

        <div class="is-flex">
          <a class="navbar-item" href="">
            Sideboards
          </a>
          <a class="navbar-item" href="">
            Credenzas
          </a>
          <a class="navbar-item" href="">
            Credenzas
          </a>          
        </div>
        <div class="is-flex">
          <a class="navbar-item" href="">
            Sideboards
          </a>
          <a class="navbar-item" href="">
            Credenzas
          </a>
          <a class="navbar-item" href="">
            Credenzas
          </a>          
        </div>
        <div class="is-flex">
          <a class="navbar-item" href="">
            Sideboards
          </a>
          <a class="navbar-item" href="">
            Credenzas
          </a>
          <a class="navbar-item is-active" href="">
            Credenzas
          </a>          
        </div>

        </div>
      </div>
       <a class="navbar-item has-text-white is-size-5" href="">
           showroom 
        </a>
         <a class="navbar-item has-text-white is-size-5" href="">
          newly arrived
         </a>
         <a class="navbar-item has-text-white is-size-5" href="">
            sale
         </a>
    
   </div>
    <div class="navbar-end is-lowercase has-text-right small-nav is-size-6">
    <div class="is-block">
       <a class="is-block has-text-white" href="">
           Favorites
        </a>
       <a class="is-block has-text-white" href="">
           Login
        </a>  
 </div>
   <div class="is-block">
       <a class="is-block has-text-white" href="">
           Subscribe
        </a>
       <a class="is-block has-text-white" href="">
           Designers
        </a>  
      </div>
    <div class="is-block">
             <a class="is-block has-text-white is-size-7" href="">
                <font-awesome-icon :icon="['fas', 'search']"/>
            </a>
            <a class="is-block has-text-white" href="">
                <font-awesome-icon :icon="['fab', 'instagram']"/>
            </a>
    </div>
    </div>
  </div>
 </div>
</nav>

<nuxt />


<footer class="footer has-background-black">
<div class="container is-fluid">
 <logo />

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

export default {
  components: {
    Logo
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
