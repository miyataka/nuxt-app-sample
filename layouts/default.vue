<template>
  <div>
    <nav class="navbar bg-primary justify-content-between flex-nowrap flex-row">
      <div class="container-fluid">
        <div>here is Logo</div>
        <ul class="nav nav-tabs">
          <li>
            <nuxt-link
              to="/"
              class="nav-link">
              <i class="fa fa-2x fa-home text-white" />
              <span class="text-white">Home</span>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link
              to="/page1"
              class="nav-link">
              <i class="fas fa-2x fa-coffee text-white" />
              <span class="text-white">page1</span>
            </nuxt-link>
          </li>
          <li>
            <nuxt-link
              to="/page2"
              class="nav-link">
              <i class="fas fa-2x fa-moon text-white" />
              <span class="text-white">page2</span>
            </nuxt-link>
          </li>
        </ul>
      </div>
    </nav>
    <nuxt/>
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
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

ul {
  flex-grow: 1;
}
li {
  flex-grow: 1;
}
</style>
