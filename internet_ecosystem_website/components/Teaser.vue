<template>
  <div
    v-editable="blok"
    class="pb-8 mb-6 font-bold text-center">
    <img
      class="h-48 w-full mb-4 object-cover"
      :src="blok.image.filename" />
    <h1 class="text-6xl">{{ blok.headline }}</h1>
    <h4 class="text-3xl">Save the world. Get paid doing it.</h4>
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
