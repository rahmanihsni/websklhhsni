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

    <!-- Main Content -->
    <div id="app" class="container-fluid py-4">
      <div class="row">
        <!-- Header -->
        <div class="pages mb-4">
          <h2 class="text-center text-dark">Berita Terbaru</h2>
        </div>

        <!-- Berita Terbaru Section -->
        <div class="col-md-6 p-3">
          <div class="card">
            <div class="card-header bg-success text-white text-center">
              <h5>Berita</h5>
            </div>
            <div class="card-body">
              <div class="berita-item">
                <!-- First News Item -->
                <div class="d-flex mb-3">
                  <img :src="images.wisuda" alt="Icon" class="icon me-3" />
                  <div>
                    <h6 class="text-danger">Pengumuman Kelulusan Siswa Tahun Pelajaran 2023/2024</h6>
                    <p class="mb-1 text-muted">06-06-2024 - SMKN 4 Tasikmalaya</p>
                  </div>
                </div>
                <hr />
                <!-- Second News Item -->
                <div class="d-flex">
                  <img :src="images.ppdb" alt="Icon" class="icon me-3" />
                  <div>
                    <h6 class="text-danger">Hasil Seleksi PPDB Tahap 2 Tahun 2020</h6>
                    <p class="mb-1 text-muted">08-07-2020 - Taufik Hidayat</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card-footer text-center">
              <button class="btn btn-success">Indeks Berita</button>
            </div>
          </div>
        </div>

        <!-- Pengumuman Terbaru Section -->
        <div class="col-md-6 p-3">
          <div class="card">
            <div class="card-header bg-success text-white text-center">
              <h5>Pengumuman Terbaru</h5>
            </div>
            <div class="card-body">
              <div class="pengumuman-item">
                <!-- First Announcement -->
                <div class="d-flex mb-3">
                  <img :src="images.smk4" alt="Icon" class="icon me-3" />
                  <div>
                    <h6>Konfirmasi Kunjungan Industri 2020</h6>
                    <p class="mb-1 text-muted">03-01-2020 - Kepada Siswa</p>
                  </div>
                </div>
                <hr />
                <!-- Second Announcement -->
                <div class="d-flex">
                  <img :src="images.sample" alt="Icon" class="icon me-3" />
                  <div>
                    <h6>Hasil Gladi Bersih UNBK 2020</h6>
                    <p class="mb-1 text-muted">22-01-2020</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="card-footer text-center">
              <button class="btn btn-success">Indeks Pengumuman</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import wisudaImage from "@/assets/img/wisuda.jpg";
import ppdbImage from "@/assets/img/ppdb.jpg";
import smk4Image from "@/assets/img/smk4.jpg";

export default {
  data() {
    return {
      images: {
        wisuda: wisudaImage,
        ppdb: ppdbImage,
        smk4: smk4Image,
      },
    };
  },
};
</script>

<style scoped>
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}

.icon {
  width: 40px;
  height: 40px;
  border-radius: 50%;
  object-fit: cover;
}

.card {
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
}

.card-header {
  font-size: 18px;
  font-weight: bold;
}

.card-body {
  padding: 15px;
}

.card-footer {
  padding: 10px;
  text-align: center;
}

.btn-success {
  background-color: #28a745;
  color: #fff;
  border: none;
  border-radius: 5px;
  padding: 8px 15px;
  cursor: pointer;
}

.btn-success:hover {
  background-color: #218838;
}
</style>

  




