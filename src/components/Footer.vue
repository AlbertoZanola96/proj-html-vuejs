<template>
  <footer>
    <div class="f-top">
      <div class="left">
        <div class="col1">
          <ul>
            <li><h4>Address</h4></li>
            <li><p>382 NE 191 st St # 87394 Miami, FL 33179-3899</p></li>
            <li><p>+1 (305) 547-9909 (9am - 5pm EST, Monday - Friday)</p></li>
            <li><p>support@maxcoach.com</p></li>
            <li>
              <i class="fab fa-facebook-square"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-instagram"></i>
              <i class="fab fa-linkedin"></i>
            </li>
          </ul>
        </div>
      </div>
      <div class="right">
        <div class="col2">
          <ul>
            <li><h4>Explore</h4></li>
            <li><p>Start here</p></li>
            <li><p>Blog</p></li>
            <li><p>About us</p></li>
          </ul>
        </div>
        <div class="col-3">
          <ul>
            <br>
            <li><p>Success Story</p></li>
            <li><p>Courses</p></li>
            <li><p>Contact us</p></li>
          </ul>
        </div>
        <div class="col-4">
          <ul>
            <li><h4>Information</h4></li>
            <li><p>Membership</p></li>
            <li><p>Purchase guide</p></li>
            <li><p>Privacy policy</p></li>
            <li><p>Terms of services</p></li>
          </ul>
        </div>
      </div>
    </div>
    <div class="f-bottom">
      <p><i class="far fa-copyright"></i> 2020 Maxcoach. All Rights Reserved</p>
      <button><a href="/"><i class="fas fa-arrow-up"></i></a></button>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');
@import '~@fortawesome/fontawesome-free/css/all.min.css';
@import "../style/vars";
footer {
  width: 100%;
  height: 380px;
  background-color: #FFFFFF;

  .f-top {
    width: 62%;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    margin-top: 80px;

    .left {
      width: 40%;
      ul {
        list-style: none;

        h4 {
          color: #333333;
        }

        p {
          color: #666868;
          font-size: 14px;
          padding-top: 5px;
          padding-bottom: 5px;
        }
        
        i {
          font-size: 30px;
          padding: 30px 40px 0 0;
          color: #666868;
        }
      }
    }

    .right {
      width: 60%;
      display: flex;
      justify-content: flex-end;

      ul {
        list-style: none;
        padding: 0 50px 0 50px;

        h4 {
          color: #333333;
        }

        p {
          color: #666868;
          font-size: 14px;
          padding-top: 5px;
          padding-bottom: 5px;
        }
      }
    }
  }
  .f-bottom {
    margin-top: 90px;
    text-align: center;
    
    p {
      color: #666868;
    }

    button {
      position: absolute;
      right: 40px;
      width: 75px;
      height: 75px;
      border-radius: 50%;
      background-color: $secondario;
      border: none;

      i {
        color: white;
        font-size: 20px;
      }
    }
  }
}
</style>
