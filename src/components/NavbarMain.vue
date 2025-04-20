<template>
  <nav class="navbar navbar-expand-lg fixed-top">
    <div class="container">
      <a class="navbar-brand" href="#">
        <img src="../assets/logo.png" alt="" />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div
        class="collapse navbar-collapse justify-content-center"
        id="navbarSupportedContent"
      >
        <!-- Tambahkan class 'mx-auto' di sini agar menu di tengah -->
        <ul class="navbar-nav mx-auto mb-2 mb-lg-0 gap-5">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Tour</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Descinations</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Activites</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pages</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>

        <!-- Form tetap di sisi kanan -->
        <button type="button" class="btn btn-outline-success">Logn in</button>
      </div>
    </div>
  </nav>
</template>

<script>
// masih kosong
</script>

<style scoped>
.navbar {
  background-color: #fef8f5;
}
</style>
