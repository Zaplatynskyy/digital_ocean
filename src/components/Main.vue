<template>
    <main>
        <Hero/>
        <Customer/>
        <Deployment/>

    </main>
</template>

<script>
import Hero from './sections/Hero.vue'
import Customer from './sections/Customer.vue'
import Deployment from './sections/Deployment.vue'

export default {
    name : 'Main',
    components : {
        Hero,
        Customer,
        Deployment
    }
}
</script>

<style>

</style>