<template>
  <section>

    <div class="is-marginless p-1 main-banner" style="background-image: url('/collection.png');">

    </div>

<div class="container is-fullhd p-1">
    <SideContact/>
    <h1 class="title is-h2 has-text-white is-size-1">collections</h1>
       <Collections/>
       <Collections/>
       <Collections/>

 </div>   
  </section>
</template>

<script>
import SideContact from "~/components/SideContact.vue";
import Collections from "~/components/Collections.vue";

export default {
  components: {
    Collections,
    SideContact,    
  }
};
</script>

<style lang="scss" scoped>
.main-banner {
  height: 30vw;
}
</style>
