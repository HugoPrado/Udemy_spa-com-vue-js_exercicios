<template>
  <span>
    <header>
      <nav-bar logo="Social" url="#" cor="green darken-1"></nav-bar>
    </header>

    <main>
      <div class="container">
        <div class="row">
          <grid-vue tamanho="4">

            <card-menu-vue>
              <div class="row valign-wrapper">
                <grid-vue tamanho="4">
                  <img src="https://materializecss.com/images/yuna.jpg" alt="" class="circle responsive-img"> <!-- notice the "circle" class -->
                </grid-vue tamanho="8">
                <grid-vue tamanho="8">
                  <span class="black-text">
                    <h4>Maria Silva</h4>
                    This is a square image. Add the "circle" class to it to make it appear circular.
                  </span>
                  teste
                </grid-vue>
              </div>
            </card-menu-vue>


          </grid-vue>
          <div class="col s8">
            <router-view/>
          </div>
        </div>
      </div>
    </main>

    <footer-vue cor="green darken-1" logo="Social" descricao="teste de descricao" ano="2019">
      <li><a class="grey-text text-lighten-3" href="#!">Link 1</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
      <li><a class="grey-text text-lighten-3" href="#!">Link 4</a></li>
    </footer-vue>



  </span>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'
import FooterVue from '@/components/layouts/FooterVue'
import GridVue from '@/components/layouts/GridVue'
import CardMenuVue from '@/components/layouts/CardMenuVue'
export default {
  name: 'App',
  components:{
    NavBar,
    FooterVue,
    GridVue,
    CardMenuVue
  }
}
</script>

<style>

</style>
