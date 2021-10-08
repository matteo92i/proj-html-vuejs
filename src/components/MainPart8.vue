<template>
    <div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-4 p-0">
                    <div class="sfondo-1">
                        <h1 class="h1-menu">hors d'oeuvres</h1>
                        <Menu v-for="(element, index) in pranzo" :key="index" :nome="element.nomePiatto" :prezzo="element.prezzo" :descrizione="element.descrizionePiatto"/>
                    </div>
                </div>

                <div class="col-4 p-0">
                    <div class="sfondo-2">
                        <h2 class="h2-menu"></h2>
                        <Menu v-for="(element, index) in colazione" :key="index" :nome="element.nomePiatto" :prezzo="element.prezzo" :descrizione="element.descrizionePiatto"/>
                    </div>
                </div>

                <div class="col-4 p-0">
                    <div class="sfondo-1">
                        <h1 class="h1-menu">hors d'oeuvres</h1>
                        <Menu v-for="(element, index) in cena" :key="index" :nome="element.nomePiatto" :prezzo="element.prezzo" :descrizione="element.descrizionePiatto"/>
                    </div>
                </div>

                
            </div>

                    
        </div>


    </div>
</template>




<script>
import Menu from "./Menu.vue"
export default {
    name:'MainPart8',

    components: {
        Menu,
    },
    data: function(){
        return{
            pranzo:[
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
            ],
            colazione:[
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
            ],
            cena:[
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lasagne',
                    prezzo: 40,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
            ]
                
        }
    }
    
}
</script>

<style lang="scss">
.sfondo-1{
    margin-top: 90px ;
    background-color: grey;
    height: 700px;
}
.sfondo-2{
    background-image: url(../assets/img/misc22x.jpg);
    background-color: white;
    margin-top: 60px;
    height: 700px; 
    background-position: center; 
    background-repeat: no-repeat; 
    background-size: cover;
    width: 100%;
}
.h1-menu{
    color: black;
    text-align: center;
    padding-top: 60px;
    padding-bottom: 60px ;
}
.h1-menu-2{
    color: white;
    text-align: center;
    padding-top: 60px;
    padding-bottom: 60px ;
    
}

    
</style>