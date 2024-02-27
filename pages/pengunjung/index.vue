<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12 p-5">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <div class="my-3">
          <input type="search" class="form-control form-cntrol-lg rounded-4" placeholder="Filter">
        </div>
        <div class="my-3 text-muted">Menampilkan 1 dari 1</div>
        <table class="table table-bordered">
          <thead>
            <tr>
              <td>NO</td>
              <td>NAMA</td>
              <td>KEANGGOTAAN</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1</td>
              <td>Tejar Maulana</td>
              <td>Siswa</td>
              <td>26 Februari 2024</td>
              <td>Baca Buku</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <nuxt-link to="/pengunjung/tambah">
      <button type="submit" class="btn ms-3 btn-lg">KEMBALI</button>
    </nuxt-link>
  </div>
</template>

<style scoped>
button {
  border: 1px solid #000;
  background-color: #3270d2;
  color: #fff;
  position: absolute;
  bottom: 30px;
  right: 30px;
  border-radius: 20px;
}

button:hover {
  border: 1px solid #000;
  background-color: #fff;
  color: #3270d2;
}
</style>