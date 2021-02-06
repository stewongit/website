<template>
  <div id="nav">
    <b-navbar toggleable="lg" type="dark" variant="info" class="mt-3 mb-5">
      <b-navbar-brand href="/">machineryApp</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>

        </b-navbar-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
          <b-nav-item to="/maschinensicherheit" active>
            Maschinensicherheit
          </b-nav-item>
          <b-nav-item to="/ce-kennzeichnung" active>
            CE-Kennzeichnung
          </b-nav-item>
          <b-nav-item to="/software" active>
            Software
          </b-nav-item>

          <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>
            <b-dropdown-item href="#">RU</b-dropdown-item>
            <b-dropdown-item href="#">FA</b-dropdown-item>
          </b-nav-item-dropdown>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
