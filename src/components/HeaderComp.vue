<template>
<div id="header">
<h1> Welcome to my Page</h1>
<BodyComp/>
<FooterComp/>
</div>


</template>

<script>
import BodyComp from '@/components/BodyComp.vue'
import FooterComp from '@/components/FooterComp.vue'


export default {
    name : 'HeaderComp',
    components: {
        BodyComp,
        FooterComp,
    },
}





</script>
<style scoped>
h1{
    background-color: rgb(0, 2, 54);
    color: white;
}

</style>