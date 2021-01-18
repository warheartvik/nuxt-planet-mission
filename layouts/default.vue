<template>
  <div>
    <nav>
            <nuxt-link to="/">Home</nuxt-link>
            <nuxt-link to="/about">About</nuxt-link>
    </nav>
    <Nuxt />
  </div>
</template>
<script>
export default {
  head: {
    title: 'Nuxt Mission',
    htmlAttrs: {
      lang: 'en'
    },
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: 'A Mission to explore Jamstack using Nuxt.' }
    ],
    link: [
      { rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }
    ]
  },
}
</script>