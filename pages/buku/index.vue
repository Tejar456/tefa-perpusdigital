<template>
  <div class="container-fluid p-5">
    <div class="row">
      <div class="col-lg-12 -flex justify-content-around">
        <div class="my-3">
          <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?">
        </div>
        <div class="my-3 text-muted">Menampilkan 4 dari 4</div>
        <div class="row">
          <div class="col-lg-2">
            <div class="card mb-3">
              <nuxt-link to="/buku/detail">
                <div class="card-body">
                  <img src="~/assets/img/cover1.jpg" class="cover">
                </div>
              </nuxt-link>
            </div>
          </div>
          <div class="col-lg-2">
            <div class="card mb-3">
              <div class="card-body">
                <img src="~/assets/img/cover1.jpg" class="cover">
              </div>
            </div>
          </div>
          <div class="col-lg-2">
            <div class="card mb-3">
              <div class="card-body">
                <img src="~/assets/img/cover1.jpg" class="cover">
              </div>
            </div>
          </div> 
          <div class="col-lg-2">
            <div class="card mb-3">
              <div class="card-body">
                <img src="~/assets/img/cover1.jpg" class="cover">
              </div>
            </div>
          </div>
          <div class="col-lg-2">
            <div class="card mb-3">
              <div class="card-body">
                <img src="~/assets/img/cover1.jpg" class="cover">
              </div>
            </div>
          </div> 
          <div class="col-lg-2">
            <div class="card mb-3">
              <div class="card-body">
                <img src="~/assets/img/cover1.jpg" class="cover">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <nuxt-link to="/">
      <button type="submit" class="btn ms-3 btn-lg">KEMBALI</button>
    </nuxt-link>
  </div>
</template>

<style scoped>
.card-body > img {
  width: 200px;
}

.cover {
  height: 100%;
  object-fit: cover;
  object-position: 0 30;
  border: none;
}
.card {
  border: none;
}

button {
  border: 1px solid #000;
  background-color: #265CB5;
  color: #fff;
  position: fixed;
  bottom: 30px;
  right: 30px;
  border-radius: 20px;
}

button:hover {
  border: 1px solid #000;
  background-color: #fff;
  color: #265CB5;
}
</style>