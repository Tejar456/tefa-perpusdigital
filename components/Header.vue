<template>
    <div class="header">
    <div class="h-img">
      <img src="~/assets/img/LOGO-SMK4.png">
    </div>
    <div class="h-text">
      <div class="t-judul">
        <p>PERPUS DIGITAL</p>
        <p>SMK NEGERI 4 TASIKMALAYA</p>
      </div>
      <p>Jl.Depok, Sukamenak, Purbaratu 46196</p>
    </div>
  </div>
</template>

<style scoped>

  .header {
    display: flex;
    align-items: center;
    width: 100%;
    height: 150px;
    background-color: #265CB5;
    color: #fff;
  }

  .h-img {
    margin-left: 25px;
  }

  .h-img > img{
    width: 80%;
  }

  .h-text {
    margin-left: -15px;
    line-height: 10px;
 ;
  }

  .t-judul {
    font-size: 20px;
    font-weight: 500;
  }
</style>