<template>
  <div id="app">
    <div id="nav">
      <b-navbar toggleable="md" type="dark" variant="info">
      
        <b-container>
          
          <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
          <b-navbar-brand href="#">Navegador</b-navbar-brand>

          <b-collapse id="nav-collapse" is-nav>
            <b-navbar-nav>
              <b-nav-item :to="{name: 'Home'}" exact>Home</b-nav-item>
              <b-nav-item :to="{name: 'About'}">Propuesta Educativa</b-nav-item>
              <b-nav-item :to="{name: 'sedes'}">Sedes</b-nav-item>
            </b-navbar-nav>
          </b-collapse>
            
        </b-container>

      </b-navbar>
      
      <b-container>
        <router-view/>
      </b-container>

    </div>
  </div>
</template>
