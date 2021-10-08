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
                        <h2 class="h2-menu">Main Course</h2>
                        <Menu v-for="(element, index) in colazione" :key="index" :nome="element.nomePiatto" :prezzo="element.prezzo" :descrizione="element.descrizionePiatto"/>
                    </div>
                </div>

                <div class="col-4 p-0">
                    <div class="sfondo-1">
                        <h1 class="h1-menu">Desserts</h1>
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
                    nomePiatto:'ahi salmon nigiri',
                    prezzo: 48,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'umi masu salad',
                    prezzo: 21,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'Temaki with crab',
                    prezzo: 32,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'california rolls',
                    prezzo: 22,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
            ],
            colazione:[
                {
                    nomePiatto:'Braised abalone',
                    prezzo: 52,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'twice cooked pork',
                    prezzo: 21,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'kung pao chicken',
                    prezzo: 32,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'char siu & Sushis',
                    prezzo: 48,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
            ],
            cena:[
                {
                    nomePiatto:'chocolate ball cake',
                    prezzo: 13,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'Lime pie with crust',
                    prezzo: 14,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },                
                {
                    nomePiatto:'Rasberry Pear cake',
                    prezzo: 18,
                    descrizionePiatto:'ragu piselli e tanto altro'
                },
                {
                    nomePiatto:'cafè au lait',
                    prezzo: 6,
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
    background-color: rgb(231, 226, 226);
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
    filter: brightness(10%);
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