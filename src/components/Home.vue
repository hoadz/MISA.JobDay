<template>
    <div>
        <header-home></header-home>   
        <menu1></menu1>
    </div>
</template>
<script>
import headerHome from './Layout/header.vue'
import menu1 from './Layout/menu.vue'
export default {
    components:{
        headerHome,
        menu1
    }
}
</script>
<style >
.iconBackground{
       background-image: url('../assets/icon.svg');
        
    }
</style>