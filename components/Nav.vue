<template>
    <div>

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
        <nuxt-link class="navbar-link has-text-white is-size-5" to="/collection">
          collection
        </nuxt-link>
        <div class="navbar-dropdown is-boxed">

        <div class="is-flex is-size-6">
          <nuxt-link class="navbar-item" to="/collection/storage">
            STORAGE
          </nuxt-link>
          <nuxt-link class="navbar-item" to="/collection/storage">
            STORAGE
          </nuxt-link>
          <nuxt-link class="navbar-item" to="/collection/storage">
            STORAGE
          </nuxt-link>                  
        </div>

          <hr class="navbar-divider">

        <div class="is-flex">
          <nuxt-link class="navbar-item" to="/collection/storage/sideboards">
            Sideboards
          </nuxt-link>
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
       <nuxt-link class="navbar-item has-text-white is-size-5" to="showroom">
           showroom 
       </nuxt-link>
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




</style>

