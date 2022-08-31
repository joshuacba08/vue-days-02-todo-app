<template>
  <div v-if="isMorning">Good Morning</div>
  <div v-text="msg"></div>
  <div class="text" v-html="html"></div>
</template>

<script>
export default {
    name:'TaskContainer',
    data(){
        return {
            isMorning: true,
            msg: 'Mi vieja mula ya no es lo que era',
            html:'<p class="text-red-900">Hola</p>'
        }
    }
}
</script>

<style>

</style>