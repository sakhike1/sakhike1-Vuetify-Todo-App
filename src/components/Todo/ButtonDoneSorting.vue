<template>
    <v-btn @click="$store.commit('toggleSorting')" class="button-done-sorting" color="#9575CD">
        Done Sorting
    </v-btn>
</template>

<script>
export default {

}
</script>

<style lang="sass">
  .button-done-sorting
    position: fixed
    bottom: 20px
    left: 50%
    transform: translateX(-50%)
    
</style>