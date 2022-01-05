<template>
    <main>
        <Hero/>
        <Customer/>
        <Deployment/>
        <Designed/>
        <Features/>
    </main>
</template>

<script>
import Hero from './sections/Hero.vue'
import Customer from './sections/Customer.vue'
import Deployment from './sections/Deployment.vue'
import Designed from './sections/Designed.vue'
import Features from './sections/Features.vue'

export default {
    name : 'Main',
    components : {
        Hero,
        Customer,
        Deployment,
        Designed,
        Features
    }
}
</script>

<style>

</style>