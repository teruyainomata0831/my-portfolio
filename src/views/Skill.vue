<template>
  <div>
    <h2>My portfolio <router-link to="/contact">&gt;</router-link></h2>
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
    <Footer />
  </div>
</template>

<script>
import Footer from '../components/Footer.vue'
export default {
  components: {
    Footer
  }
}
</script>

<style scoped>
  h2 {
    text-align: center;
    margin-top: 60px;
    font-family: 'Lato', sans-serif;
    font-family: 'Baloo Bhaina 2', cursive;
    font-family: 'Source Sans Pro', sans-serif;
    font-family: 'Playfair Display', serif;
  }
  .f-container{
    display: flex;
    flex-wrap:wrap;
    margin-left: 155px;
    cursor: pointer;
    max-width: 100%;
  }
  .f-item1{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
    border-radius: 5px;
  }
  .f-item1:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
  .f-item2{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
    border-radius: 5px;
  }
  .f-item2:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
  .f-item3{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
  }
  .f-item3:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
  .f-item4{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
    border-radius: 5px;
  }.f-item4:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
  .f-item5{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
    border-radius: 5px;
  }
  .f-item5:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
  .f-item6{
    width: 335px;
    height: 257px;
    margin: 20px;
    box-shadow: 0px 3px 10px rgba(0,0,0,0.2);
    transition: .3s;
    border-radius: 5px;
  }
  .f-item6:hover{
    box-shadow: 0 10px 15px -5px rgba(0,0,0,.15),0 0 5px rgba(0,0,0,.1);	transform: translateY(-50px);
    transition: 0.3s;
  }
</style>