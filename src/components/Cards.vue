<template>
  <section class="cards">
    <div class="container">
        <div class="big-card">
        <div class="card1">
            <img class=" mx-auto " src="../assets/img/img 6.png" alt="">
            <span class="span1">5 дней</span>
            <h2>Специальный пакет услуг для...</h2>
            <h3 class="umra-title">Умра Пакеты / Пользовательские Пакеты </h3>
            <div class="cards-title">
              
                <h3>$1,199</h3>
            <p>На человека</p>

            </div>
            <div class="cards-title">
            <h3>Мекка:</h3>
            <p>5 ночей</p>
            </div>
            <div class="cards-title">
                <h3>Медина:</h3>
            <p>5 ночей</p>

            </div>
            <div class="cards-title">
                <h3>Отправление из:</h3>
            

            </div>
            <div class="cards-title">
                <h3>Стоимость:</h3>
            <p>Авиабилетов не включено</p>
            

            </div>
            <h2 class="sena-title">Цена включает:</h2>

            <ul class="cards-menu">
                <li>Виза</li>
                <li>Размещение в отеле</li>
                <li>Наемный транспорт</li>
                <li>Завтрак</li>
                <li>Налоги</li>
                <li>Руководство</li>
                <li>Исторический тур</li>
            </ul>

            <router-link to="/fayl" class="card-button">Book now</router-link>
           



        </div>
    </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.cards{
    padding-top: 34px;
   
    
}
.big-card{
    display: flex;
    justify-content: space-between;
}

.card1 {
width: 310px;
border-radius: 5px 5px 0px 0px;
border: 1px solid var(--line, #EAEAEC);
background: #FFF;
position: relative;

}

.card1 img{
    padding: 84px 117px;
}
 .span1{
    color: #FFF;
font-family: Rubik;
font-size: 12px;
font-style: normal;
font-weight: 500;
line-height: normal;
padding: 12px;
border-radius: 4px;
background: #FFA800;
position: absolute;
top: 0;
right: 0;
}
.card1 h2{
    color: var(--black, #3D3E49);
font-family: Inter;
font-size: 16px;
font-style: normal;
font-weight: 700;
line-height: 24px; /* 150% */
padding: 20px;
border-top: 1px solid var(--line, #EAEAEC);

}
.umra-title{
    color: var(--main, #43B97F);
font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: 24px; /* 200% */
padding: 12px 40px 12px 20px;
}
.cards-title{
    display: flex;
    
  
}

.cards-title h3{
color: var(--black, #3D3E49);

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 600;
line-height: 24px; /* 200% */
padding-left: 20px;
padding-top: 14px;
}
.cards-title p{
    color: var(--black, #3D3E49);

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: 24px; /* 200% */
padding-left: 20px;
padding-top: 14px;
}
.cards-title p{
    color: var(--black, #3D3E49);

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 400;
line-height: 24px; /* 200% */
}
.cards-title h3:hover{
color: var(--main, #43B97F);
font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 600;
line-height: 24px; /* 200% */
}
.sena-title{
color: var(--black, #3D3E49);

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 600;
line-height: 24px; /* 200% */
padding-block: 20px;
}
.cards-menu{
    display: flex;
    flex-wrap: wrap;
    padding-left: 20px;
    gap: 10px;
}
.cards-menu li{
    color: var(--black, #3D3E49);

font-family: Inter;
font-size: 12px;
font-style: normal;
font-weight: 600;
line-height: 24px; /* 200% */
padding: 6px 8px;
border-radius: 6px;
border: 1px solid var(--line, #EAEAEC);
background: #FAFAFA;

}
.card-button{
    color: #FFF;

font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 600;
line-height: normal;
border-radius: 4px;
background: var(--main, #43B97F);
padding: 18px 88px;
margin: 25px;
border: none;
cursor: pointer;

}

</style>