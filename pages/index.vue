<template>
  <section>
<nav class="navbar navbar-expand-lg navbar-light">
  <div class="container-fluid">
    <a class="navbar-brand"><img src="../assets/drive/logo.svg"/></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#" style="color: #FF0050;">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" style="color: #FFFFFF;">Contact Us</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
  </div>

  <div class="content">
    <img src="../assets/drive/hero-home.jpg" class="d-block w-100"/>
    <div class="content-caption d-md-block">
      <p class="goose">Goosebumps</p>
      <p class="come">Come standard</p>
      <p class="para">Discover the benefits of DRIVECLUB Trade-in and get a free vehicle evaluation</p>
  </div>
    </div>


</section>
</template>

<script>
export default {

}
</script>

<style lang='scss'>
@import '~assets/scss/main';
* {
  font-family: 'Proxima';
  color: white;
}

.navbar {
  position: absolute;
  top: 0;
  width: 100%;
  z-index: 9999
}
.navbar-brand {
  top: 36px;
left: 120px;
width: 148px;
height: 16px;
background: 0% 0% no-repeat padding-box;
opacity: 1;
}
.nav-link {
  text-align: center;
font: normal normal 300 16px/22px Poppins;
letter-spacing: 0.64px;
color: #FFFFFF;
opacity: 0.87;
text-transform: uppercase;
top: 32px;
left: 1223px;
width: 106px;
height: 23px;
}

.content {
  height: 50% !important;
}

.content-caption {
   position: absolute;
   top: 172px;
left: 140px;
width: 714px;
height: 91px;
text-align: left;
color: #FFFFFF;
}
.content-caption .goose{
top: 172px;
width: 714px;
height: 91px;
font: normal normal 800 80px/75px Proxima Nova;
letter-spacing: 1.6px;
opacity: 0.87;
text-transform: uppercase;
}
.content-caption .come {
top: 259px;
width: 360px;
height: 45px;
font: normal normal 800 40px/38px Proxima Nova;
letter-spacing: 1.6px;
opacity: 0.87;
text-transform: uppercase;
}
.content-caption .para {
top: 332px;
width: 466px;
height: 45px;
font: normal normal 300 16px/22px Poppins;
letter-spacing: 0.32px;
opacity: 0.6;
}
</style>
