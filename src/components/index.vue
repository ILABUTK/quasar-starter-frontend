<template>
  <div class="layout-view layout-padding">
    <div class="branding">
      <div class="splash"></div>
      <div class="tagline">Quasar Starter</div>
      <hr>
      <p>Quasar App with Laravel Backend API</p>
    </div>
    <div class="row no-gutter">
      <button class="primary full-width" v-link="{name: 'login'}">
        Login
      </button>
    </div>
    <br>
    <div class="row no-gutter">
      <button class="primary full-width" v-link="{name: 'register'}">
        Register
      </button>
    </div>
  </div>
</template>

<style lang="stylus">
  @import "../themes/app.variables.styl"

  @media only screen and (min-width: 601px){
    .layout-padding{
      margin 0 auto
    }
  }

  .splash {
    background url(../statics/quasar-logo.png) no-repeat center center
    margin 0 auto
    height 300px
    width 300px
  }

  .branding {
    width 80%
    margin 0 auto
    text-align center
    max-width 350px
    padding-bottom 10px
  }

  .branding .tagline {
    color $primary
    font-size 35px
    line-height 30px
  }

  .branding p {
    color $primary
    font-size 18px
  }
  .branding hr {
    max-width 50px
    border-color $primary
    border-width 2px
    border-style solid
    margin 30px auto
  }
</style>

<script>
export default {
  data () {
    return {

    }
  }
}
</script>
