<template>
    <div>
        <div class="container-fluid">
            <div class="row">
                <div class="col-4">
                    <div class="sfondo-1">
                        <h1 class="h1-menu">hors d'oeuvres</h1>
                        <Menu v-for="(element, index) in pranzo" :key="index" :nome="element.nomePiatto" :prezzo="element.prezzo" :descrizione="element.descrizionePiatto"/>
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
            ]
        }
    }
    
}
</script>

<style lang="scss">

    
</style>