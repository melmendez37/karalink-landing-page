<template>
  <div class="bg-dark">
    <div class="container-fluid">
      <div class="row p-4">
        <div class="col-md-6 p-4">
          <div class="card bg-dark width text-light text-start mb-4">
            <img src="https://images.pexels.com/photos/7674/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=800" class="carimg-top" alt="...">
            <div class="card-body">
              <h5 class="card-title fw-bold">Mission Statement</h5>
              <p class="card-text">To improve public transportation, increasing accessibility and availability for Filipinos.</p>
            </div>
          </div>
        </div>
        <div class="col-md-6 p-4">
          <div class="card bg-dark width text-light text-start mb-4" >
            <img src="https://images.pexels.com/photos/7674/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=800" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title fw-bold">Vision Statement</h5>
              <p class="card-text">Build smart communities with seamless access to secure and convenient transportation and  implement smart technologies in the Philippines with effort and passion.</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.container-fluid{
  background-color: #353743;
}

.card{
  outline-color: white;
  background-color: #404A50;
}




</style>
