
<template>
    <div class="container">
      <div class="row">
        <div class="text-left col-xs-12 col-sm-12 col-md-12 col-lg-12">
          <h1>Dashboards</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-11 col-sm-11 col-md-11 col-lg-11">
          <div class="btn-group" role="group">
            <button class="btn btn-default" v-for="botao in botoes">{{botao}}</button>
            <button class="btn btn-success">+</button>
          </div>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-1 col-lg-1" >
          <span class="glyphicon glyphicon-cog" aria-hidden="true"></span>
        </div>
      </div>
      <!-- layout -->
      <div class="row" v-if="layout == 0">
        <div class="addChart col-xs-3 col-sm-3 col-md-3 col-lg-3">
            <span>+ Add Chart</span>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-1 col-lg-1"></div>
        <div class="addChart col-xs-3 col-sm-3 col-md-3 col-lg-3">
            <span>+ Add Chart</span>
        </div>
        <div class="col-xs-1 col-sm-1 col-md-1 col-lg-1"></div>
        <div class="addChart col-xs-3 col-sm-3 col-md-3 col-lg-3">
            <span>+ Add Chart</span>
        </div>
      </div>
      <div class="row" v-if="layout == 1">
        <div class="col-xs-2 col-sm-2 col-md-2 col-lg-2"></div>
        <div class="addChart col-xs-3 col-sm-3 col-md-3 col-lg-3">
            <span>+ Add Chart</span>
        </div>
        <div class="col-xs-2 col-sm-2 col-md-2 col-lg-2"></div>
        <div class="addChart col-xs-3 col-sm-3 col-md-3 col-lg-3">
            <span>+ Add Chart</span>
        </div>
        <div class="col-xs-2 col-sm-2 col-md-2 col-lg-2"></div>
      </div>
      <div class="row" v-if="layout == 2">
        layout 2
      </div>
      <div class="row" v-if="layout == 3">
        layout 3
      </div>
      <div class="row" v-if="layout == 4">
        layout 4
      </div>
    </div>
</template>

<script>
    export default{
      props: {
        layout: {
          type: Number,
          required: true
        }
      },
      data() {
        return{
          botoes: ["Visao Geral", "vendas", "botao", "a"]
        }
      }
    }
</script>

<style scoped>
.addChart{
  padding-top: 15%;
  padding-bottom: 15%;
  margin: 0% 1% 0% 1%;
  border-style: dashed;
  border-radius: 5px;
  border-color: gray;
}
.row {
  margin-bottom: 2%;
}
</style>
