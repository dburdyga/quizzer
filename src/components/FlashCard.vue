<template>
  <div class="ui centered card">
    <div class="content">
      <div class="header">
        {{card.term}}
      </div>
      <div class="description">
        {{card.description}}
      </div>

     </div>
   </div>
</template>

<script>
export default {
  props: ['card'],
}

</script>

<style>

</style>
