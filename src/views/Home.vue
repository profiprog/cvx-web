<template>
  <div class="home">
    <b-img alt="plagát" :src="require('../assets/plagat.jpg')" fluid></b-img>
    <!-- <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/> -->
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';
// import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

@Component({
    components: {
    // HelloWorld
    },
})
export default class Home extends Vue {}
</script>
