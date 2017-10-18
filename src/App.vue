<template>
  <div id="app">
    <div style="height: 0; width: 0; position: absolute; visibility: hidden"><!-- inject:svg --><!-- endinject --></div>
<div id="frame">

    <aside class="left del-right">
      <a href="/">
        <div id="logo">
          <svg class="icon">
            <use xlink:href="#Logo-icon"></use>
          </svg>
        </div>
      </a>

      <nav>
        <div class="item" data-index="1">
          <svg class="icon link" >
            <use xlink:href="#bar-chart-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="2">
          <a href="/produtos.html"></a>
          <svg class="icon link">
            <use xlink:href="#clothes-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="3">
          <svg class="icon link">
            <use xlink:href="#label-icon"></use>
          </svg>
        </div>
        <div class="item" data-index="4">
          <svg class="icon link">
            <use xlink:href="#info-icon"></use>
          </svg>
        </div>
      </nav>
    </aside>
    <section id="beside" class="">
      <header class="main del-bottom">
        <svg class="icon">
          <use xlink:href="#shop-icon"></use>
        </svg>
        <h1>
          Loja ModaJá
        </h1>
        <div id="user-account">
          <button id="logout-btn" type="button" class="custom">

            <svg class="icon">
              <use xlink:href="#logout-icon"></use>
            </svg>

            <div role="label" for="logout-btn">Logout</div>
          </button>
          <div style="background-image:url(http://www.hellomaps.net/images/joomla-maps/faceuser1.jpg)" class="avatar"></div>
        </div>
      </header>
      <div class="d-flex flex-row">
        <section id="content">

        </section>
        <aside class="right del-left">

          <header>
            <h2>Bem-vindo!</h2>
            <h3>04 de Outubro</h3>
          </header>

          <article class="sidebar-summary-item">
            <h4>Central de Suporte</h4>
            <p>Nenhum chamado aberto</p>
            <a href="">Abrir Chamado
              <svg class="icon text">
                <use xlink:href="#forward-arrow-icon"></use>
              </svg>
            </a>
          </article>
          <article class="sidebar-summary-item">
            <h4>Método de Pagamento</h4>
            <p>Mastercard xxxx6677</p>
            <a href="">Alterar
              <svg class="icon text">
                <use xlink:href="#forward-arrow-icon"></use>
              </svg>
            </a>
          </article>
        </aside>
      </div>
    </section>

  </div>

</div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  @import "assets/sass/painel.scss"
</style>
