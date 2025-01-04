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
              <nuxt-link to="/biodata/biodatakami" class="nav-link">biodata</nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    
</div>
</template>

<script setup></script>

<style scoped>
.blockquote-footer {
  font-size: 0.875rem;
}
</style>

