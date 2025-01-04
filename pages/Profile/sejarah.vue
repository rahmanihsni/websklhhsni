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
      
      <div class="container py-5">
          <!-- Sejarah Section -->
          <section id="sejarah" class="mb-5">
              <h1 class="text-center fw-bold mb-4">SEJARAH SMK NEGERI 4 TASIKMALAYA</h1>
              <div class="image-container text-center">
                  <img src="assets/img/sejarah.png" alt="Sejarah" class="img-fluid rounded shadow" />
              </div>
              <p class="text-justify mt-4 description">
                  Sejalan dengan Program Pemerintah di bidang pendidikan Menengah Kejuruan pada saat itu, yakni pemerataan akses, ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu Kota Tasikmalaya. Terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK maka beberapa tokoh masyarakat, unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada pemerintah Kota Tasikmalaya dan Pemerintah Provinsi Jawa Barat agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
              </p>
          </section>

          <!-- Identitas Sekolah Section -->
          <section id="identitas" class="mb-5">
              <h1 class="text-center fw-bold mb-3">Identitas Sekolah</h1>
              <div class="text-center mb-4">
                  <img src="assets/img/logo.png" alt="Logo Sekolah" class="logo-img" />
              </div>
              <table class="table table-bordered table-striped">
                  <tbody>
                      <tr><td><strong>NPSN</strong></td><td>20276063</td></tr>
                      <tr><td><strong>Tanggal SK Pendirian</strong></td><td>26 Juli 1955</td></tr>
                      <tr><td><strong>Nama Sekolah</strong></td><td>SMK Negeri 4 Tasikmalaya</td></tr>
                      <tr><td><strong>Alamat</strong></td><td>Jl. Depok</td></tr>
                      <tr><td><strong>Kelurahan</strong></td><td>Sukamenak</td></tr>
                      <tr><td><strong>Kecamatan</strong></td><td>Purbaratu</td></tr>
                      <tr><td><strong>Kota</strong></td><td>Tasikmalaya</td></tr>
                      <tr><td><strong>Kode POS</strong></td><td>46196</td></tr>
                      <tr><td><strong>Provinsi</strong></td><td>Jawa Barat</td></tr>
                      <tr><td><strong>Telepon/Fax</strong></td><td>+622651312059</td></tr>
                      <tr><td><strong>Email</strong></td><td>info@smkn4tsm.sch.id</td></tr>
                  </tbody>
              </table>
          </section>

          <!-- Visi Misi Section -->
          <section id="visi-misi" class="mb-5">
              <h1 class="text-center fw-bold mb-3">Visi Misi</h1>
              <div class="content mt-4">
                  <h2 class="fw-bold">Visi</h2>
                  <p>TERWUJUDNYA LULUSAN YANG CERDAS, AKTIF, KOMPETITIF, ADAPTIF, DAN PRODUKTIF BERLANDASKAN IMAN DAN TAKWA</p>
                  <h2 class="fw-bold mt-4">Misi</h2>
                  <ol>
                      <li>Menyiapkan Sumber Daya Manusia yang cerdas dan kompeten baik hardskill maupun softskill.</li>
                      <li>Meningkatkan dan mengembangkan aktifitas serta kreatifitas seluruh warga sekolah dalam berbagai kegiatan positif.</li>
                      <li>Mewujudkan manajemen pengelolaan yang efektif, efesien, transparan, akuntabel dan layanan prima.</li>
                      <li>Menumbuhkan dan mengembangkan potensi dan kemampuan Sumber Daya Manusia yang berdaya saing tinggi melalui berbagai kegiatan akademik maupun non-akademik.</li>
                      <li>Menyelenggarakan berbagai program kegiatan dalam upaya meningkatkan Sumber Daya Manusia yang mampu menyesuaikan dengan perkembangan.</li>
                      <li>Mengembangkan sarana prasarana dan lingkungan sekolah yang menyenangkan sebagai wadah menumbuhkembangkan daya kreasi dan inovasi untuk menghasilkan produk teknologi tepat guna.</li>
                      <li>Membangun jiwa wirausaha yang handal melalui pembelajaran Teaching Factory (TEFA) dan Kelas Industri.</li>
                      <li>Menjalin dan mengembangkan kemitraan dengan Industri dan Dunia Kerja (IDUKA) serta lembaga lainnya yang relevan.</li>
                      <li>Menanamkan dan membudayakan sikap dan perilaku yang baik pada aktivitas di sekolah maupun dalam kehidupan sehari-hari.</li>
                  </ol>
              </div>
          </section>

          <!-- Jurusan Section -->
          <section id="jurusan" class="mb-5">
              <h1 class="text-center fw-bold mb-3">Jurusan di SMKN 4 Tasikmalaya</h1>
              <div class="galeri">
                  <div class="galeri-item">
                      <img src="assets/img/pplg.png" alt="PPLG" class="galeri-img" />
                      <p class="galeri-caption">PPLG</p>
                  </div>
                  <div class="galeri-item">
                      <img src="assets/img/tkjt.png" alt="TJKT" class="galeri-img" />
                      <p class="galeri-caption">TJKT</p>
                  </div>
                  <div class="galeri-item">
                      <img src="assets/img/tbsm.png" alt="TSM" class="galeri-img" />
                      <p class="galeri-caption">TSM</p>
                  </div>
                  <div class="galeri-item">
                      <img src="assets/img/dkv.png" alt="DKV" class="galeri-img" />
                      <p class="galeri-caption">DKV</p>
                  </div>
                  <div class="galeri-item">
                      <img src="assets/img/toi.png" alt="TOI" class="galeri-img" />
                      <p class="galeri-caption">TOI</p>
                  </div>
              </div>
          </section>
      </div>
  </div>
</template>

<style scoped>
.galeri {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
  gap: 20px;
  justify-items: center;
  align-items: center;
}

.galeri-item {
  text-align: center;
}

.galeri-img {
  width: 100px;
  height: 100px;
  object-fit: cover; /* Menjaga proporsi gambar */
  border-radius: 10px; /* Opsional, untuk sudut melengkung */
}

.galeri-caption {
  margin-top: 10px;
  font-size: 1rem;
  font-weight: bold;
}
</style>
