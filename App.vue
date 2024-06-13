

<template>
    <div class="wrapper">
           <!-- шапка -->
            <Header/>

            <main class="page">	
              <section class="artistic">
                <div class="artistic__container _container">
                  <div class="artistic__block">
                    <h1 class="artistic__titel">artistic</h1>
                    <p class="artistic__text">Бережный и аккуратный ремонт для вашей ванной</p>
                  </div>            

                </div>
              </section>

              <section class="why">
                <div class="why__border">
                  <div class="why__container _container">
                    <h3 class="why__subtitel">Почему выбирают нас </h3>
                    <h2 class="why__titel">Мы работаем только в Санкт-Петербурге. Благодаря этому поддерживаем качество и не распылемся</h2>
                    <div class="why__grid">
                      <div class="why__item">
                        <h4 class="why__subItem">Гарантия</h4>
                        <p class="why__text">Реальная гарантия <br><span>60 месяцев</span></p>
                      </div>
                      <div class="why__item">
                        <h4 class="why__subItem">Выгода</h4>
                        <p class="why__text">Ремонт ванной 
                          <br> <span>от 27 000 руб.</span></p>
                      </div>
                      <div class="why__item">
                        <h4 class="why__subItem">Скорость</h4>
                        <p class="why__text">Ванна под ключ 
                          <br> за <span>12 дней</span></p>
                      </div>
                      <div class="why__item">
                        <h4 class="why__subItem">Опыт</h4>
                        <p class="why__text">Успешно трудимся
                          <br> начиная с <span>2007 года</span></p>
                      </div>
                    </div>
                  <button class="why__btn">Оставить заявку</button>
                  </div>
                </div>
              </section>

              <section class="calculate">
                <div class="calculate__container _container">
                  <h2 class="calculate__titel">Расчитайте стоимость ремонта санузла быстро
                    и легко со скидкой <span>5 000 рублей</span></h2>
                  <div class="calculate__block">
                    <div class="calculate__item-img">
                      <img src="./img/pic1.jpg" alt="img">
                    </div>
                    <div class="calculate__block-Form">
                      <form action="" class="calculate__form">
                        <div class="calculate__item">
                          <label  for="square" class="calculate__label">Площадь санузла</label>
                          <input type="text" class="calculate__inp" name="square" id="square" placeholder="м2" autocomplete="off">
                        </div>
                        <div class="calculate__item">
                          <label  for="name" class="calculate__label">Имя</label>
                          <input type="text" class="calculate__inp" name="name" id="name" placeholder="Ваше имя" autocomplete="off">
                        </div>
                        <div class="calculate__item">
                          <label  for="phone" class="calculate__label">Телефон</label>
                          <input type="text" class="calculate__inp" name="phone" id="phone" placeholder="+7" autocomplete="off">
                        </div>
                        <button class="calculate__btn" type="button">Рассчитать стоимость</button>
                      </form>
                    </div>
                  </div>
                </div>
              </section>

              <section class="kinds">
                <div class="kinds__container _container">
                  <div class="kinds__block-titel">
                    <h2 class="kinds__titel title">Виды работ</h2>
                  </div>                  
                  <div class="kinds__grid">
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Ремонт санузлов под ключ</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Закупка и доставка доваров</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Демонтажные работы</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Разводка электропроводки</p>
                    </div>

                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Укладки плитки на стены и пол</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Разводка труб</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Отделка стен</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Выравнивание полов</p>
                    </div>

                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Отделка потолка</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Дизайн проект</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Установка бытовой техника</p>
                    </div>
                    <div class="kinds__item">
                      <img src="./img/im1.jpg" alt="img">
                      <p class="kinds__text">Установка сантехники</p>
                    </div>
                  </div>
                </div>
              </section>
            </main>

            <!-- Подвал -->
           <Footer/>
        </div>
</template>

<script>
//стили
  import './scss/style.scss'
  import './scss/header.scss'
  import './scss/home.scss'
  import './scss/footer.scss'
/* ===================================== */
import Header from './components/Header.vue';
import Footer from './components/Footer.vue'

  export default  {
    components: {
        Header,
        Footer  
    },
    data(){
        return {
          isActive: false
        }
      },
  
  }
</script>

<style scoped>
 
</style>
