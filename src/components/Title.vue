<template>
  <div class="quadrato">
    <h1>{{msg}}</h1>
    <div id="hero"></div>
  </div>
</template>

<script>
    export default {
    name: 'Title',
    props: {
        msg: String
    }
    }
</script>

<style lang="scss">
    #hero{
        background-image: url("https://fantascienzaitalia.com/wp-content/uploads/2018/10/Saluto-spock.jpg");
        width: 50rem;
        height: 37.5rem;
        margin: auto;
        background-size: cover;
    } 
        

</style>