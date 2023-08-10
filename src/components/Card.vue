<template>
  <section class="rek">
    <div class="container">
        <div class="title-blok">
            <h2>Рекомендуемые</h2>
            <button>Посмотреть все</button>
        </div>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
.title-blok{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 70px;
}
.title-blok h2{
color: var(--black, #3D3E49);
font-family: Inter;
font-size: 24px;
font-style: normal;
font-weight: 600;
line-height: normal;
}
.title-blok button{
 color: var(--main, #43B97F);
font-family: Inter;
font-size: 14px;
font-style: normal;
font-weight: 600;
line-height: normal;
padding: 16px 24px;
border-radius: 10px;
border: 1px solid var(--line, #b4b4c5);
background: #FFF;
cursor: pointer;

}

</style>