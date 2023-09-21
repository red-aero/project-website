<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
<header id="header" class="fixed-top header-transparent">
    <div class="container d-flex align-items-center justify-content-between position-relative">

      <div class="logo">
        <!--<h1 class="text-"><RouterLink to="/"><span>FOOOTBALL</span></RouterLink></h1>-->
        <RouterLink to="/"><img src="src/assets/img/logo.png" alt="bundesliga logo" class="img-fluid"></RouterLink>
      </div>

      <nav id="navbar" class="navbar">
        <ul>
          <li><RouterLink class="nav-link scrollto active" to="/">Home</RouterLink></li>
          <li><a class="nav-link scrollto" href="#about">About Us</a></li>
          <li><a class="nav-link scrollto" href="#Position">Positions</a></li>
          <li><a class="nav-link scrollto" href="#gallery">Gallery</a></li>
          <li><RouterLink class="nav-link scrollto" to="/overview">Overview</RouterLink></li>
          <li class="dropdown"><a href="#"><span>Drop Down</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">Drop Down 1</a></li>
              <li class="dropdown"><a href="#"><span>Deep Drop Down</span> <i class="bi bi-chevron-right"></i></a>
                <ul>
                  <li><a href="#">Deep Drop Down 1</a></li>
                  <li><a href="#">Deep Drop Down 2</a></li>
                  <li><a href="#">Deep Drop Down 3</a></li>
                  <li><a href="#">Deep Drop Down 4</a></li>
                  <li><a href="#">Deep Drop Down 5</a></li>
                </ul>
              </li>
              <li><a href="#">Drop Down 2</a></li>
              <li><a href="#">Drop Down 3</a></li>
              <li><a href="#">Drop Down 4</a></li>
            </ul>
          </li>
          <li><RouterLink class="nav-link scrollto" to="/About">Contact</RouterLink></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header><!-- End Header -->

  <RouterView />
</template>

<style scoped>
</style>
