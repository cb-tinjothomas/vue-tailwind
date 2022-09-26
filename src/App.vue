<template>
<h1 class="text-bold text-xl ml-4">Hello to my {{increment}}</h1>
<p >how are you</p>
<button @click="increment">Clcik me</button>
<Tinjo title="UX Designer"/>
<Tinjo title="Design Technologist"/>
</template>
<script>
import Tinjo from './components/tinjo.vue';
export default {
    name: "MyComponent",
    data() {
        return {
            siteName: "Learn Vue LiveLessions"
        };
    },
    method: {
        increment: () => { console.log("clicked"); }
    },
    components: { Tinjo }
}
</script>