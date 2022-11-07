<template>
    <div class="NavBarContainer"> 
        <h1 class="NavBarServer"> SSRP </h1>
        <h1 class="NavBarServer"> TTT </h1>
        <h1 class="NavBarServer"> Prop Hunt </h1>
        <h1 class="NavBarServer"> Bhop </h1>
        <h1 class="NavBarServer"> Surf </h1>
        <h1 class="NavBarServer"> Deathrun </h1>

        <h1 class="NavBarComms"> Forums </h1>
        <h1 class="NavBarComms"> Discord </h1>
    </div>

    <div class="NavBarServerLine"></div>
    <div class="NavBarCommsLine"></div>
</template>





<script>

    export default {
        name: 'NavBar',
        components: {}
    }

</script>






<style scoped>

    .NavBarContainer {
        height: 70px;
        width: 1000px;

        position: absolute;

        display: flex;
        flex-wrap: wrap;
        justify-content: space-evenly;

        font-size: small;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;

        margin-top: 15px;
        margin-left: 375px;
    }

    .NavBarContainer .NavBarServer {
        background: linear-gradient(to bottom right, #6CD051, #c9ebd8);
        background-clip: text;
        color: transparent;
    }

    .NavBarContainer .NavBarComms {
        background: linear-gradient(to bottom right, #ce8e2f, #c9ebd8);
        background-clip: text;
        color: transparent;
    }

    .NavBarServerLine {
        height: 5px;
        width: 675px;

        position: absolute;

        margin-top: 70px;
        margin-left: 405px;

        background: linear-gradient(to bottom right, #6CD051, #c9ebd8);
    }

    .NavBarCommsLine {
        height: 5px;
        width: 250px;

        position: absolute;

        margin-top: 70px;
        margin-left: 1100px;

        background: linear-gradient(to bottom right, #ce8e2f, #c9ebd8);
    }

</style>