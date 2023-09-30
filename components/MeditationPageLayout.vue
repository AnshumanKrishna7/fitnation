<template>
  <div class="bg-williamgreen min-h-screen flex flex-col">
    <NavBar />

    <!-- page Content -->
    <div class="flex-1 pb-12 overflow-hidden">
      <!-- title -->
      <h1 class="text-3xl font-bold font-orelega text-center text-periwinklegrey mb-6 pb-2 py-10">{{ pageTitle }}</h1>

      <!-- paragraph -->
      <div class="font-golox text-golox text-periwinklegrey px-40 py-5">
        <!-- paragraph content -->
        <slot name="paragraph"></slot>
      </div>

      <!-- main -->
      <div class="flex flex-col md:flex-row items-center mt-8 text-periwinklegrey px-20 pl-32">
        <!-- left column (image) -->
        <div class="md:flex-1">
          <img :src="image" alt="Image" class="mx-auto" />
        </div>

        <!-- right column (text) -->
        <div class="md:flex-1 mt-6 md:mt-0 text-center text-periwinklegrey">
          <!-- points -->
          <div class="text-left pl-4 pt-16">
            <ul>
              <slot name="points"></slot>
            </ul>
          </div>
        </div>
      </div>
    </div>

    <Footer class="footer" />
  </div>
</template>

<script>
export default {
  props: {
    pageTitle: String,
    image: String,
    points: Array,
  },
};
</script>

<style scoped>
</style>
