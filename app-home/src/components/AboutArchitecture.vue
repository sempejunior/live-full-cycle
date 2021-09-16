
<template>
  <el-carousel :autoplay="false" arrow="always" height="350px" style="max-width: 1300px;margin: auto;">
   <el-carousel-item>
      <img class ="item__image"
        src="../images/monolito.png"
        alt=""
      />
    </el-carousel-item>
    <el-carousel-item>
      <img class ="item__image"
        src="../images/micro_frontends_architecture.png"
        alt=""
      />
    </el-carousel-item>
    <el-carousel-item >
      <img class ="item__image"
        src="../images/pipelineMicroFrontEnd.png"
        alt=""
      />
    </el-carousel-item>
  </el-carousel>

  <el-row :gutter="12" style="margin-top:40px;">
      <el-col :span="8">
          <el-card shadow="always" class ="card-boad">
            <template #header>
              <div class="card-header">
                <i class="el-icon-circle-plus"></i>
                <span style="margin-left: 20px">Benefícios</span>
              </div>
            </template>
              <ul style="align-items: center;">
                <li>Independência de frameworks</li>
                <li>Códigos menores e mais fáceis de serem testados</li>
                <li>Frontends com menores responsabilidades</li>
                <li>Deploys independentes</li>
                <li>Maior escalabilidade</li>
                <li>Uma forma de evoluir frontends legados</li>
                <li>Possibilidade de upgrade, update e reescrita de pequenas partes</li>
                <li>Menor acoplamento e maior coesão</li>
            </ul>  
          </el-card>
        </el-col>
      <el-col :span="8">
        <el-card shadow="hover" class = "card-boad">
          <template #header>
            <div class="card-header">
              <i class="el-icon-remove"></i>
              <span style="margin-left: 20px">Problemas</span>
            </div>
          </template>
            <ul>
              <li>Tamanho do payload</li>
              <li>Complexidade</li>
              <li>Responsabilidade compartilhada</li>
              <li>Testes E2E</li>
              <li>Manter a coerência de estilos.</li>
            </ul>  
          </el-card>
      </el-col>
      <el-col :span="8">
        <el-card shadow="never" class = "card-boad"> <template #header>
            <div class="card-header">
              <i class="el-icon-s-platform"></i>
              <span style="margin-left: 20px">Tipos de implementação</span>
            </div>
          </template>
          <ul>
            <li>Server Side</li>
            <li>Iframes</li>
            <li>Frameworks Javascript</li>
            <li>Web components</li>
          </ul>  
        </el-card>
    </el-col>
  </el-row>
</template>

<style>
  .el-carousel__item h3 {
    color: #475669;
    font-size: 14px;
    opacity: 0.75;
    line-height: 200px;
    margin: 0;
  }

  .el-carousel__item:nth-child(2n) {
    background-color: #99a9bf;
  }

  .el-carousel__item:nth-child(2n + 1) {
    background-color: #d3dce6;
  }
  .card-header{
    font-size: 25px;
  }
  .image {
    width: 80%;
    display: block;
    margin-left: auto;
    margin-right: auto;
    align-items: center;
  }

  .card-boad{
    background-color: #3C415C;
    color: #FFFFFF;
    font-family:courier;
  }
  .el-card__header{
    background-color: #000000;
    color:#FFFFFF;
  }

  .item__image {
    width: 100%;
    height: 100%;
    object-fit: fill
  }
</style>
