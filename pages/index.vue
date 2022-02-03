<template>
  <h1>Welcome to my first Nuxt App</h1>
</template>

<script>
export default {
  name: 'IndexPage',
  head() {
    return {
      title: 'Applications Nuxt Index',
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Nuxt application'
        }
      ],
      htmlAttrs: {
        lang: 'en'
      }
    }
  }
}
</script>
