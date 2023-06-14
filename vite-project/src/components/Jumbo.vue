<template>
    <div class="my_jumbo">
        <div class="jumbo-elements-container">
            <h1>This Is my Jumbotron</h1>
            <!-- <img src="../assets/pexels-pixabay-265216.jpg" alt=""> -->
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.my_jumbo {
    width: 100%;
    height: 400px;
    text-align: center;
    background-color: aqua;
    padding-top: 20px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url("../assets/pexels-pixabay-265216.jpg");
    background-repeat: none;
    background-size: cover;
    background-position: bottom;
}

.jumbo-elements-container {
    display: flex;
    justify-content: center;
    align-items: center;
    max-width: 500px;
}
</style>