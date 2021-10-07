<template>
    <div>
        <div class="container">
            <div class="row mt-5">
                <div class="col-4 p-0">
                    <div class="sfondo-1">
                        <h1 class="h1-menu">hors d'oeuvres</h1>
                        <div class="prezzo">
                            <h3 class="h3-menu">ahi salmon nigri</h3>
                            <span>48$</span>
                        </div>
                        <p class="p-menu">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>

                        <div class="prezzo">
                            <h3 class="h3-menu">ahi salmon nigri</h3>
                            <span>48$</span>
                        </div>
                        <p class="p-menu">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>

                        <div class="prezzo">
                            <h3 class="h3-menu">ahi salmon nigri</h3>
                            <span>48$</span>
                        </div>
                        <p class="p-menu">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>

                        <div class="prezzo">
                            <h3 class="h3-menu">ahi salmon nigri</h3>
                            <span>48$</span>
                        </div>
                        <p class="p-menu">Lorem ipsum dolor sit amet consectetur adipisicing elit..</p>
                    </div>
                </div>

                <div class="col-4 p-0">
                    <div class="sfondo-2"></div>
                </div>

                <div class="col-4 p-0">
                    <div class="sfondo-1"></div>
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
.sfondo-1{
    margin-top: 60px ;
    background-color: grey;
    height: 700px;
}
.sfondo-2{
    background-image: url(../assets/img/misc22x.jpg);
    background-color: #cccccc; 
    height: 700px; 
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover;
    width: 100%;
}
.prezzo{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-left: 60px;
    margin-right: 60px;
    padding-top:10px;
    padding-bottom: 10px;
}
.h1-menu{
    color: black;
    text-align: center;
    padding-top: 60px;
    padding-bottom: 60px ;
}
.h3-menu{
    color: black;
}
    
.p-menu{
    color: black;
    text-align: left;
    margin-left: 60px;
    margin-right: 60px;
}
    
</style>