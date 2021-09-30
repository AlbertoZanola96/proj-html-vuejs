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
            <i class="fas fa-shopping-cart"></i>
          </li>
          <li>
            <i class="far fa-user-circle"></i>
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
@import '~@fortawesome/fontawesome-free/css/all.min.css';
header {
  width: 100%;
  height: 750px;
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
            top: 23px;
            color: #20AD96;
                
          }

          a {
            text-decoration: none;

            p {
              font-size: 17px;

              i {
                position: relative;
                bottom: 2px;
                padding-left: 2px;
                font-size: 12px;
              }
            }
          }
        }
      }
    }
  }
  .jumbotron {

    .svg {
      width: 100%;
      height: 400px;
      transform:rotateX(180deg);
      margin-top: 290px;
    }
  }
}

</style>
