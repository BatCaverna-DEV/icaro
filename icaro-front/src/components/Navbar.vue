<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Icaro</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <RouterLink class="nav-link" to="/home">Home</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/home">Sobre</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/home">Pesquisadores</RouterLink>
          </li>
          <li class="nav-item">
            <RouterLink class="nav-link" to="/home">Publicações</RouterLink>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>

</style>