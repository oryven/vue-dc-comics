<template>
  <section>
    <div class="container">
      <button>Sign Up Now!</button>

      <div>
      <div>Follow Us</div>
        <ul>
          <li><img src="../assets/img/footer-facebook.png" alt=""></li>
          <li><img src="../assets/img/footer-twitter.png" alt=""></li>
          <li><img src="../assets/img/footer-youtube.png" alt=""></li>
          <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
          <li><img src="../assets/img/footer-periscope.png" alt=""></li>
        </ul>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'Social',
  
}
</script>

<style scoped lang="scss">
    section {
        height: 100px;
        background-color: #303030;
        .container {
          height: 100px;
          display: flex;
          justify-content: space-between;
          width: 80%;
          margin: auto;
        }
        button {
            font-size: 14px;
            border: 2px solid #008CFF;
            background-color: transparent;
            color: white;
            padding: 10px;
        }
        div {
            display: flex;
            align-items: center;
            margin-right: 20px;
            color: #008CFF;
            text-transform: uppercase;
            font-weight: bold;
        }
        ul {
            display: flex;
            align-items: center;
            li {
                display: inline-block;
                margin-right: 20px;   
            }
        }
    }
</style>