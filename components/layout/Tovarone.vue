<template>
  <div class="tovar">
 <ul class="cards-list">
  
    <li class="card">
      <img class="img" src="https://i.ibb.co/VcMnh56k/a2bf38dd0504dc8e247858957380e37f-1.png" alt="Ранец" width="212" height="212">
      <div class="star"> <IconStar></IconStar>
</div>
      <p class="text">Ранец Berlingo Expert "Hockey league" 37*28*16см, 2 отделения, 1 карман, анатомическая спинка</p>
      <div class="scidca">-25%</div>
      <div class="stoimost">
      <p class="zena">2575,85 ₽</p>
      <p class="scidca2">2920,50 ₽</p>
      </div>
      <button type="button" name="popup-button" class="sravnenie">Сравнить</button>
      <button type="button" name="popup-button" class="basket">В Корзину</button>

    </li>  
 
   
  </ul>
</div>
  
   
  
  </template>
 
  <style>
  .tovar {
    background-color: white;
    height: 437px;
    margin: 10px 0px 20px 0px;

  }
.cards-list {
  margin: 0 auto;
  display: grid;
  max-width:60%;
  grid-template-columns: repeat(2, minmax(256px, 256px));
  grid-column-gap:60px;
  grid-row-gap: 20px;
  height: 445px;
  border: 1px solid white;
  justify-content:center;
  
 }
.card {
  position: relative;
  list-style: none;
  border: 1px solid #F6F6F6;
  height: 431px;
  padding-left: 10px;
  padding-top: 10px;
  
  
}
.scidca {
  position: absolute;
  top: 10px;
  left: 10px;
  color: #E0001B;
font-weight: 700;
border: 1px solid #F6F6F6;
border-radius: 2px;
border-radius: 2px;
}
.img {
  display: block;     
  margin: 0 auto;

}
.star {

  margin-top: 10px;
}
.text {
  
}
.stoimost {
 display: flex;
  gap: 10px;
}
.zena {
  width: 70px;
  font-weight: 700;
  
}
.scidca2 {
  
  color: #D2D2D1;
  text-decoration: line-through;
}
.sravnenie {
width: 110px;
height: 36px;
border-color: #F6F6F6;
background-color: #F6F6F6;
} 

.basket {
  margin-left: 10px;
width: 110px;
height: 36px;
background: #E0001B;
border-radius: 2px; 
color: white ;
}
</style>