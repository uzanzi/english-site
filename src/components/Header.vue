<script setup>

</script>

<template>
  <nav class="navbar">
    <div>
      <img src="/assets/img/xavatar.png" alt="xavatar" width="75" height="75">
      <p>Ugo Zanzi</p>
    </div>
    <div class="nav-links" ref="navLinks">
      <ul>
        <li><router-link to="profil">Profile</router-link></li>

        <li><router-link to="portfolio">Portfolio</router-link></li>

        <li><router-link to="blog">Blog</router-link></li>

        <li><router-link to="cv">Cv</router-link></li>
      </ul>
    </div>
    <img src="/assets/img/menu-btn.png" alt="menu" class="menu" ref="menu">
  </nav>
</template>
<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  padding-left: 5px;
  padding-right: 5px;
  background: black;

  div {
    display: flex;
    align-items: center;
    font-size: 32px;
    color: white;
  }

  div:nth-child(2) a {
    padding: 5px 30px;
  }

  .menu {
    position: absolute;
    top: 32px;
    right: 50px;
    width: 35px;
    display: none;
  }
}

.nav-links ul {
  display: flex;
  list-style-type: none;

  a {
    text-decoration: none;
    color: white;
    font-size: 24px;
    padding: 0;
  }
}

@media screen and (max-width: 919px) {
  .navbar {
    padding: 0;
  }

  .menu {
    display: block !important;
  }

  .nav-links {
    position: absolute;
    background-color: rgb(255, 255, 255, 0.20);
    width: 100%;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    backdrop-filter: blur(7px);
    margin-left: -100%;
    transition: all 0.3s ease;

    ul {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding-left: 0;

      li {
        margin: 25px 0;
        font-size: 1.2em;

        a {
          color: black;
        }
      }
    }
  }

  .mobile-menu {
    margin-left: 0;
  }
}
</style>
<script>
export default {
  name: "Header",
  mounted() {
    const menu = this.$refs.menu;
    const navLinks = this.$refs.navLinks;
    menu.addEventListener('click', () => {
      navLinks.classList.toggle('mobile-menu')
    })
  }
}
</script>