<template>
  <section>

    <div class="is-marginless p-1 main-banner" style="background-image: url('/collection.png');">

    </div>

<div class="container  p-1" style="margin-right: 240px">
    <SideContact/>
    <h1 class="title is-h2 has-text-white is-size-1">lounge chairs</h1>
       <Columns/>
       <Columns/>
       <Columns/>

 </div>   
  </section>
</template>

<script>
import SideContact from "~/components/SideContact.vue";
import Columns from "~/components/Columns.vue";

export default {
  components: {
    Columns,
    SideContact,    
  }
};
</script>

<style lang="scss" scoped>
.main-banner {
  height: 30vw;
}
</style>
