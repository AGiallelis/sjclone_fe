<template>
    <div>
    <b-jumbotron bg-variant="info" text-variant="white" border-variant="dark">
        <template #header>BootstrapVue</template>

        <template #lead>
        This is a simple hero unit, a simple jumbotron-style component for calling extra attention to
        featured content or information.
        </template>

        <hr class="my-4">

        <p>
        It uses utility classes for typography and spacing to space content out within the larger
        container.
        </p>
    </b-jumbotron>
    </div>
</template>

<script>
export default {
  name: 'Carousel',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
