<template>
  <div class="contact">
    <img src="../assets/img.png" />
    <p>
      ビジネスのお話、お仕事依頼、その他...etc
      <br />お気軽にご連絡ください！
    </p>
    <a href="mailto:terubot1711@icloud.com">
      <font-awesome-icon icon="envelope" />inomata1117&#64;eay.jp
    </a>
    <a href="https://line.me/ti/p/zgLYzv_eoh">
      <font-awesome-icon :icon="['fab', 'line']" />LINE ID:teruyainomata
    </a>
    <Footer />
  </div>
</template>

<script>
import Footer from "../components/Footer.vue";
export default {
  components: {
    Footer
  }
};
</script>

<style scoped>
img {
  border-radius: 100px;
  width: 110px;
  display: block;
  margin: auto;
  margin-top: 50px;
  margin-bottom: 40px;
}
p {
  text-align: center;
  font-size: 15px;
}
a {
  display: flex;
  justify-content: center;
  font-size: 15px;
  color: #1976d2;
}
a:hover {
  opacity: 0.6;
}
</style>