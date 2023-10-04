<template>
  <div class="list">
    <div class="container">
      <div class="row d-flex">
        <div class="col-md-12">
          <div class="card">
            <div class="card-header">
              <h2>Pesquisar por nome</h2>
            </div>
            <hr />
            <div class="card-body">
              <div class="card card-content">
                <div class="row align-content-lg-between">
                    <div class="col-md-6 d-inline">
                        imagem
                    </div>
                    <div class="col-md-6">
                        Nome
                    </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "ListComponent",
};
</script>
<style>
hr {
  width: 500px;
}
.container {
  margin: 0 50vh;
}
.card {
  background-color: #fff;
  color: #2c3e50;
  border-radius: 0.4rem;
  box-shadow: 0px 0px 5px #00000060;
}
.card-header,
.card-body {
  margin: 0 4rem;
  padding: 1rem 0;
}
</style>
