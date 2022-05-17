<template>
  <header>
    <div class="container">
      <div class="header_logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav>
        <ul>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
          <li><a href=""> Link </a></li>
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
  margin: 1rem auto;

  .container{
    display: flex;
    align-items: center;
  }
  .header_logo img{
    height: 80px;
  }
  nav{
  width: 100%;

    ul{
      display: flex;
      justify-content: end;
    
    
      li{
        margin-left: 2rem;
        // line-height: 100%;
        
        a{
          color: #000000;
        }
      }
    }  
  }
}


</style>
