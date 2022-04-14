<template>
<div>
    © All rights Reserved
    <nav>
        <a href="https://google.ca">Link to Google</a>
    </nav>
</div>


</template>

<script>
export default {
    name : 'FooterComp',
    props :{
        title: {
            type: String,
        default: "I'm a footer",
        },
    },
    

}

</script>

<style scoped>
nav a {
    color: black;
}
</style>