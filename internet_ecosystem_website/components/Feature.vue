<template>
  <div v-editable="blok"
    class="py-2 text-center">
    <nuxt-link
      class="hover:underline"
      style="color:#7bb062"
      to="/">
      <center>
      <a href=blok.link>
      <img
      class="h-48 w-48 mb-4 object-cover"
      :src="blok.icon.filename" />
      </a>  
      </center>
    <h1 class="text-lg">{{ blok.name }}</h1>
    <p class="text-gray-600">
      {{ blok.description }}
    </p>
    </nuxt-link>




  </div>
</template>

<script>
export default {
  props: {
    blok: {
      type: Object,
      required: true
    }
  }
}
</script>
