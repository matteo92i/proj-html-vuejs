<template>
    <div>
        <div class="prezzo">
            <h3 class="h3-menu">{{nome}}</h3>
            <span>{{prezzo}}</span>
        </div>
        <p class="p-menu">{{descrizione}}</p>
    </div>
        

</template>



        
            

<script>
export default {
    name:"Menu",
    props:['nome','prezzo','descrizione'],
    
}
</script>

<style lang="scss">



    

.prezzo{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-left: 60px;
    margin-right: 60px;
    padding-top:10px;
    padding-bottom: 10px;
}


.h3-menu{
    color: black;
}
.h3-menu-2{
    color: white;
}
    
.p-menu{
    color: black;
    text-align: left;
    margin-left: 60px;
    margin-right: 60px;
}
.p-menu-2{
    color: white;
    text-align: left;
    margin-left: 60px;
    margin-right: 60px;
}

</style>