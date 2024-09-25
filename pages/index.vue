<template>
  <div class="min-vh-100 d-flex align-items-center justify-content-center bg-gradient" style="background: linear-gradient(to right, #4299e1, #805ad5);">
    <div class="container text-center p-4">
      <!-- Profile Section -->
      <div class="bg-white shadow-lg rounded p-4 mx-auto" style="max-width: 768px;">
        <!-- Profile Image -->
        <div class="mb-4">
          <img 
            class="rounded-circle mx-auto d-block border border-white" 
            src="@/assets/my_photo.jpg"
            alt="Profile Picture"
            style="width: 128px; height: 128px;" 
          />
        </div>

        <!-- Profile Information -->
        <h1 class="h3 font-weight-bold text-dark mb-2">Halo! Saya Muhammad Azka Giberneo!</h1>
        <p class="text-muted mb-4">Umur 19 Tahun | Mahasiswa Teknologi Informasi di Universitas Brawijaya</p>

        <!-- Contact Information -->
        <div class="text-muted mb-4">
          <p><strong>Email:</strong> azkagiberneo@gmail.com</p>
          <p><strong>Telepon:</strong> +62 813-9844-2550</p>
          <p><strong>Alamat:</strong> Bekasi, Jawa Barat, Indonesia</p>
        </div>

        <!-- Social Media Links -->
        <div class="d-flex justify-content-center mb-4">
          <a href="https://www.instagram.com/azkagiberneo07?igsh=MTJocnk0ZDY5djZpdQ==" class="text-dark mx-2">
            <img src="@/assets/icons8-instagram-50.png">
          </a>
          <a href="https://www.linkedin.com/in/muhammad-azka-giberneo-95914b32b" class="text-dark mx-2">
            <img src="@/assets/icons8-linkedin-50.png">
          </a>
          <a href="https://github.com/zkagbrno" class="text-dark mx-2">
            <img src="@/assets/icons8-github-50.png">
          </a>
        </div>

        <!-- About Me -->
        <h2 class="h4 font-weight-bold text-dark mb-3">Tentang Saya</h2>
        <p class="text-muted mb-4">
          Saya adalah seorang mahasiswa Teknologi Informasi yang masih berproses dan ingin memperdalam pengetahuan tentang Teknologi dan bidang terkait lainnya.
        </p>

        <!-- Skills Section -->
        <h2 class="h4 font-weight-bold text-dark mb-3">Keterampilan</h2>
        <div class="row text-left text-muted mb-4">
          <div class="col-6">
            <ul class="list-unstyled">
              <li>✔️ HTML, CSS, PHP, JavaScript</li>
              <li>✔️ Vue.js</li>
              <li>✔️ Tailwind CSS, Bootstrap</li>
            </ul>
          </div>
          <div class="col-6">
            <ul class="list-unstyled">
              <li>✔️ Node.js</li>
              <li>✔️ MySQL</li>
              <li>✔️ Git, GitHub</li>
            </ul>
          </div>
        </div>

        <!-- Education Section -->
        <h2 class="h4 font-weight-bold text-dark mb-3">Pendidikan</h2>
        <div class="text-muted mb-3">
          <p><strong>D3 Teknologi Informasi</strong> - Universitas Brawijaya</p>
          <p>2023 - Sekarang</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HomePage",
}
</script>

<style scoped>
a {
  transition: color 0.3s ease;
}
</style>
