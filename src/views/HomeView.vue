<template>
    <Navbar />
    <div>
        <h1>Hello world!!</h1>
    </div>
</template>
<style>
html{
    background-color: #06142e;
}
</style>
<script lang="ts">
import Navbar from '@/components/Navbar.vue';
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'HomeView',
    components: {
        Navbar,
    }
});
</script>