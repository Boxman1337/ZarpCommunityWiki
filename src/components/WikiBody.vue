<template>
    <div class="WikiBodyContainer">
        <div class="VerticalNavBar"></div>
    </div>
</template>


<script>

    export default {
        name: 'WikiBody',
        components: {}    
    }

</script>



<style scoped>

    .WikiBodyContainer {

        height: 600px;
        width: 80%;

        margin: auto;
        margin-top: 10px;

        border-radius: 10px;

        background-color: rgb(51, 48, 48);
    }

    .VerticalNavBar {

        height: 600px;
        width: 250px;

        border-radius: 10px 0px 0px 10px;

        background-color: rgb(31, 30, 31); 
    }

</style>