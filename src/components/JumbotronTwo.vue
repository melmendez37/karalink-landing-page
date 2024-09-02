<template>
  <div class="bg-dark">
    <div class="container">
      <div class="d-flex flex-column justify-content-center align-items-start h-100 p-4 bg-indigo">
        <h1 class="font-weight-light bg-grey text-start display-4">Start your journey now <br/> and make every minute count.</h1>
        <button type="button" class="btn btn-outline-light btn-lg mt-2">INSTALL NOW</button>
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'JumbotronComponentTwo'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container{
  height: 500px;
  width: max-vh-screen;
}



.bg-grey{
  color: #d9d9d9;
}
</style>
