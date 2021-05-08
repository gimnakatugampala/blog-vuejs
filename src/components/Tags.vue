<template>
  <a href="#" class="btn btn-primary m-1" v-for="tag in tags" :key="tag">{{tag}}</a>
</template>

<script>
export default {
    name:'Tags',
    props:{
        tags:Array
    }

}
</script>

<style>

</style>