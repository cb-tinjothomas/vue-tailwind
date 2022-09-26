<template>
   <div class="bg-slate-100 p-4 round shadow-orange-100">
    <h1 class="text-bold text-xl name">Hello to my app</h1>
    <p>{{title}}</p>
    <button>Clcik me</button>
   </div>
</template>

<style scoped>
    .name  {
background: red;
    }
</style>

<script>
    export default {
        name : 'TinjoComp',
       props : ['title']
    }
</script>