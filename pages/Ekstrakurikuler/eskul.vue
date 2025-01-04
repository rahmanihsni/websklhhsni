<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand d-flex align-items-center" href="#">
          <img src="/assets/img/smkn4.jpg" alt="Logo" width="30" height="30" class="me-2">
          SMK NEGERI 4 TASIKMALAYA
        </a>
        <button 
          class="navbar-toggler" 
          type="button" 
          data-bs-toggle="collapse" 
          data-bs-target="#navbarNav" 
          aria-controls="navbarNav" 
          aria-expanded="false" 
          aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <nuxt-link to="/" class="nav-link" aria-current="page">Home</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/profile/sejarah" class="nav-link">Sejarah</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/Ekstrakurikuler/eskul" class="nav-link">Eskul</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/galeri/foto-foto" class="nav-link">Galeri</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link to="/berita/informasi" class="nav-link">Berita</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-lik to="/biodata/biodatakami" class="nav-link">biodata</nuxt-lik>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <div class="container">
      <h4 class="mt-5">Ekstrakurikuler <br> <span class="text-primary">Siswa</span></h4>
      <div class="row m-3 mt-5 justify-content-center">
        <div class="col-6 col-md-4 col-lg-4">
          <div class="card mt-3 bg-light rounded-4">
            <img src="~/assets/img/pmr1.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
            <div class="card-body text-center p-2 mb-3 mt-3">
              <h6>Pmr</h6>
            </div>
          </div>
        </div>

        <div class="col-6 col-md-4 col-lg-4">
          <div class="card mt-3 bg-light rounded-4">
            <img src="~/assets/img/paskibra.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
            <div class="card-body text-center p-2 mb-3 mt-3">
              <h6>Paskibra</h6>
            </div>
          </div>
        </div>

        <div class="col-6 col-md-4 col-lg-4">
          <div class="card mt-3 bg-light rounded-4">
            <img src="~/assets/img/voli1.jpg" class="card-img-top rounded-2 mt-3" alt="img-artikel">
            <div class="card-body text-center p-2 mb-3 mt-3">
              <h6>Voli</h6>
            </div>
          </div>
        </div>

        <div class="col-6 col-md-4 col-lg-4">
          <div class="card mt-3 bg-light rounded-4">
            <img src="~/assets/img/badminton.png" class="card-img-top rounded-2 mt-3" alt="img-artikel">
            <div class="card-body text-center p-2 mb-3 mt-3">
              <h6>Badminton</h6>
            </div>
          </div>
        </div>

        <div class="col-6 col-md-4 col-lg-4">
          <div class="card mt-3 bg-light rounded-4">
            <img src="~/assets/img/futsal.jpg" class="card-img-top rounded-2 mt-3" alt="img-artikel">
            <div class="card-body text-center p-2 mb-3 mt-3">
              <h6>Futsal</h6>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({ title: "Ekstrakurikuler - SMKN 4 Tasikmalaya" });
</script>

<style scoped>
h4, h6, .btn {
  font-family: "Poppins", serif;
}

h4 {
  margin-left: 95px;
}

.card {
  background-color: transparent;
  backdrop-filter: blur(20px);
  border: 2px solid #ffff;
}

.btn {
  font-size: 12px;
  width: 150px;
  border: 2px solid #ffff;
}

.card-img-top {
  width: 150px;
  margin: auto;
}

.text-primary {
  color: #1F60A0 !important;
}

@media only screen and (min-width: 600px) and (max-width: 890px) {
  h4 {
    margin-left: 30px;
  }

  .card-img-top {
    width: 45%;
  }
}

@media only screen and (max-width: 600px) {
  h4 {
    margin-left: 35px;
  }

  .card {
    margin-top: 20px;
  }

  .card-img-top {
    width: 50%;
  }

  h6 {
    font-size: small;
  }
}
</style>




