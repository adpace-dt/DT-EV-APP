<template>
    <div class="parking-spot">
<!--        <img class="car" src="../assets/car.png" alt="">-->

    </div>
</template>

<script>
    export default {
        name: "ParkingSpot"
    }
</script>

<style lang="scss" scoped>
    @import '../assets/css/index.scss';

    .parking-spot {
        border: 3px solid #0067b8;
        height: 125px;
        width: 60vw;
        min-width: 200px;
        max-width: 300px;
        background-image: url("../assets/car.png");
        background-repeat: no-repeat;
        background-position: center;
        background-size: 95% auto;

        & .car {
            max-height: 120px;
            width: 95%;
        }

    }
</style>
