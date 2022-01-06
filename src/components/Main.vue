<template>
    <main>
        <Hero/>
        <Customer/>
        <Deployment/>
        <Designed/>
        <Features/>
        <Service/>
        <Development/>
    </main>
</template>

<script>
import Hero from './sections/Hero.vue'
import Customer from './sections/Customer.vue'
import Deployment from './sections/Deployment.vue'
import Designed from './sections/Designed.vue'
import Features from './sections/Features.vue'
import Service from './sections/Service.vue'
import Development from './sections/Development.vue'



export default {
    name : 'Main',
    components : {
        Hero,
        Customer,
        Deployment,
        Designed,
        Features,
        Service,
        Development
    }
}
</script>

<style>

</style>