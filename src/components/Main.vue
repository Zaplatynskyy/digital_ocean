<template>
    <main>
        <Hero/>
        <Customer/>
        <Deployment/>
        <Designed/>

    </main>
</template>

<script>
import Hero from './sections/Hero.vue'
import Customer from './sections/Customer.vue'
import Deployment from './sections/Deployment.vue'
import Designed from './sections/Designed.vue'


export default {
    name : 'Main',
    components : {
        Hero,
        Customer,
        Deployment,
        Designed
    }
}
</script>

<style>

</style>