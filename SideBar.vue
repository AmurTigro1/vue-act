<template>
    <div class="container">
    <!-- <div class="logo">
        <li><a href="#">Stern</a></li>
    </div>   -->
    <div class="nav">
     <ul>
    <li><a href="">MovieReel</a></li>
    <li><a href="">CinemaGuide</a></li>
    <li><a href="">PopcornPanel</a></li>
    <li><a href="">ShowtimeSider</a></li>
    
    </ul>
</div>
</div>
</template>

<style scoped>
.container {
    background-color: black;
}
.logo a{
    font-size: 40px;
    text-decoration: none;

    }
    ul {
        list-style: none;
        margin: 0;
        padding: 0;
        overflow: auto;
        border-right: 1px solid #db0000;
        /* width: 200px;
        padding-top:30px; */
        height: 100%;
        position: absolute;
        /* background-color: #ECEE81; */
    }
    ul a {
        text-decoration: none;
        color:white;
        display: flex;
        /* margin-left: 30px; */
        padding: 30px;

    }
    ul li a:hover {
        background-color: #db0000;
    }
</style>