<template>
  <div class="container">
    <CThemeProvider>
      <CColorModeProvider>
        <CBox font-family="body" as="main">
          <CReset />
          <nav class="">
            <NuxtLink to="/">Home</NuxtLink>
            <NuxtLink to="/about">About</NuxtLink>
            <Drawer />
          </nav>
          <Nuxt />
        </CBox>
      </CColorModeProvider>
    </CThemeProvider>
  </div>
</template>

<style scoped>
nav {
  display: flex;
  justify-content: space-evenly;
  font-size: large;
  padding-top: 1rem;
}
</style>