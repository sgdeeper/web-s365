<template>
　<div>
    <v-fade-transition>
      <Nuxt />
    </v-fade-transition>
  </div>
</template>

<style>
html {
  font-family: 'Lato', 'M PLUS Rounded 1c', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #4BBD6A;
  color: #fff;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.bg-sub {
  background-color: #318053;
}

button {
  font-size: 2.4rem;
  border-radius: 4px;
  display: inline-block;
  text-decoration: none;
  min-width: 120px;
  padding: 10px 30px;
  margin: 20px auto;
  opacity: 1;
}

button:hover {
  opacity: 0.7;
  transition: 0.3s;
}

.button {
  background-color: #318053;
}

.button--accent {
  color: #272343;
  font-weight: bold;
  background-color: #F9EB49;
}


</style>
