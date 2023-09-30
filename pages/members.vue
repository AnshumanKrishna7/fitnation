


<!-- soon  -->
<!-- basically after I decide what features to add in it, or when supabase starts supporting auth0, whichever comes first -->





<template>
    <div class="flex flex-col bg-williamgreen min-h-screen">
      <Navbar />
  
      <div class="container mx-auto py-10">
        <h1 class="text-3xl font-semibold text-center text-white mb-6">soon</h1>
  
        <!-- Log Out Button -->
        <button @click="logout" class="bg-red-500 text-white px-4 py-2 rounded-md shadow-md hover:bg-red-600">
          Log Out
        </button>
  
        <!-- Example cards -->
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-4 pt-10">
          <!-- Doomsday (Coming soon) -->
          <div class="bg-white rounded-lg shadow-md p-4">
            <img src="@/assets/images/index/caloriefour.jpg" alt="Daily Calorie Intake" class="w-full h-32 object-cover rounded-md mb-3" />
            <h2 class="text-lg font-semibold text-gray-800">Doomsday</h2>
            <p class="text-gray-600">Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente quas quis molestiae adipisci quae animi quidem eligendi nihil temporibus harum perferendis ullam asperiores suscipit deserunt, aliquid modi distinctio quibusdam magnam!</p>
          </div>
        </div>
      </div>
  
      <Footer class="sticky-footer" />
    </div>
  </template>
  
  <script>
  import Navbar from '~/components/NavBar.vue';
  import { supabase } from '~/supabase.js';
  
  export default {
    components: {
      Navbar,
    },
    methods: {
      async logout() {
        try {
          await supabase.auth.signOut();
          //redirect
          this.$router.push('/auth'); // login page
        } catch (error) {
          console.error('Logout error:', error.message);
        }
      },
    },
  };
  </script>
  
  <style scoped>
  .sticky-footer {
    margin-top: auto;
  }
  </style>
  