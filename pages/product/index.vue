<template>
  <div>
    <app-masthead
      featuredImage="https://res.cloudinary.com/odriscolls/image/upload/q_auto,f_auto/v1584304556/brandon-header-large.jpg"
    ></app-masthead>
    <div class="container">
      <div class="flex">
        <div class="w-full p-12">
          <!-- <article v-for="{ uid, data, id } in posts" :key="id">
            <NuxtLink
              class="text-xl text-gray-700 font-secondary hover:text-green-500"
              :to="`/product/${uid}`"
              >{{ data.title[0].text }}</NuxtLink
            >
          </article> -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  async asyncData({ $prismic }) {
    const posts = await $prismic.api.query(
      $prismic.predicates.at("document.type", "product")
    );
    return {
      posts: posts.results,
    };
  },
  head: {
    title: "Blog",
  },
};
</script>
