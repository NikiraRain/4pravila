<template>
  <div class="content-wrap">
    <div class="container">
      <div class="modal-result-top">
        <h2 class="modal-result-h2">Спасибо за вашу заявку!</h2>
        <p>Наш менеджер свяжется с вами в течение 30 минут.</p>
        <p class="modal-result-p">Мы работаем с понедельника по пятницу с 9 до 19 часов. Если вы оставите заявку в выходные или в нерабочее время, вы будете первыми кому мы позвоним в ближайший рабочий день :)</p>
        <p>До встречи!</p>
      </div>
      <div class="modal-result-bottom" style="margin-bottom: 20px;">
        <picture>
          <!-- <source class="round" srcset="~/assets/img/circle.png" media="(min-width: 480px)" alt="banner.name"> -->
          <img class="round" src='~/assets/img/circle-m.png'>
        </picture>
        <!-- <img class="round" src='~/assets/img/circle.png'> -->
        <div class="team-hero">
          <div class="team-name">Марат Даутов</div>
          <div class="team-description">Основатель и руководитель компании</div>
        </div>
      </div>
      <a href="/" class="back">На главную</a>
    </div>
  </div>
</template>

<script>
import AppHeaderMenuMain from '~/components/AppHeaderMenuMain.vue'
import AppHeader from '~/components/AppHeader.vue'
import AppHeaderTop from '~/components/AppHeaderTop.vue'
import AppSlider from '~/components/AppSlider.vue'
import AppZachem from '~/components/AppZachem.vue'
import AppPlus from '~/components/AppPlus.vue'
//import AppFiveShagov from '~/components/AppFiveShagov.vue'
import AppOpinions from '~/components/AppOpinions.vue'
import AppContacts from '~/components/AppContacts.vue'
// import AppFooter from '~/components/AppFooter.vue'
import AppPravila from '~/components/AppPravila.vue'
import AppMenuRight from '~/components/AppMenuRight.vue'
import AppMarat from '~/components/AppMarat.vue'
import AppProblems from '~/components/AppProblems.vue'
import AppProgress from '~/components/AppProgress.vue'
import AppSale from '~/components/AppSale.vue'
import AppOt from '~/components/AppOt.vue'
import AppBanki from '~/components/AppBanki.vue'
import AppWork from '~/components/AppWork.vue'
import AppCallActions from '~/components/AppCallActions.vue'
import AppTypeService from '~/components/AppTypeService.vue'
import AppSwiper from '~/components/AppSwiper.vue'
import AppCompare from '~/components/AppCompare.vue'
import AppVideoSwiper from '~/components/AppVideoSwiper.vue';

// import Vue from 'vue'
// import Router from 'vue-router'
// import VueYandexMetrika from 'vue-yandex-metrika'                               

// const router = new VueRouter({...}) // your routes

export default {
  data() {
    return {
        initialactive: 0,
        initial: 0
    }
  },
  components: {
    AppHeaderMenuMain,
    AppHeader,
    AppHeaderTop,
    AppSlider,
    AppZachem,
    AppPlus,
   // AppFiveShagov,
    AppOpinions,
    AppContacts,
    // AppFooter,
    AppPravila,
    AppMenuRight,
    AppMarat,
    AppProblems,
    AppProgress,
    AppSale,
    AppOt,
    AppBanki,
    AppWork,
    AppCallActions,
    AppTypeService,
    AppSwiper,
    AppCompare,
    AppVideoSwiper
  },
  methods: {
      activedTabRule: function (index) {
        // this.initialactive = index - 1
        this.initial = index - 1
        // console.log('qwe=', this.qwe.initialactive)
    }
  }
}
</script>

<style>
/* 
@import url('https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700,800');
@import url('https://fonts.googleapis.com/css?family=Roboto:100,300,400,500,700');
@import url('https://fonts.googleapis.com/css?family=Arimo');
@import url('https://fonts.googleapis.com/css?family=Roboto+Condensed');
@import url('https://fonts.googleapis.com/css?family=EB+Garamond');

@import url('https://fonts.googleapis.com/css?family=Yanone+Kaffeesatz:300,400,600,700,800'); */
/* @font-face {
  font-family: 'Raleway-Bold';
  src: url('~/static/fonts/Raleway-Bold.ttf') format('truetype');
}
@font-face {
  font-family: 'Raleway-Light';
  src: url('~/static/fonts/Raleway-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'Raleway-Medium';
  src: url('~/static/fonts/Raleway-Medium.ttf') format('truetype');
} */

/* @font-face {
  font-family: 'AvantGardeGothicC';
  src: url('~/static/fonts/AVG65.pfm') format('PFM');
  src: url('~/static/fonts/AVG65.PFB') format('PFB');
} */
.back{
  text-decoration: none;
  align-items: center;
  border: 1px solid rgba(129, 34, 25, 1);
  padding: 5px 20px;
  color: rgba(129, 34, 25, 1);
  cursor: pointer;
  text-align: center;
}

.link {
    position: relative;
    top: -60px;
}
body {
  font-family:  'roboto', 'EB Garamond','Yanone Kaffeesatz', 'Roboto Condensed', 'Arimo', 'Open Sans', Source Sans Pro, Arial;
  font-size: 16px;
}
.test {
  height: 500px;
  background-color: rgb(180, 180, 180)
}
.act {
  display: none;
}

.container{
  max-width: 1080px;
  margin: 20px auto;
  text-align: center;
}

@media (min-width: 1024px) {
  .act {
    display: block;
  }
}
</style>
