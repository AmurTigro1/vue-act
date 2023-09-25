<template>
    <div class="container">
        <div class="logo">
        </div>
        <div class="list">
     <ul>
                <img src="./N.png" alt="">
        <li><a href="#">TV Shows</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">My list</a></li>
    </ul>
    <!-- <div class="right">
        <ul>
        <li><a href="#">TV Shows</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">My list</a></li>
    </ul>
    </div> -->
    
</div>
</div>
</template>

<style scoped>
.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.right {
    display: flex;
    justify-content: space-between;
}
img {
    height: 100px;
}
ul li a:hover {
        background-color: #db0000;
    }
    .list {
        width:100%;
        /* background-color: rgb(24, 113, 29); */
    }
    ul {
        list-style: none;
        display: flex;
        align-items: center;
       /* background-color: #ECEE81; */
        padding: 10px;
        /* margin-left: 150px; */

    }
    ul a {
        text-decoration: none;
        color:white;
        padding:25px;
        font-size: 15px;
        margin-top:0%;
    }
</style>