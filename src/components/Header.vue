<template>
    <div class="container">
        <img id="logo" src="../assets/images/ZarpCustomLogo.png">
    </div> 
</template>







<script>

    export default {
        name: 'Header',
        components: {}
    }

</script>



<style scoped>

    .container {
        height: 100px;
        width: auto;

        border: 2px solid #d4d4d4;
        border-radius: 25px;

        background-color: #447321;
    }

    #logo {
        height: 85px;

        padding-top: 10px;
        padding-left: 25px;
    }


</style>