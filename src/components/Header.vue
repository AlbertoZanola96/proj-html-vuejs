<template>
  <header>
    <div class="container">
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
              <input type="text" name="" id="">
            </li>
          </ul>
        </div>
      </div>
      <div class="jumbotron">
        
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
@import '~@fortawesome/fontawesome-free/css/all.min.css';
header {
  width: 100%;
  height: 750px;
  background-color: #E9E6E3;

  .container {
    width: 60%;
    height: 100%;
    margin: 0 auto;
    border: 1px solid black;
    
    .hed-top {
      width: 100%;
      height: 80px;
      background-color: red;
      display: flex;
      align-items: center;
      justify-content: space-between;

      .logo {
        float: left;


        img {
          width: 170px;
        }
      }

      .serch {
        float: right;
        display: flex;


        ul {
          display: flex;
          list-style: none;

          li {
            margin-left: 35px;
          }
        }
      }
    }
  }
}

</style>
