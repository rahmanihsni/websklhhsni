<template>
  <div>
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

      <div class="container-fluid py-5">
          <div class="col-lg-12 mb-4">
              <h5 class="text-center text-white rounded-3 p-2 m-3 bg-dark">
                  GURU <b>SMKN 4 TASIKMALAYA</b>
              </h5>
          </div>
          <section class="gallery">
              <div class="galeri-item">
                  <img src="/assets/img/guru1.jpg" alt="guru" class="galeri-image" />
                  <p class="gallery-caption">Taufik Hidayat</p>
              </div>
              <div class="galeri-item">
                  <img src="/assets/img/guru2.jpg" alt="guru" class="galeri-image" />
                  <p class="gallery-caption">Zul Hilmi</p>
              </div>
              <div class="galeri-item">
                  <img src="/assets/img/guru3.jpg" alt="guru" class="galeri-image" />
                  <p class="gallery-caption">Lisye Diana</p>
              </div>
              <div class="galeri-item">
                  <img src="/assets/img/guru4.jpg" alt="guru" class="galeri-image" />
                  <p class="gallery-caption">Suminar</p>
              </div>
              <div class="galeri-item">
                  <img src="/assets/img/guru5.jpg" alt="guru" class="galeri-image" />
                  <p class="gallery-caption">Joy</p>
              </div>
          </section>
      </div>
  </div>
</template>

<style scoped>
.gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;
  margin: 20px 0;
}

.galeri-item {
  flex: 0 1 calc(20% - 20px); /* 5 items per row, minus gap */
  background-color: #f9f9f9;
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 10px;
  transition: transform 0.3s;
  text-align: center;
}

.galeri-item:hover {
  transform: scale(1.05);
}

.galeri-image {
  width: 100%; /* Ensures images take up the full container width */
  height: auto; /* Maintain aspect ratio */
  border-radius: 8px;
}

.gallery-caption {
  color: #000; /* Black text for better visibility */
  margin-top: 10px;
  font-size: 14px;
  font-weight: bold;
}

h5 {
  background-color: #343a40; /* Added dark background */
  color: #fff; /* White text for visibility */
  font-weight: bold;
}
</style>
