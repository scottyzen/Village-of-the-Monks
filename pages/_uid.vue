<template>
  <div>
    <app-masthead :featuredImage="post.featured_image.url"></app-masthead>
    <div class="container">
      <div class="mb-8">
        <h1 class="title">
          <small>{{ post.sub_title }}</small>
          {{ post.title[0].text }}
        </h1>
        <slices class="max-w-2xl mx-auto" :slices="post.body" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: this.post.title[0].text + " | Village of the Monks",
      meta: [
        {
          hid: "description",
          name: "description",
          content: this.post.discription,
        },
        {
          hid: "keywords",
          name: "keywords",
          content: this.post.keywords,
        },
      ],
    };
  },
  async asyncData({ $prismic, params, error }) {
    try {
      const post = (await $prismic.api.getByUID("page", params.uid)).data;
      return { post };
    } catch (e) {
      error({ statusCode: 404, message: "Page not found" });
    }
  },
};
</script>
