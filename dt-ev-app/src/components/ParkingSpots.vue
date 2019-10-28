<template>
    <div>
        <div class="container">
            <div class="left-col">
                this is the placeholder for chargers
            </div>
            <div class="right-col">
                <ParkingSpot style="margin-top: auto;"></ParkingSpot>
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
        name      : "ParkingSpots",
        components: {
            ParkingSpot
        }
    }
</script>

<style scoped>
    .container {
        display: flex;
        height: 92vh;
        width: 100vw;
        align-items: flex-end;
        background-color: #007bff;
    }

    .left-col {
        width: 25vw;
    }

    .right-col {
        display: flex;
        height: 100%;
        flex-direction: column;
        width: 75vw;
        justify-content: flex-end;
        align-items: flex-end;
        align-self: flex-end;
        margin-top: auto;
    }
</style>
