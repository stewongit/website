<template>
  <div>
    <!-- ======= Top Bar ======= -->


    <!-- ======= Header ======= -->
    <b-container fluid class="bg-info px-0 px-sm-2">
      <b-container>
        <navigation></navigation>
      </b-container>
    </b-container>

      <!-- ======= Main ======= -->
      <b-container>
        <Nuxt />
      </b-container>

  </div>

</template>

<script>
import navigation from "~/components/header/navigation";

export default {
  components: [
    navigation,
  ]
}
</script>

<style>
html {
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}


.wrapper {
  position: sticky;
  top: 0;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}

</style>
