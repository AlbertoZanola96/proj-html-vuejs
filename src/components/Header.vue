<template>
  <header>
    <div class="hed-top">
      <div class="logo">
      <img src="../assets/img/dark-logo.png" alt="">
      </div>
      <div class="serch">
        <ul>
          <li>
            <a href="#">
              <p>Home <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <a href="#">
              <p>Pages <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <a href="#">
              <p>Courses <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <a href="#">
              <p>Features <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <a href="#">
              <p>Blog <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <a href="#">
              <p>Shop <i class="fas fa-angle-down"></i></p>
            </a>
          </li>
          <li>
            <i style="color:gray" class="fas fa-shopping-cart"></i>
            <div class="circle">
              <p>0</p>
            </div>
          </li>
          <li>
            <i style="color:gray" class="far fa-user-circle"></i>
          </li>
          <li>
            <input class="btn" type="text" placeholder="     Search...">
            <i class="fas fa-search"></i>
          </li>
        </ul>
      </div>
    </div>
    <div class="jumbotron">
      <img class="svg" src="../assets/img/jumbo-overlay.svg" alt="">
      <div class="element">
        <i class="fas fa-ruler-combined"></i>
        <i class="far fa-life-ring"></i>
        <i class="fas fa-book"></i>
        <i class="fas fa-shopping-cart"></i>
      </div>
      <div class="text-jumbo">
        <h1>Complete Your <br>Dreams in JavaS <br>Programming</h1>
        <p>Lear any coding program in distance and for a <br>responsable fee. You don't have to struggle alone, <br>you've got our assistance and help.</p>
        <div class="btn-jumbo">
          <a href="#"><i class="fas fa-download"></i> Download free E-book</a>
        </div>
      </div>
      <div class="img-jumbo">
        <img src="../assets/img/home-5-hero-image.png" alt="">
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
@import '~@fortawesome/fontawesome-free/css/all.min.css';
@import "../style/vars";
header {
  width: 100%;
  height: 850px;
  background-color: #E9E6E3;

  .hed-top {
    margin: 0 auto;
    padding-top: 15px;
    position: relative;
    width: 62%;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: space-between;


    .logo {
      float: left;


      img {
        width: 150px;
      }
    }

    .serch {
      padding-top: 10px;
      float: right;
      display: flex;
      margin-top: 20px;
      

      ul {
        display: flex;
        list-style: none;

        li {
          margin-left: 28px;

          a {
            color: $primario;
          }

          .circle {
            position: absolute;
            top: 20px;
            left: 902px;
            width: 15px;
            height: 15px;
            background-color: $secondario;
            border-radius: 50%;

            p {
              color: white;
              font-size: 10px;
              text-align: center;
            }
          }

          .btn {
            position: relative;
            bottom: 14px;
            width: 200px;
            height: 50px;
            background-color: white;
            border: none;
            border-radius: 5px;
            }

          .fa-search {
            position: absolute;
            right: 15px;
            top: 30px;
            color: $secondario;
                
          }

          a {
            text-decoration: none;

            p {
              font-size: 17px;

              i {
                position: relative;
                bottom: 1px;
                padding-left: 2px;
                font-size: 14px;
              }
            }
          }
        }
      }
    }
  }
  .jumbotron {
    width: 62%;
    height: 100%;
    margin: 0 auto;

    .element {
      color: #a5a5a5;
      position: absolute;
      right: 0;
      top: 300px;
      width: 40px;
      height: 150px;
      background-color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: space-around;
      border-top-left-radius: 7px;
      border-bottom-left-radius: 7px;
    }

    .svg {
      position: absolute;
      top: 450px;
      left: 0;
      width: 100%;
      height: 400px;
      transform:rotateX(180deg);
      z-index: 3;
    }

    .text-jumbo {
      float: left;

      h1 {
        margin-top: 150px;
        font-size: 40px;
        color: $primario;
        margin-bottom: 30px;
      }

      p {
        font-size: 17px;
        font-size: 600;
        color: #9592A8;
      }

      .btn-jumbo {
        margin-top: 40px;
        width: 280px;
        height: 60px;
        background-color: $secondario;
        border-radius: 6px;

        a {
          display: flex;
          justify-content: center;
          padding-top: 17px;
          text-decoration: none;
          color: white;
          
          i {
            margin-right: 10px;
          }
        }
      }

    }

    .img-jumbo {
      float: left;

      img {
        position: relative;
        top: 100px;
        left: 200px;
        z-index: 999;
      }
    }
  }
}

</style>
