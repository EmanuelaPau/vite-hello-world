<template>
    <div class="my_info-card">
        <div class="info-card-wrapper">
            <img class="card-img" src="../assets/card-img.svg" alt="">
            <div class="card-text">
                <h1>Crea uno spazio su invito in cui sentirti partecipe
                </h1>
                <p>
                    I server Discord sono organizzati in canali tematici in cui puoi collaborare, condividere o
                    semplicemente parlare della tua giornata senza intasare una chat di gruppo.
                </p>

            </div>
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
.my_info-card {
    /* background-color: aqua; */
    width: 100%;
    height: 500px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.info-card-wrapper {
    max-width: 1000px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.card-img {
    /* height: 350px; */
    width: 500px;
}

.card-text {
    margin-left: 50px;
    width: 350px;
}
</style>