<template>
    <p class="text-center fst-normal">RCN Soft © Copyright {{ano}} </p>
</template>
<script>
    let year = new Date();
    year = year.getFullYear();
    
    export default{
        name : 'FooterVue',
        data(){
            return{
                ano : year
            }
        }
    }
</script>