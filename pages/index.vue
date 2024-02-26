<template>
  <div class="container-fluid">
    <div class="row my-5 d-flex justify-content-around">

      <div class="col-lg-6 kartu">
        <nuxt-link to="/pengunjung/tambah">
          <div class="card bg-pengunjung rounded-5">
            <div class="card-body">
              <h2>Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
      
      <div class="col-lg-6 kartu">
        <nuxt-link to="/buku">
          <div class="card bg-buku rounded-5">
            <div class="card-body">
              <h2>Pengunjung</h2>
            </div>
          </div>
        </nuxt-link>
      </div>
  </div>
    <div class="row my-5 d-flex justify-content-around">

      <div class="col-lg-6 kartu">
          <div class="card c2 rounded-5">
            <div class="card-body text">
              <h1>3</h1>
              <h1>Pengunjung</h1>
            </div>
          </div>
      </div>

      <div class="col-lg-6 kartu">
          <div class="card c2 rounded-5">
            <div class="card-body text">
              <h1>180</h1>
              <h1>Buku</h1>
            </div>
          </div>
      </div>

    </div>
  </div>
</template>

<style scoped>
.card {
  height: 250px;
  box-shadow: 1px 1px 10px #3333;
}

.card.bg-pengunjung {
  background-image: url('../assets/img/bg-home-kunjungan.jpeg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.card.bg-buku {
  background-image: url('../assets/img/bg-home-cari-buku.jpg');
  background-repeat: no-repeat;
  background-position: center center;
  background-size: cover;
}

.kartu {
  width: 40%;
}

.c2 {
  border: 1px solid #000;
}

.text {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>