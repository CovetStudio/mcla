<template>
  <section>


    <div class="is-marginless p-1 inner-banner" style="background-image: url('/collection.png');">

    </div>

<div class="container  p-1" style="margin-right: 240px">
     <SideContact/>
    <h1 class="title is-h2 has-text-white is-size-1">storage</h1>
       <Columns/>
       <Columns/>
       <Columns/>

 </div>   
  </section>
</template>

<script>
import Logo from "~/components/Logo.vue";
import Columns from "~/components/Columns.vue";
import SideContact from "~/components/SideContact.vue";

export default {
  components: {
    Logo,
    Columns,
    SideContact
  }
};
</script>

<style lang="scss" scoped>
.inner-banner {
  height: 30vw;
}
.side-contact-info {
  top: 400px;
}
</style>
