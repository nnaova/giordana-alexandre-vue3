<script setup>

</script>
<template>
    <!-- Navbar Start -->
    <nav class="navbar navbar-expand-lg bg-white navbar-light shadow-sm py-3 py-lg-0 px-3 px-lg-0">
      <router-link to="/" class="navbar-brand ms-lg-5">
        <h1 class="m-0 text-uppercase text-dark"><i class="bi bi-droplet-half fs-1 text-primary me-3"></i>BOTW MONSTERs
        </h1>
      </router-link>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarCollapse">
        <div class="navbar-nav ms-auto py-0 mx-4">
          <router-link to="/" class="nav-item nav-link active">Home</router-link>
          <router-link to="/monsterList" class="nav-item nav-link">Monsters</router-link>
        </div>
      </div>
    </nav>
    <!-- Navbar End -->
</template>