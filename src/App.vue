<template>
    <div class="AppContainer">
        <Header/>
        <WikiBody/>
    </div>
</template>






<script>

    import Header from './components/Header.vue'
    import WikiBody from './components/WikiBody.vue'

    export default {
        name: 'App',
        components: { 
            Header,
            WikiBody
        }
    }

</script>




<style scoped>
    
</style>