<template>
    <div>
        Parking spots graphic
        <div class="container">
            <div class="left-col">

            </div>
            <div class="right-col">
                <ParkingSpot></ParkingSpot>
                <ParkingSpot style="margin-top: 20px;"></ParkingSpot>
                <ParkingSpot style="margin-top: 20px;"></ParkingSpot>
                <ParkingSpot style="margin-top: 20px;"></ParkingSpot>
            </div>
        </div>


    </div>
</template>

<script>
    import ParkingSpot from './ParkingSpot';

    export default {
        name: "ParkingSpots",
        components: {
            ParkingSpot
        }
    }
</script>

<style scoped>
.container {
    display: flex;
    height: 100%;
}

    .right-col {
        display: flex;
        height: 100%;
        flex-direction: column;
    }
</style>
