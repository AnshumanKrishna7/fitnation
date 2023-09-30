<template>
  <div class="flex flex-col bg-williamgreen min-h-screen">
    <Navbar />

    <div class="container mx-auto py-10">
      <h1 class="text-3xl font-bold font-orelega text-center text-periwinklegrey pb-2">Calorie Tracking</h1>
      <h2 class="text-2xl font-bold font-orelega text-center text-periwinklegrey mb-6 pb-2">[The feature is coming soon.. to stay updated, sign up today!]</h2>

      <!-- calorie cards -->
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
        
        <!-- calorie Tracking Card 1 (Daily Intake) -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/calories/caloriefour.jpg" alt="Daily Calorie Intake" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Daily Calorie Intake</h2>
          <p class="text-gray-600">Track your daily calorie consumption to meet your nutritional goals.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
        </div>

        <!-- calorie Tracking Card 2 (Food Diary) -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/calories/caloriethree.jpg" alt="Food Diary" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Food Diary</h2>
          <p class="text-gray-600">Keep a record of your meals and snacks to monitor your calorie intake.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
        </div>

        <!-- calorie Tracking Card 3 (Calorie Burn) -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/calories/caloriefour.jpg" alt="Calorie Burn" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Calorie Burn</h2>
          <p class="text-gray-600">Track the calories you burn through exercise and daily activities.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
        </div>

        <!-- calorie Tracking Card 4 (Nutritional Goals) -->
        <div class="bg-greysuit rounded-lg shadow-md p-4">
          <img src="@/assets/images/calories/caloriethree.jpg" alt="Nutritional Goals" class="w-full h-32 object-cover rounded-md mb-3" />
          <h2 class="text-lg font-semibold text-gray-800">Nutritional Goals</h2>
          <p class="text-gray-600">Set and monitor your nutritional goals for a balanced diet.</p>
          <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
        </div>

      </div>
    </div>

    <Footer class="sticky-footer" />
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
