

<template>
     <header class="header">
                <div class="header__container _container">
                  <div class="header__flex">
                    <div class="header__icon">
                      <a href="" class="header__iconLink">
                        <img src="../img/icon.svg" alt="icon">
                      </a>
                    </div>
                    <div class="header__menu" :class="{ active: isActive }">
                      <nav class="header__body">
                        <ul class="header__list">
                          <li class="header__item"><a href="" class="header__link">Главная</a></li>
                          <li class="header__item"><a href="" class="header__link">Цены</a></li>
                          <li class="header__item"><a href="" class="header__link">Калькулятор ремонта</a></li>
                          <li class="header__item"><a href="" class="header__link">Примеры работ</a></li>
                          <li class="header__item"><a href="" class="header__link">Новости</a></li>
                          <li class="header__item"><a href="" class="header__link">Отзывы</a></li>
                        </ul>
                      </nav>
                    </div>
                    <div class="header__number">
                        <p>+8(950) 019-19-19</p>
                        <button @click="clickBtn()" ref="button" type="button" class="header__burger"><span></span></button>
                    </div>
                      <!-- <button @click="clickBtn()" ref="button" type="button" class="header__burger"><span></span></button> -->
                  </div>
                </div>
     </header>
</template>

<script>

  export default  {
    data() {
    return {
      isActive: false
    }
  },
 
      methods: {
        clickBtn(e){
          const btn = this.$refs.button;
          btn.classList.toggle('active');
          this.isActive = !this.isActive;
        }
    }
  }
</script>

<style scoped>
 
</style>
