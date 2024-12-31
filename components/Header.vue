<template>
    <div class="container">
       <nav class="navbar navbar-expand-lg ">
            <div class="row ">
                <div class="col-lg-3">
                    <img src="/assets/img/logo.png" alt="">
                </div>
                <div class="col-lg-7 col-md-7 col-sm-8 col-8 text-light">
                    <h4>SMK Negeri 4 Tasikmalaya</h4>
                    <address>Jl Depok Kel. Sukamenak Kec. Purbaratu 
                    Kota Tasikmalaya</address>
                </div>
            </div>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse px-5" id="navbarNavDropdown">
        <ul class="navbar-nav mx-5 pt-2">
          <nuxt-link to="/">
            <li class="nav-item">
              <h6>BERANDA</h6>
            </li>
          </nuxt-link>
          <li class="nav-item mx-3">
            <nuxt-link to="/frofil/">
              <h6>PROFILE</h6>
            </nuxt-link>
          </li>
          <li class="nav-item mx-3">
            <nuxt-link to="/eskul/">
              <h6>EKSTRAKULIKULER</h6>
            </nuxt-link>
          </li>
          <li class="nav-item mx-3">
            <nuxt-link to="/kurikulum/konsentrasiKeahlian">
              <h6>KOMPETENSI KEAHLIAN</h6>
            </nuxt-link>
          </li>
        </ul>
    </div>
    </nav>
</div>


</template>

<style scope>
.container{

    background-color: #135975;
    max-width: 100%;
}

.navbar {
    background-color: #135975;
}

img{
  width: 90px; 
}

h6 {
    color: white;
    text-decoration: none;

}

</style>