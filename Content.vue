<template>
    <div class="content">
    <img src="./1.webp" alt="">
    <img src="./2.jpg" alt="">
    <img src="./3.jpg" alt="">
    <img src="./4.jpg" alt="">
    <img src="./6.jpg" class="a" alt="">
    <img src="./7.jpeg" alt="">

</div>
</template>
<style scoped>
    p {
        color:white;
    }
    content .a {
        height:168px;
        width: 299;
    }
    .content {
        min-width:150px;
        margin-left: 250px;
         position: relative;
        overflow: hidden;
    }
    img {
    padding: 30px;
    height: auto;
    transition: transform 0.3s, opacity 0.3s;
    }
   img:hover {
    transform: scale(1.1); /* Increase the scale on hover (you can adjust the value) */
    opacity: 0.7; 
   }
    
</style>