<template>
    <div class="HeaderContainer">
        <img id="HeaderLogo" src="../assets/images/ZarpCustomLogo.png">
    </div> 
</template>







<script>

    export default {
        name: 'Header',
        components: {
            
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
        padding-left: 9.55%;
    }


</style>