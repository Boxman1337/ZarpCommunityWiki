<template>
    <div class="HeaderContainer">
        <img id="HeaderLogo" src="../assets/images/ZarpCustomLogo.png">
        <NavBar/>
    </div> 
</template>







<script>

    import NavBar from "./NavBar.vue"

    export default {
        name: 'Header',
        components: {
            NavBar
        }
    }

</script>



<style scoped>

    .HeaderContainer {
        height: 100px;
        width: auto;
    }

    #HeaderLogo {
        height: 85px;

        position: absolute;

        padding-top: 10px;
        padding-left: 25px;
    }


</style>