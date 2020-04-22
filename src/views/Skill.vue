<template>
  <div>
    <h2>My portfolio</h2>
    <div class="f-container">
      <div class="f-item1">
        <a href="http://3.114.158.164/">
          <img src="../assets/img1.png" alt="" height="257" width="335">
        </a>
      </div>
      <div class="f-item2">
        <a href="/">
        <img src="../assets/img2.png" alt="" height="257" width="335">
        </a>
      </div>
      <div class="f-item3">
        <a href="https://slack-clone-app-4d8ac.web.app/">
          <img src="../assets/img3.png" alt="" height="257" width="335">
        </a>
      </div>
      <div class="f-item4">
        <a href="https://heyvuejs.netlify.app/">
          <img src="../assets/img4.png" alt="" height="257" width="335">
        </a>
      </div>
      <div class="f-item5">
        <a href="#">
          <img src="../assets/img5.png" alt="" height="257" width="335">
        </a>
      </div>
      <div class="f-item6">
        <a href="#">
          <img src="../assets/img5.png" alt="" height="257" width="335">
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
  h2 {
    text-align: center;
    margin-top: 60px;
    font-family: 'Amatic SC', cursive;
  }
  .f-container{
    display: flex;
    flex-wrap:wrap;
    margin-left: 155px;
    cursor: pointer;
  }
  .f-item1{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
    transition: 0.5s;
  }
  .f-item1:hover{
    opacity:  0.7;
    width: 340px;
  }
  .f-item2{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
    transition: 0.5s;
  }
  .f-item2:hover{
    opacity:  0.7;
    width: 340px;
  }
  .f-item3{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
    transition: 0.5s;
  }
  .f-item3:hover{
    opacity:  0.7;
    width: 340px;
  }
  .f-item4{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
    transition: 0.5s;
  }
  .f-item4:hover{
    opacity:  0.7;
    width: 340px;
  }
  .f-item5{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
  }
  .f-item6{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0 0 0 1px;
  }
</style>