<template>
    <div>
        <div class="container-fluid">
            <div class="row">
              
                <div class="col-5 p-0 sfondo">
                    <img class="img-fluid img-margine" src="../assets/img/logo.png" alt="logo">
                    <div class="h-flex">
                        <h5 class="h5-margine">the best table in town</h5>
                        <h1 class="h1-white h1-margine">fine dining experience </h1>
                        <p class="p-white p-margine">Lorem ipsum dolor sit amet consectetur adipisicing elit. Commodi ratione assumenda ad corrupti atque architecto ex impedit aperiam? Perspiciatis cum in unde recusandae blanditiis saepe alias maxime molestias aperiam dolorum!</p>
                        <button class="stile b-margine">explore the menu</button>
                    </div> 
                </div>


            
                <div class="col-7 p-0">
                    <div class="banner-0 d-flex justify-content-center">
                        <nav>
                            <ul>
                                <li v-for="(element,index) in cerca" :key="index">
                                    <a :href="element.link">{{element.titolo}}</a>
                                </li>
                            </ul>
                        </nav>
                    </div>
                </div>

            </div>
        </div>


    </div>

</template>

            

<script>
import cerca from "../datiJs/Navbar.js"
export default {
    data: function(){
        return{
            cerca: cerca,
        }
    }
    
}
</script>

<style lang="scss">
.banner-0{
    background-image: url(../assets/img/slider52x.jpg);
    background-color: #cccccc; 
    height: 600px; 
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover;
    width: 100%;
}
.img-sfondo{
    width: 100%;
    height: 600px;
}
.sfondo{
    height: 600px;
    background-color: black;
}
.h-flex{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.img-margine{
    margin-bottom: 90px;
    padding-top: 30px;
    margin-left: 45px;
}
    

h5{
    text-transform:uppercase;
    color: white;
}
.h5-margine{
    width: 400px;
    margin-bottom: 30px;
    font-size: 10px;
}
.h1-margine{
    width: 400px;
    margin-bottom: 30px;
}
.p-margine{
    width: 400px;
    margin-bottom: 30px;
}
.b-margine{
    width: 250px;
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
ul{
    display: inline;
    list-style: none;
}
li{
  float: left;
  font-size: 15px;
  margin-left: 15px;
  margin-right: 10px;
}
a:-webkit-any-link {
    color: white;
    cursor: pointer;
    text-decoration: none;
}

  
</style>



    



                      
                 

                      
                  
                  
                     
                  



    
    




