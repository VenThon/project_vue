<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <!-- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous"> -->
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
   <div class="wrapper">
        <div class="header">
              <div class="header_left">
                  <h1>Couple Shop</h1>
                  <ul>
                    <li><a href="#product1">Product1</a></li>
                    <li><a href="#product2">Product2</a></li>
                    <li><a href="#product3">Product3</a></li>
                  </ul>
              </div>
              <div class="header_right">
                <form class="btn" style="margin:auSto;max-width:300px">
                    <input type="text" placeholder="Search.." name="search2">
                    <button type="submit"><i class="fa fa-search"></i></button>
                </form>
              </div>
        </div>
        <div class="container" style="height: 530px; width: 100%; padding-top: 100px; ">
            
            <div class="sub_contain" style="display: flex; padding: 15px;">
              <div class="sub_container">
              <h2>Welcome guys to my couple shop</h2>
              <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. psa earum? Vel ipsum consequuntur mollitia exercitationem animi sapiente qui. Dolore voluptas magnam omnis error dolorem?</p>
              <button>Go to website</button>
            </div>
            <div class="image">
              <img src="./img/p1.jpg" style=" width: 100%; height: 500px;">
            </div>
            </div>
        </div>

        <div class="content">
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
                
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
        </div>
        <div class="content">
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
                
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
            <div class="sub_content1">
                <img src="./img/p1.jpg" alt="">
                <p>Cloths Couple</p>
                <div class="btn_order">
                  <button>Boy Now</button>
                </div>
            </div>
        </div>
        <div class="end_content">
          <div class="end_content_left">
            <div class="name_product">
              <ul>
                    <li><a href="#product1">Product1</a></li>
                    <li><a href="#product2">Product2</a></li>
                    <li><a href="#product3">Product3</a></li>
              </ul>
            </div>
            <!-- <div class="socalmedia">
                <i class="fa fa-facebook-official" aria-hidden="true"></i>
              <i class="fa fa-instagram" aria-hidden="true"></i>
              <i class="fa fa-linkedin" aria-hidden="true"></i>
            </div> -->

          </div>
          <div class="socalmedia">
                <i class="fa fa-facebook-official" aria-hidden="true"></i>
              <i class="fa fa-instagram" aria-hidden="true"></i>
              <i class="fa fa-linkedin" aria-hidden="true"></i>
          </div>
          <div class="end_content_right">
              <button>Enter Email</button>
              <button>Subscribe</button>
          </div>
        </div>
  </div>
  </header>
</template>

<style scoped>
    /* <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> */
  
    .wrapper{
      background-color: silver;
      width: 100%;
      /* height: 100vh; */
      height: auto;
      border-radius: 10px;
    }
    .header{
      background-color:#4a529d ;
      height: 80px;
      /* padding: 20px; */
      position: absolute;
      display: flex;
      border-radius: 10px;
      justify-content: space-between;
      width: 98%;
      
    }
    h1{
      color:white;
      display: flex;
      margin-left: 10px;
      align-items: center;
    }
    ul {
      list-style-type: none;
      display: flex;
      justify-content: space-around;
      /* width: 400px;
      height: 40px; */
      gap: 20px;
      /* background-color: brown; */
    }
    ul li a{
      color: white;
      font-size: 1.4rem;
    }
    .header_left{
      width: 55%;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .header_right{
      display: flex;
      align-items: center;
      margin-right: 10px;
    }
    .header_right input{
      height: 30px;
      width: 200px;
      border-radius: 5px;
    }
    .header_right button{
      height: 35px;
      width: 50px;
      border-radius: 5px;
    }
    .container{
      display: flex;
    }
    .sub_container{
      width: 60%;
      height: 500px;
      background-color:whitesmoke;
      border-radius: 10px;
    }
    .sub_container h2{
      font-size: 2rem;
      color: brown;
      padding: 50px;
    }
    .sub_container p{
      padding: 0px 20px 0px 20px;
      font-size: 1.1rem;
      color:black;
    }
    .sub_container button{
      background-color: silver;
      height: 30px;
      border-radius: 6px;
      color: black;
      margin: 20px 0px 0px 40px;
    }
    .image{
      width: 40%;
    }
    img{
      border-radius: 10px;
      
    }
    .content{
      /* background-color: #4a529d; */
      width: 100%;
      height: 350px;
      padding: 10px;
      display: flex;
      justify-content: space-around;
    }
    .sub_content1{
      width: 22%;
      height: 360px;
      background-color:#B6A6A8 ;
      border-radius: 7px;
      border: 2px solid wheat;
    }
    .sub_content1 p{
      display: flex;
      justify-content: center;
      color: green;
      font-size: 1rem;
    }
    .sub_content1 button{
      color:white;
      background-color: #4a529d;
      border-radius: 5px;
    }
    .btn_order{
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .sub_content1 img{
      width: 100%;
      height: 270px;
    }
    .end_content{
      display: flex;
     margin-top: 10px;
      justify-content: space-between;
      /* justify-content: space-around; */
      background-color:#814F5E;
      padding: 10px;
    }
   .end_content_left{
    display: flex;
    align-items: center;
    justify-content: space-between;
    
   }
   .end_content_right{
    display: flex;
    align-items: center;
   }
   .end_content_right button{
    background-color: #4a529d;
    color: white;
    height: 30px;
    border-radius: 5px;
   }
   .socalmedia{
     display: flex;
     align-items: center;
     color:whitesmoke;
     justify-content: space-around;
     font-size: 30px;
   }
  
</style>
