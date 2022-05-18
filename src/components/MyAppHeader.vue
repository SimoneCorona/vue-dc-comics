<template>
  <header>
    <div class="container">
      <div class="header_logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      
      <nav>
        <ul>
          <li><a href=""> CHARACTERS </a></li>
          <li class="active"><a href=""> COMICS </a></li>
          <li><a href=""> MOVIES </a></li>
          <li><a href=""> TV </a></li>
          <li><a href=""> GAMES </a></li>
          <li><a href=""> COLLECTIBLES </a></li>
          <li><a href=""> VIDEOS </a></li>
          <li><a href=""> FANS </a></li>
          <li><a href=""> NEWS </a></li>
          <li><a href=""> SHOP </a></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {
  name: 'MyAppHeader',
}
</script>


<style scoped lang="scss">
@import "../style/variables.scss";

header{
  padding: 1rem auto;

  .container{
    display: flex;
    align-items: center;
  }
  .header_logo img{
    height: 70px;
    
  }
  nav{
  display: inline-block;
  width: 100%;
  height: 100px;
  
  .active{
          color: #0C7CEC;
          border-bottom: 4px solid #0C7CEC;
        }
    ul{
      display: flex;
      justify-content: end;
    
      li{
        margin-left: 1.5rem;
        line-height: 96px;
        
        a{
          font-weight: bold;
          color: inherit;
          height: 100%;
        }
        
      }
    }  
  }
}


</style>
