<template>
  <main>
    <div class="block-one">
      <div class="text-one">
        <p>START LEARNING CODING LANGUAGES</p>
        <h2>Build Your Dream <span>TODAY</span></h2>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: 'Main',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
@import '~@fortawesome/fontawesome-free/css/all.min.css';
@import "../style/vars";
main {
  width: 100%;

  .block-one {
    width: 62%;
    margin: 0 auto;

    .text-one {
      text-align: center;
      margin-top: 70px;

      p {
        color: #666868;
        font-weight: 500;
        margin-bottom: 15px;
      }

      h2 {
        font-size: 40px;
        color: $primario;
        font-weight: 600;

        span {
          font-size: 40px;
          color: $secondario;
          font-weight: 600;
        }
      }
    }
  }
}

</style>
