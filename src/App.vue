<template>
   <div>
    <h1>12</h1> 
    <hr>
    <card-ui :menuTitle="'성공'"/>
    <card-ui />
    <card-ui :menuTitle="'성공'"/>
    <card-ui :menuTitle="'성공'"/>
    <card-ui />
    <card-ui />
    <card-ui />
   </div>
</template>

<script>
  import CardUi from './ui-items/card-ui.vue';
  export default {
    components : {
      CardUi,
    }
  }
</script>

<style>

</style>