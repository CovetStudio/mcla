<template>
  <div>
<SideContact/>
<section class="hero">
  <div class="hero-body">
    <div class="container">
        <h1 class="has-text-black">ewf</h1>
        <h2 class="has-text-black">jd</h2>
    </div>
  </div>
</section>

<section class="section is-paddingless">

    <div class="">

        <div class="columns">
            <div class="column is-three-quarters">
                <img width="100%" src="/product-placeholder-2.png">
            </div>
        </div>

    <div class="container py-1">
        <div class="columns">
            <div class="column is-one-fifth">
                image,
            </div>
            <div class="column is-three-fifths">
                <h1 class="title is-h2 has-text-grey is-size-1">lounge chair <span class="has-text-white">3115</span></h1>
                    <div class="columns">
                        <div class="column is-one-quarter">

<ul class="product-info">
<li>designer. 
<span class="has-text-white">unknown</span>
</li><li>
country.
<span class="has-text-white">brazil</span>
</li><li>
size.
<span class="has-text-white">w30 d33 h28</span>
</li><li>
availability.
<span class="has-text-white">ready for purchase</span>
</li> <li>
product no.
<span class="has-text-white">stg-lou-4658
</span>
</li>
</ul>


                        </div>
                         <div class="column is-three-quarters pr-1">
<h4 class="is-size-3 has-text-white pb-1">$15,000 <small class="is-size-6">*price includes restoration</small></h4>
<p class="has-text-white">Leather and metal chair + ottoman, originally designed by Oscar Niemeyer, called the Alta Chair, in 1971. I purchased 10 of these which were prototypes for a re-issue by a French company. They were produced by a German Artisan, in Dortmund. The French company went under and never paid him so I bought them directly from him. They are exceptionally well made with the highest degree of quality, materials and hardware. Only 12 were made for this reissue.</p>
         <p class="has-text-white py-1">
        <font-awesome-icon :icon="['fas', 'file-alt']" />
            <small> tearsheet</small>
        </p>
                        </div>                       
                    </div>
            </div>
        </div>
         
    </div>


        
    
    </div>

  </section>


<div class="container  p-1" style="margin-right: 240px">
    <h1 class="title is-h2 has-text-white is-size-1">exolore more</h1>

<Columns/>
<Columns/>
  </div>

  </div>
</template>
<script>
import SideContact from '~/components/SideContact.vue'
import Columns from "~/components/Columns.vue";

export default {
  components: {
    SideContact,
    Columns
  }
}

</script>

<style lang="scss" scoped>

.product-info li {
    display: block;
    margin-bottom: 10px
}

.product-info li span {
    display: block
}

</style>
