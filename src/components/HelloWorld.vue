<template>
  <div class="navigation">
    <div class="nav_wrapper">
      <img  class="nav_image" src="../assets/medical-logo.svg" alt="">
      <p class="nav_text">Home</p>
      <p class="nav_text">About</p>
      <p class="nav_text" >Care service</p>
      <p class="nav_text" >Contact</p>
    </div>
  </div>

  <div class="container">
    <div class="rounded-gradient-box">

      <div class="half-circle"></div>
      <div class="full-circle"></div>
      <div class="full-circle-two"></div>
      <div class="info_widget">
        <div class="fire">🔥</div>
        <p> #1 best medical center</p>
      </div>
      <div class="main_info">
        <p>The <span>Best Medical</span> <br> and Treatment <br> Cetner for You</p>
      </div>
      <div class="main_info_bottom">
          <p>Connect with our professional doctors who are ready to help you manage <br> your healt with expertise and dedication</p>
      </div>
      <img class="female-png" src="../assets/female-med.png" alt="">
  
    </div>
  </div>

  <div class="cards">
  

       
    <div class="doctor_card">
      <div class="top_card"><img src="../assets/placeholder.svg" alt="">
          <p>Connect with <br> our proffesional <br> doctors</p>

      </div>

          <div class="doctors">
            <img  class="doctor1" src="../assets/doctor1.jpg" alt="">
            <img  class="doctor2" src="../assets/doctor2.jpg" alt="">
            <img  class="doctor3" src="../assets/doctor3.jpg" alt="">
          </div>
      <p class="last-card-text">More than 200+ doctors in service</p>
    </div>

    <div class="next_arrow">
      <img src="../assets/arrow-right.svg" alt="">
    </div>

    <div class="boost_card">
    
      <p>Boost you health to </p>
      <div class="progress-bar">
        <div class="progress-fill"></div>
      </div>
  
  
      <span>101%</span>
    
    </div>

    <div class="next_arrow">
      <img src="../assets/arrow-right.svg" alt="">
    </div>



    <div class="speciality_card">

      <img  class="illustration" src="../assets/smile.svg" >
      <div class="expression">
          <p>90% Satisfying treatment</p>
          <p>90% Happy customer</p>
          <p>100% fast response</p>

      </div>
    </div>


  </div>

  <div class="service_provide">
    <h1>Our Healtcare Service Provide 
    </h1>
  </div>
 

  <div class="service">
    <div class="service_wrapper">

      <div class="online">
        <img   src="../assets/online.svg" >
        <h1>Online Assistance</h1>
        <p>Ease your pain and shoote your joints</p>
      </div>

      <div class="help">
        <img   src="../assets/heart.svg" >
        <h1>Health Status</h1>
        <p>Know the latest information about your health</p>
      </div>


      <div class="result">
        <img   src="../assets/dna.svg" >
        <h1>Test Results</h1>
        <p>View your test results online</p>
      </div>

    </div>
  </div>

  

  

  
 
</template>

<script setup>

</script>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap');


.container {
  display: flex; /* Flexbox для центрирования содержимого */

  justify-content: center; /* Горизонтальное центрирование */

  margin: 0; 
}

.rounded-gradient-box {
  width: 1500px; /* Ширина блока */
  height: 800px; /* Высота блока */
  border-radius: 15px; /* Закругление углов */
  background: linear-gradient(
    to bottom,
    hsla(211, 63%, 81%, 0.42) 0%, 
    /* rgb(253, 215, 210) 100% */
    rgb(252, 237, 230) 100%
  );
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  position: relative; /* Для позиционирования полукруга внутри */
}

.half-circle {
  width: 550px; /* Ширина полукруга */
  height: 275px; /* Высота полукруга */
  background-color: hsla(0, 0%, 100%, 0.49); /* Цвет полукруга */
  border-radius: 500px 500px 0px 0px; /* Закругление только нижних углов */
  position: absolute; /* Абсолютное позиционирование */
  bottom: 0; /* Положение у нижнего края контейнера */
  right: 200px; /* Положение у правого края контейнера */
  border: 3px solid rgb(255, 255, 255);
  border-bottom: none;
}
.full-circle{
  width: 220px; /* Ширина полукруга */
  height: 220px; /* Высота полукруга */
  background-color: hsla(0, 0%, 100%, 0.49); /* Цвет полукруга */
  border-radius: 50%; /* Закругление только нижних углов */
  position: absolute; /* Абсолютное позиционирование */
  bottom: 550px; /* Положение у нижнего края контейнера */
  right: 300px; /* Положение у правого края контейнера */
  border: 3px solid rgb(255, 255, 255);
  border-bottom: none;
}


.full-circle-two{
  width: 170px; /* Ширина полукруга */
  height: 170px; /* Высота полукруга */
  background-color: hsla(0, 0%, 100%, 0.49); /* Цвет полукруга */
  border-radius: 50%; /* Закругление только нижних углов */
  position: absolute; /* Абсолютное позиционирование */
  bottom: 310px; 
  
  right: 0px; /* Положение у правого края контейнера */
  border: 3px solid rgb(255, 255, 255);
  border-bottom: none;
}


.female-png{
  width: 650px;
  position: absolute;
  bottom: 0;
  right: 0;
}

.info_widget{
  margin: 0px 10px 0px 10px;
display: flex;
justify-content: center;
align-items: center;
  font-family: "Raleway", sans-serif;
  font-size:30px;
 background-color: hsla(0, 0%, 100%, 0.49);
 border: 3px solid rgb(255, 255, 255);
 width: 420px;
 border-radius: 50px;
position: absolute;
top:170px;
left:80px;
}

.fire{
padding: 10px 15px 10px 15px;

  margin-right: 17px;
  background-color: rgb(251, 251, 251);
  border-radius: 40px;

}

.main_info{
  font-family: "Raleway", sans-serif;
  font-size:70px;
position: absolute;
top:230px;
left: 90px;


}

span{
  font-weight: 550;
  font-size:80px;
}

.main_info_bottom{
  color: rgb(47, 47, 47);
  font-family: "Raleway", sans-serif;
  font-size:20px;
position: absolute;
top:570px;
left: 90px;
 border-radius: 50px;
}

.doctors img{
border: 2px solid rgb(255, 255, 255);
  width:80px;
  height: 80px;
  object-fit: cover;
  border-radius: 80px;

}

.doctors img:nth-child(2) {
  position: relative; /* Относительное позиционирование */
  left: -25px; /* Смещение для перекрытия */
}

.doctors img:nth-child(3) {
  position: relative; /* Относительное позиционирование */
  left: -50px; /* Смещение для перекрытия */
}

.top_card img{
 
margin: 16px 0px 0px 0px;
  border-radius: 80px;
width: 60px;
height: 60px;
}

.top_card{
  display: flex;
  justify-content: center;
margin-right: 143px;

  
}

.doctor_card  p{
  font-family: "Raleway", sans-serif;
  font-size:20px;
}
.doctor_card{
  background-color: rgb(252, 237, 230);
  border-radius:  30px 0px 0px 30px;
  padding: 0px 30px 0px 30px;
}
.cards{
  display: flex;
  justify-content: center;
  margin-top: 40px;

}


.last-card-text{
  color: rgb(128, 128, 128);
}



.progress-bar {
  width: 240px; /* Полная ширина контейнера */
  height: 20px; /* Высота полосы */
  background-color: #ffffff; /* Цвет фона полосы */
  border-radius: 10px; /* Скругленные углы */
  overflow: hidden; /* Обрезка содержимого */
  position: relative; /* Для позиционирования содержимого внутри */
  transform: scaleY(1.2)
}

.progress-fill {
  width: 60%; /* Процент заполнения полосы, можно менять */
  height: 100%;
  background: linear-gradient(90deg, rgb(88, 157, 121), rgb(6, 252, 72)); /* Градиент от одного цвета к другому */
  transition: width 0.5s ease-in-out; /* Плавная анимация изменения ширины */
}



.boost_card{
  padding: 40px 70px 0px 70px;
  font-family: "Raleway", sans-serif;
  font-size:20px;
  /*background-color: rgb(238, 225, 212);*/
  background-color: rgb(252, 237, 230);
}

.boost_card span{
 font-size: 100px;
 color: rgb(12, 83, 59);
}

.illustration{
  width:300px;
}


.speciality_card{
  display: flex;
  border-radius:  0px 30px 30px 0px;
  justify-content: center;
  align-items: center;
  background-color: rgb(252, 237, 230);
}
.expression{
padding: 10px;

flex-wrap: column;
}

.speciality_card p{
  font-family: "Raleway", sans-serif;
}

.expression p{
font-family: "Raleway", sans-serif;
padding: 10px;
border: 1px solid black;
border-radius: 30px;

}


.next_arrow img{

  margin-top: 14px;
   background-color: rgb(255, 255, 255);
  padding: 20px;
    border-radius: 80px;
  width: 40px;
  height: 40px;
  }



.next_arrow {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: rgb(252, 237, 230);
  }


  .nav_wrapper{

    display: flex;
    justify-content: center;
    align-items: center;
   

  }

  .nav_wrapper , .nav_text, .nav_image{
    margin-right: 145px;
  }

  .nav_wrapper p{
    font-family: "Raleway", sans-serif;
    font-size:25px;
  }


  .service img {
    width: 110px;
    background-color: rgb(244, 243, 243);
    border-radius: 30px;
    padding: 8px;
  }


  .service h1 {

    font-family: "Raleway", sans-serif;
  font-size:35px;
  font-weight: 600;
  }

  .service p {
    font-family: "Raleway", sans-serif;
  font-size:22px;
  color: rgb(171, 171, 171);

  }

  .service_wrapper{
    display: flex;

    justify-content: center;
    gap:120px;
  }

  .online , .help , .result{
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-top: 10px;
  }

  .service{
    margin-top: 60px;
  }

  .service_provide{
    margin-top: 40px;
    font-family: "Raleway", sans-serif;
    font-size:30px;
    display: flex;
    justify-content: center;
  }
</style> 
