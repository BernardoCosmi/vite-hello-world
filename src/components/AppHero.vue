<script>
export default{
    name: "AppHero"
}
</script>

<template>

    <div class="jumbotron">
        <hr class="my-4">
        <h2 class="display-4">Questo Jumbotron serve solo a richiamare la tua attenzione</h2>
        <p class="lead">Questo serve solo a farti perdere altro tempo a leggere</p>
        <hr class="my-4">
    </div>
    
</template>

<style scoped>
    .jumbotron{
        padding: 10px;
        text-align: center;
    }
    h2, p, hr{
        margin: 5px;
    }
    h2{
      font-weight: 500;  
      color: lightblue;
    }
</style>
