<script>
export default {
    name: "AppHero"
}
</script>

<template>
    <!-- Jumbotron -->
    <section>
        <div id="jumbotron">
            <img class="fill" src="../assets/landscape_comp_m.jpeg" alt="">
            <h1 class="white">Rubber ducks</h1>
            <p>Rubber ducks can help many developer in many situations &#128526; </p>
        </div>
    </section>
</template>

<style scoped>
#jumbotron {
    width: 100%;
    background-color: black;
    border-radius: 2rem;
    padding: 1rem;
}

#jumbotron img {
    margin: 1rem;
    width: 80%;
}

.fill {
    object-fit: cover;
}
</style>