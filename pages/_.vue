<template>
  <article>
    <h1 class="text-6xl font-normal leading-normal mt-0 mb-2 text-emerald-800">
      {{ article.title }}
    </h1>
    <nuxt-content class="text-base font-light leading-relaxed mt-0 mb-4" :document="article" />
  </article>
</template>

<script>
export default {
  async asyncData ({ $content, app, params, error }) {
    const path = `/${params.pathMatch || 'index'}`
    const [article] = await $content({ deep: true }).where({ path }).fetch()

    if (!article) {
      return error({ statusCode: 404, message: 'Article not found' })
    }

    return {
      article
    }
  }
}
</script>