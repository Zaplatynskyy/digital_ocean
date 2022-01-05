<template>
    <main>
        <Hero/>
        <Customer/>
    </main>
</template>

<script>
import Hero from './sections/Hero.vue'
import Customer from './sections/Customer.vue'


export default {
    name : 'Main',
    components : {
        Hero,
        Customer
    }
}
</script>

<style>

</style>