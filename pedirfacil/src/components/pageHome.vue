<template>
  <div class="container">
      <h1 class="title">Pedir-Fácil</h1>
      <div class="img">  
          <img src="../assets/menu (1).jpg" alt=""> 
      </div> 
      <div class="btn">
        <h2>Cardapio</h2>
        <select>
          <option>Oque Temos</option>
          <option>Hamburger</option>
          <option>Bolos</option>
          <option>Salgados</option>
          <option>Pizza</option>
          <option>Bebidas</option>

        </select>

      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
body{
  background: #1B1B1B;
}
.title{
  color: #F8B502;
  text-align: center;
  font-size: 54px;
}
.img{
  height: 200px;
  
}
.btn{
  background: red;
  width: 100px;
  margin: auto;
 
}

select{
  font-size: 22px;
  border-radius: 5px;
 
}
/* #inner {
  margin: 0 auto;
  width: 50%; Altere para o valor da largura desejada. 
  background: #F8B502;
  color: #F8B502;

} */
img{
    display: block;
    margin-left: auto;
    margin-right: auto;
    position: static;
   
    }
    h2{
      font-size: 40px;
    }
</style>