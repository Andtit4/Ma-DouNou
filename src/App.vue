<template>
  <nav>
    <div class="navbarContainer">
      <div class="navbarItems">
        <li>
          <router-link to="/about">A propos</router-link>
        </li>
        <li>
          <router-link to="/command">Commandes</router-link> 
        </li>
          <li>
            <router-link to="/product">Produits</router-link> 
          </li>
          <!-- <li>
            <form>
              <input type="text" placeholder="Rechercher" />
            </form>
          </li> -->
      </div>
    </div>
  </nav>
  <router-view/>
</template>

<style>
* {
  background-color: #f5f6fa;
  font-family: 'Poppins', sans-serif;
}

ul {
  position: fixed;
  top: 0;
  list-style-type: none;
  padding: 0;
  margin: 0;
  overflow: hidden;
  width: 60px;
}

li {
  padding: 21px;
  float: right;
  display: inline;
}

li a {
  display: block;
  text-align: center;
  text-decoration: none;
  color: #000
}
li a:hover{
  background-color: transparent;
  text-decoration: underline;
  text-underline-position: under;
  color: #5E4B56
}

nav a.router-link-exact-active {
  color: #5E4B56;
  text-decoration: underline;
  text-underline-position: under
}
.vnb .button-red {
    background: #FF3B30;
}
.vnb .button-red:hover {
    background: #FC0D00;
}
</style>
