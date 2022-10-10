<template>
  <header class="container">
    
     <img src="../assets/img/dc-logo.png" alt="logo"/>
     <nav>
        <ul>           
            <li>
                <a href="#">CARACTERS</a>
            </li>
            <li>
                <a href="#">COMICS</a>
            </li>
            <li>
                <a href="#">MOVIES</a>
            </li>
            <li>
                <a href="#">TV</a>
            </li>
            <li>
                <a href="#">GAMES</a>
            </li>
            <li>
                <a href="#">COLLECTIBLES</a>
            </li>
            <li>
                <a href="#">VIDEOS</a>
            </li><li>
                <a href="#">FANS</a>
            </li>
            <li>
                <a href="#">NEWS</a>
            </li>
            <li>
                <a href="#">SHOP</a>
            </li>
            
        </ul>
       
     </nav>
    
    
  </header>
  
  
</template>

<script>
export default {
    name:'HeaderComponent',
    
};
</script>

<style
lang="scss" scoped>
.container {
    margin: 50px auto;
    max-width: 1200px;
    display: flex;
    justify-content: space-between;
}
img {
    width: 80px;
}
nav {
    margin-top: 20px;
    display: flex;
    justify-content: space-between;    
}
ul {
    display: flex;
    justify-content: space-between;  
    list-style: none;
}
li {
   padding-left: 1%;   
}
a {
    color: black;
    text-decoration-line: none;
}



</style>