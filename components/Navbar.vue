<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
        <nuxt-link to="/" class="navbar-brand"> 
             Navbar
        </nuxt-link>
      <div class="collapse navbar-collapse" >
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <nuxt-link exact no-prefetch="" active-class="active" to="/" class="nav-link">
                Home
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" to="/about" class="nav-link">
                About
            </nuxt-link>
          </li>
          <li class="nav-item">
            <nuxt-link active-class="active" to="/users" class="nav-link">
                Users
            </nuxt-link>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
