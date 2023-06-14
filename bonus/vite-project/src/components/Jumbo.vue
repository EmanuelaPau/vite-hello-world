<template>
    <div class="my_jumbo">
        <div class="jumbo-elements-container">
            <h1>Immagina uno spazio...</h1>
            <p>... dove far parte di un club scolastico, un gruppo di gamer, una community artistica mondiale o dove
                trascorrere tempo assieme a un piccolo gruppo di amici: uno spazio in cui è più facile chiacchierare ogni
                giorno e ritrovarsi più spesso.
            </p>
            <button @click="increment()">
                Click tester {{ counter }}
            </button>
            <!-- <img src="../assets/pexels-pixabay-265216.jpg" alt=""> -->
        </div>
    </div>
</template>

<script>
export default {
    components: {

    },
    data() {
        return {
            counter: 0,
        }
    },
    methods: {
        increment() {
            this.counter++;
        }
    }
}
</script>

<style scoped>
.my_jumbo {
    width: 100%;
    height: 600px;
    text-align: center;
    background-color: aqua;
    padding-top: 20px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;

    background-image: url("../assets/jumbo.png");
    background-repeat: none;
    background-size: cover;
    background-position: bottom;
}

.my_jumbo h1 {
    text-transform: uppercase;
    font-weight: 800;
    font-size: 3rem;
    line-height: 3.5rem;
    margin-bottom: 20px;
}

.my_jumbo p {
    margin-bottom: 20px;
}

.my_jumbo button {
    height: 3rem;
    margin-bottom: 30px;
    padding: .7rem 2rem;
    border-radius: 1.5rem;
    border: none;
}

.jumbo-elements-container {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    max-width: 600px;
    font-size: .93rem;
}
</style>