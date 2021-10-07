<template>
    <div>
        <div class="container-fluid">
            <div class="row">
              
              <div class="col-5 sfondo">
                  <div class="col-12">
                      <img src="../assets/img/logo.png" alt="logo">
                  </div>
                  <div class="col-8 mx-auto">
                      <h5>the best table in town</h5>
                  </div>
                  <div class="col-8 mx-auto">
                      <h1 class="h1-white">fine dining experience </h1>
                  </div>
                  <div class="col-8 mx-auto">
                      <p class="p-white">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi ratione assumenda ad corrupti atque architecto ex impedit aperiam? Perspiciatis cum in unde recusandae blanditiis saepe alias maxime molestias aperiam dolorum!</p>
                  </div>
                  <div class="col-8 mx-auto">
                      <button class="stile">explore the menu</button>
                  </div>

              </div>

              <div class="col-7">
                  <img class="img-sfondo" src="../assets/img/slider52x.jpg" alt="slider">
              </div>

            </div>

        </div>

    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss">
.img-sfondo{
    width: 100%;
    height: 600px;
}
.sfondo{
    height: 600px;
    background-color: black;
}
h5{
    text-transform:uppercase;
    color: white;
}
.h1-white{
    text-transform:uppercase;
    color: white;
    
}
.p-white{
    color: white
}
.stile{
    border: 2px solid white;
    background-color: black;
    text-transform:uppercase;
    color: white;
}
    
    
    





</style>