<template>
    <main>
        <h2>Exercício de Formulário:</h2>  
          <label id="titulo">Nome:</label>        
          <input class="insert" placeholder="" type="text">
          <label>E-mail:</label>  
          <input class="insert" placeholder="" type="text">
          <label>Gênero:</label>  
          <input class="insert" placeholder="" type="text">
          <label>Endereço:</label>  
          <input class="insert" placeholder="" type="text">
          <label>Telefone:</label>  
          <input class="insert" placeholder="" type="tel">          
      </main>
</template>

<script></script>

<style scoped>
  main{
    display: flex;
    justify-content: center;
     width: 50vw;
    height: 100vh;
    flex-direction: column;
  }

  .insert {
    border: solid 2px rgb(5, 0, 7);
    background-color: rgb(250, 242, 231);
    border-radius: 23px;
    height: 40px;
    width: 450px;
  }
</style>   