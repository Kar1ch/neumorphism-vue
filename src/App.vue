<script setup>
</script>

<template>
  <div class="content-wrapper">
    <div class="container">
      <div class="header">
<<<<<<< Updated upstream
        <h3>Инди работяги</h3>
        <div>Юра в тайне гей</div>
=======
        <h3>Заголовок</h3>
        <div>Текст но поменьше</div>
>>>>>>> Stashed changes
      </div>

      <div class="container-blocks">
        <div class="circle-block"></div>

        <img class="girl-pic" src="https://www.indieworkers.ru/workers.svg"/>
      </div>
        
      <div class="footer">
      </div>
    </div>
  </div>
</template>

<style scoped>
  .content-wrapper{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .container{
    flex-direction: column;
    display: flex;
    margin: auto;
    background-color: #ecf0f3;
    width: 400px;
    filter: drop-shadow(10px 10px 5px #d1d9e6) drop-shadow(-5px -5px 5px #fff);
    /*filter: drop-shadow();
    /*box-shadow: inset 10px 10px 10px #d1d9e6;*/
    border-radius: 60px;
    padding: 20px;
  }

  .header{
    display: flex;
    background-color: #ecf0f3;
    filter: drop-shadow(10px 10px 5px #d1d9e6) drop-shadow(-5px -5px 5px #fff);
    border-radius: 40px;
    padding: 12px 24px;
    flex-direction: column;
  }

  .container-blocks{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
  }

  .circle-block{
    margin-top: 20px;
    width: 190px;
    height: 190px;
    background-color: #ecf0f3;
    box-shadow: inset 10px 10px 10px #d1d9e6, inset -5px -5px 10px #fff;
    border-radius: 100%;
  }

  .girl-pic{
    margin-top: 20px;
    width: 190px;
    height: 190px;
    border-radius: 40px;
  }

  .footer{
    background-color: #ecf0f3;
    display: flex;
    border-radius: 40px;
    margin-top: 20px;
    padding: 36px 24px;

    box-shadow: inset 10px 10px 10px #d1d9e6, inset -5px -5px 10px #fff;
  }
</style>
