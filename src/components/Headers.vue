<template>
  <div>
    <header class="header">
      <div class="header-top">
      
      <div class="container">

        <div class="header-top__wrapper">
          <div class="top-left">
            <span class="span">Служба поддержки:</span>
            <a href="tel:+998 71 123 45 67" class="link">+998 71 123 45 67</a>
          </div>
          <div class="top-right">
            <div class="select__list">
              <select name="" id="" class="select-class">
                <option value="ru">Russia</option>
                <option value="eng">England</option>
                <option value="uz">Uzbekistan</option>
              </select>
            </div>
          </div>


        </div>
       

      
       
  
        </div>
      </div>

      <div class="header-bottom">
        <div class="container">
          <div class="bottom__block">
            <div class="logo">
              <a href="#"><img src="../assets/img/Layer_1.png" alt="img"></a>
            </div>
            <div class="bottom-list">
              <ul class="bottom-menu">
                <router-link to="Главная" class="router">Главная</router-link>
                <router-link to="" class="router">Умра и Зиерат</router-link>
                <router-link to="" class="router">О нас</router-link>
                <router-link to="" class="router">Блог</router-link>
                <router-link to="" class="router">Связаться с нами</router-link>
              </ul>
            </div>
            <button class="bottom-button">Войти</button>
          </div>
        </div>
      </div>
     
      
    </header>
    <div class="header-end">
      <img src="../assets/img/ekrem-osmanoglu-6OwJWFP6Or8-unsplash 1.png" alt="">
     </div>
   
   
 
    
  </div>
</template>

<script>
export default {

}
</script>

<style>
.header-end{
  padding-bottom: 30px;
  width: 100%;
}

.container{
  width: 1300px;
  margin: 0 auto;
}
.header-top{
  background: #252D24;
  width: 100%;

 
  
}
.header-top__wrapper{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-block: 15px;
  
}
.span{
  color: #c7bbbb;
font-family: Rubik;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;
padding-block: 13px;
/* padding-left: 72px; */
}
.link{
  
color: #FFF;
font-family: Rubik;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;
padding-block: 13px;
padding-left: 10px;
}

.select-class{
    border: none;
    width:85px;
    font-size: 14px;
    font-weight: 17px;
    color: #272A39;
}
.select__list{
    display: flex;
    align-items: center;border: none;
}
.select__list::before{
    content: '';
    width: 18px;
    height: 18px;
    display: block;
    background-image:url('../assets/img/Rectangle 330.png');
    background-position: center;
    background-repeat: no-repeat;
    margin-right: 8px;
}
.select-class option{
  
font-family: Rubik;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: normal;

}
.bottom__block{
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.logo{
  padding-block: 20px;
}
.bottom-list ul{
  width: 550px;
  display: flex;
  justify-content: space-between;
  gap: 32px;
  padding-block: 30px;
}
.router{
  color: var(--black, #3D3E49);
font-family: Inter;
font-size: 16px;
font-style: normal;
font-weight: 500;
line-height: normal;
}
.router:hover{
  color: var(--main, #43B97F);
}
.bottom-button{
  color: #FFF;
font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 500;
line-height: 12px; /* 100% */
padding: 16px;
border-radius: 10px;
background: var(--main, #43B97F);
cursor: pointer;
}
.header-end{
  width: 1440px;


}

</style>