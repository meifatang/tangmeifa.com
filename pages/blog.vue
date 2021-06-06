<template>
    <div class="">
      <ul>
        <li v-for="item in articles" :key="item.title">
          <a v-bind:href="item.path">{{ item.title }}</a>
        </li>
      </ul>
    </div>
</template>

<script>
export default {
  async asyncData ({ $content, app, params, error }) {
    //const path = `/${params.pathMatch || 'index'}`
    const articles = await $content({ deep: true }).only(['title']).fetch()

    console.log(articles)

    if (!articles) {
      return error({ statusCode: 404, message: 'Article not found' })
    }

    return {
      articles
    }
  }
}
</script>