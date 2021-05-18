<template>
    <div>
      <b-jumbotron bg-variant="info" text-variant="white" border-variant="dark">
          <template #header>ShopGo</template>

          <template #lead>
            Ευκολά και γρήγορα δημιουργησε το δικό σου ηλεκτρονικό κατάστημα
          </template>
    
          <div class="form-group">
            <input type="text" class="form-control" id="search" placeholder="Search for a product">
          </div>

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

  .form-group{
    margin: 0 auto;
    width: 800px;
  }
</style>
