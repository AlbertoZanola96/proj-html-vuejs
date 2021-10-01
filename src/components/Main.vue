<template>
  <main>
    <div class="block-one">
      <div class="text-one">
        <p>START LEARNING CODING LANGUAGES</p>
        <h2>Build Your Dream <span>TODAY</span></h2>
      </div>
      <div class="element">
        <div class="item">
          <img src="../assets/img/home-5-image-box-01.png" alt="">
          <h3>Idea Discussion</h3>
          <p>Get teamed up with the specialists<br>who work and teach coding for years<br>at famous universities.</p>
          <div class="btn">
            <button>Start now <i class="fas fa-arrow-right"></i></button>
          </div>
        </div>
        <div class="item">
          <img src="../assets/img/home-5-image-box-02.png" alt="">
          <h3>Web Development</h3>
          <p>Learn to start building a webpage from<br>scratch. You decide your own pace,<br>course and speed.</p>
          <div class="btn">
            <button>Start now <i class="fas fa-arrow-right"></i></button>
          </div>
        </div>
        <div class="item">
          <img src="../assets/img/home-5-image-box-03.png" alt="">
          <h3>System Administration</h3>
          <p>Learners are encouraged to study the<br>mechanism and structure of system<br>administration.</p>
          <div class="btn">
            <button>Start now <i class="fas fa-arrow-right"></i></button>
          </div>
        </div>
        <div class="item">
          <img src="../assets/img/home-5-image-box-04.png" alt="">
          <h3>Graphic Design</h3>
          <p>have a passion for graphics and arts?<br>Show your talents with confidence and<br>self-assertiveness.</p>
          <div class="btn">
            <button>Start now <i class="fas fa-arrow-right"></i></button>
          </div>
        </div>
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
    height: 650px;
    margin: 0 auto;

    .text-one {
      text-align: center;
      padding-top: 70px;

      p {
        color: #666868;
        font-weight: 500;
        padding-bottom: 15px;
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
    .element {
      display: flex;
      justify-content: space-between;
      padding-top: 70px;

      .item {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        h3 {
          font-weight: 600;
          color: #0e0e0e;
        }

        p {
          color: #666868;
          font-size: 14px;
          text-align: center;
          padding-top: 20px;
        }

        .btn {
          margin-top: 20px;

          button {
            border: none;
            background-color: white;
            color: $primario;
            font-size: 17px;
            font-weight: 600;
          }
        }
      }
    }
  }
}

</style>
