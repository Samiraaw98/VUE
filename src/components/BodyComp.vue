<template>
<div id="body">
<h2> {{title}}  </h2>
<p :id = 'firstId'>{{content}} </p>

</div>

</template>
<script>
export default {
    name : 'BodyComp',
    props: {
        title: {
            type: String,
            default:"I'm a Body Comp" ,
        },
    },
    data() {
        return {
            content: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque esse odio doloribus dolore. Magnam!",
            firstId :'Para',
        }
    },
}


</script>

<style scoped>

</style>