<template>
  <div class="flex flex-col bg-williamgreen min-h-screen">
    <NavBar />

<div class="container mx-auto py-10">
  <h1 class="text-3xl font-bold font-orelega text-center text-periwinklegrey pb-2">Workout Programs</h1>
  <h2 class="text-2xl font-bold font-orelega text-center text-periwinklegrey">[The feature is coming soon.. to stay updated, sign up today!]</h2>
  <h2 class="text-l font-orelega text-center text-periwinklegrey mb-6 pb-2">[checkout /meditation to keep yourself calm till we roll out the feature :D]</h2>

  <!-- Workout Cards -->
  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-8">
    
    <!-- Workout Card 1 (Chest {All}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/chest.jpg" alt="Chest Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Chest {All}</h2>
      <p class="text-gray-600">A comprehensive chest workout to strengthen your chest muscles.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 2 (Arms {Biceps}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/arms.jpg" alt="Back Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Arms {Biceps}</h2>
      <p class="text-gray-600">Focus on building your biceps with targeted arm exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 3 (Arms {Triceps}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/triceps.jpg" alt="Legs Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Arms {Triceps}</h2>
      <p class="text-gray-600">Strengthen your triceps with effective arm workouts.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 4 (Arms {Forearms}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/forearms.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Arms {Forearms}</h2>
      <p class="text-gray-600">Focus on forearm development with targeted exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 5 (Core {Abs}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/abs.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Core {Abs}</h2>
      <p class="text-gray-600">Achieve strong and defined abs with these core exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 6 (Core {Obliques}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/obliques.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Core {Obliques}</h2>
      <p class="text-gray-600">Target your obliques for a balanced core with these exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 7 (Back {Traps & mid}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/midbacklats.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Back {Traps & mid}</h2>
      <p class="text-gray-600">Strengthen your mid-back and traps with these back exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 8 (Back {Lats & more}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/latpull.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Back {Lats & more}</h2>
      <p class="text-gray-600">Work on your lats and more with these effective back workouts.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 9 (Shoulders {All}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/shoulder.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Shoulders {All}</h2>
      <p class="text-gray-600">Comprehensive shoulder workout for impressive shoulder muscles.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>
    
    <!-- Workout Card 10 (Legs {Quads}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/legpress.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Legs {Quads}</h2>
      <p class="text-gray-600">Strengthen your quads with targeted leg exercises.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>
    
    <!-- Workout Card 11 (Legs {Hamstrings}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/hams.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Legs {Hamstrings}</h2>
      <p class="text-gray-600">Build strong hamstrings with these leg day workouts.</p>
      <Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>

    <!-- Workout Card 12 (Legs {Calves}) -->
    <div class="bg-greysuit rounded-lg shadow-md p-4">
      <img src="@/assets/images/musclegroup/calves.jpg" alt="Shoulders Workout" class="w-full h-32 object-cover rounded-md mb-3" />
      <h2 class="text-lg font-semibold text-tiber">Legs {Calves}</h2>
      <p class="text-gray-600">Focus on your calf muscles with these targeted leg exercises.</p><Button class="mt-4 bg-tiber text-greysuit py-2 px-4 rounded hover:bg-black hover:text-white" href="/auth">Details</Button>
    </div>
    
  </div>
</div>

    <!-- <Footer class="sticky-footer" /> -->
    <Footer />
  </div>
</template>

<script>
</script>

<style scoped>
.sticky-footer {
  margin-top: auto;
}
</style>
