<template>
    <div id="app">
        <Nav />
        <Nuxt />
        <Footer />
    </div>
</template>

<script>
    import Nav from '@/components/Nav.vue'
    import Footer from '@/components/Footer.vue'
    export default {
        components: {
            Nav,
            Footer
        },
    }
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;500;600&family=Rubik:wght@300;400;500;600;700;800;900&display=swap');
body {
    background-color: #FFFFFF;
    font-family: 'Rubik', sans-serif;
}
a {
    transition: 0.25s ease-in;
}
</style>