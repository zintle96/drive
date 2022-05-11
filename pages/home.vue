<template>
<section>
 <div id="navigation-bar">
    <nav>
    <img src="../assets/drive/logo.svg"/>
      <ul>
        <li><a href=#>Home</a></li>
        <li><a href=#>Contact</a></li>
        <a href="#" id="menu-icon"></a>
      </ul>
    </nav>
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
  background: url('../assets/drive/hero-home.jpg');
  background-size: cover;
  background-repeat: no-repeat;
}
section {
  width: 100%
}
h1 {
  color: $red;
}
nav {
  overflow: hidden;
  position: absolute;
  top: 0;
  width: 100%;
  z-index: 9999
}
  ul {
    text-align: right;
    list-style-type: none;
    list-style-type: none;
    margin: 0;
    padding: 15px;
  }
    li {
      display: inline;
      font-size: 17px;
    }
      a {
        color: #f2f2f2;
        text-decoration: none;
        padding: 14px;
      }
</style>
