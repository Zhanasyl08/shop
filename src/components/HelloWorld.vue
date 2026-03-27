<template>
  <div class="inform">
    <div id="title">
      <button onclick="window.open('./components/about.vue')">О нас
      </button>

<!--Адреса все дела-->
    </div>
    <div id="loc">
      <button class="loc">Адреса</button>
      <br>
      <br>
      <br>

      <!--Будет опции чтобы можно было выбирать-->
      <div class="catalog">
        <div id="menu">
          <button class="man">Мужчинам</button>
          <button class="woman">Женщинам</button>
          <button class="baby">Детям</button>
          <button class="sport">Спорт</button>
          <button class="classic">Классика</button>
        </div>

      </div>


<!--Поисковик здесь будет жи есть если че-->

      <div class="search">
        <div id="searcher">  <!--Вот здесь-->
        <input type="search">

<!--Фильтр айдишка-->
          <div id="filt">

            <!--Здесь будет фильтр которые можно будет установить-->
          <button class="filt"></button>

        </div>
      </div>

      <div class="end">
        <div id="end">
          <!--Здесь будут иконки соц сетей-->   >
          <button class="endless">Адреса</button>
           <button class="endless">Помощь</button>
            <button class="endless">Доставка</button>
             <button class="endless">Обмен и возврат</button>
              <button class="endless">Контакты</button>
               <button class="endless">Размеры</button>
                <button class="endless">Оплата</button>
                 <button class="endless">Пользовательское соглашение</button>
                  <button class="endless">Политика конфеденциальности</button>
        </div>
        </div>
        <div class="icons">
          <div id="main">
            <!--Здесь просто переход на главную страницу-->
             </div>



            <div id="account">
              <!--Здесь вход в аккаунт-->


            </div>

            <div id="cart">
              <!--Здесь будет корзина если он зайдет сюда то он перейдет на вкладку регистрации-->

            </div>




        </div>


        <!--Очень долгая тема кнш но здесь будет все кроссовки их описания и тд и тп посмотрим как будем делать-->
        <div class="shoes">
          <div id="sneakers">


</div>
        </div>
      </div>
    </div>
  </div>

</template>

<style>
body {
  background-color: black;
  margin: 0;
  padding: 20px;
}

#title {
  text-align: left;
  font-size: 16px;
}

#loc {
  text-align: right;
  margin-bottom: 16px;
}

#menu {
  color: aliceblue;
  text-align: left;
}

#searcher { 
  text-align: center;
}

#filt {
  color: aliceblue;
}

#end {
  text-align: end;

  color: aliceblue;

  }
  #main {
    text-align: center;
    position: fixed;
    color: grey;

  }



</style>


<!--Здесь будет код vue-->