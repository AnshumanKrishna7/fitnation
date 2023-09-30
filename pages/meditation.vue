<template>
  
  <div class="flex flex-col bg-williamgreen min-h-screen">
    <Navbar />

    <div class="container mx-auto py-10">
      <h1 class="text-3xl font-bold font-orelega text-center text-periwinklegrey mb-6 pb-2">Meditation Classes</h1>

      <!-- Meditation Cards -->
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">

        <!-- Meditation Card 1 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationonetwo.jpg" alt="Meditation Class 1" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Getting Started with Meditation</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page1">Details</Button>
        </div>

        <!-- Meditation Card 2 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationtwo.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Peaceful Meditation Environment</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page2">Details</Button>
        </div>

        <!-- Meditation Card 3 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationthree.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">The Foundation</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page3">Details</Button>
        </div>

        <!-- Meditation Card 4 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationfour.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Phase 1: Mindfulness of Breath</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page4">Details</Button>
        </div>

        <!-- Meditation Card 5 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationfive.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Phase 2: Body Scan</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page5">Details</Button>
        </div>

        <!-- Meditation Card 6 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationsix.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Phase 3: Loving-Kindness Meditation</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page6">Details</Button>
        </div>

        <!-- Meditation Card 7 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationseven.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Phase 4: Visualization</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page7">Details</Button>
        </div>

        <!-- Meditation Card 8 -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/meditation/meditationeight.jpg" alt="Meditation Class 2" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Wrapping Up Your Meditation Practice</h2>
          <p class="text-gray-600">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/meditations/page8">Details</Button>
        </div>

      </div>
    </div>

    <Footer class="sticky-footer"  />
  </div>
</template>

<script>
import Navbar from '~/components/NavBar.vue';

export default {
  components: {
    Navbar,
  },
};
</script>

<style scoped>
.sticky-footer {
  margin-top: auto;
}
</style>
