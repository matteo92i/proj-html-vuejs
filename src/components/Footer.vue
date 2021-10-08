<template>
    <div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-12 banner-2">
                    <div class="f-center">
                        <img src="../assets/img/logo.png" alt="logo">
                        <p class="p-white ordine">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione. Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem libero, dolorum, totam fugit sed quisquam, recusandae adipisci architecto dicta iure.</p>
                        
                        <div> 
                            <ul>
                                <li class="cerchio" v-for="(element,index) in social" :key="index">   
                                    <a :href="element.link"></a>
                                </li>
                            </ul> 
                        </div>
                    
                    </div>



                </div>
            </div>
        </div>

        <div class="copyright">
            <p class="p-white-copyright"> copyrightcopyrightcopyrightcopyright</p>
        </div>

    </div>
</template>

<script>
import social from "../datiJs/Footerlink.js"
export default {
    name:'Footer',
    data: function(){
    return{
        social: social,
        }
    }
    
}
</script>

<style lang="scss">
.banner-2{
    background-image: url(../assets/img/footer2x.jpg);
    background-color: #cccccc; 
    height: 600px; 
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover;
    width: 100%;
}
.ordine{
    text-align: center;
    width: 400px;
    height: 100px;
}
.cerchio{
    background-color: white;
    border: 1px solid white;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    margin: 15px 15px;
}
.copyright{
    background-color: black;
    height: 60px;
}
.p-white-copyright{
    color: white;
    text-align: center;
    font-size: 10px;
}
    

    

</style>