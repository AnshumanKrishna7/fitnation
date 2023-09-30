<template>
  <NavBar />

    <div class="hero text-black scroll-smooth bg-graysuit" id="site-container">
      <div class="h-screen flex flex-col items-center">
        <div class="hero-content flex flex-col items-center">
          <div class="vertical-center-container">
            <div class="super-big-text font-orelega text-6xl font-bold ">
              FITNATION
            </div>
          </div>
            <p class="font-abril text-4xl font-bold text-center">
              Fitness, summed up.
            </p>
          </div>
        </div>
      </div>

  <div class="content bg-williamgreen text-periwinklegrey flex flex-col gap-10 py-20 justify-center items-center text-lg">
    <div class="intro flex flex-col justify-center items-center gap-10">
      <p class="text-4xl font-abril w-fit text-center font-bold">From a Fitness Enthusiast, to the Fitness Enthusiasts.</p>
        <div class="flex flex-col text-center text-0.5xl gap-4 text-base px-36 font-mono pb-4">
          <p class="font-golox">
            Fitnation is the one stop solution everyone somehow or the other is looking for, in a form or two, with a feature or other. It has everything that helps you achieve your fitness, calorie, and meditation goals, all, under a single roof.
          </p>
          <p class="font-golox">
            With a wide array of exercises, and a community of fitness enthusiasts to help you along the way, we'd only be ever expanding with new ideas to implement, some of the future prospects include a seperate page and a community to showcase yor fitness journey or body slash workout progress at, a chat based feature to answer all your questions, and if any were left still, email support and everything, this is not just another fitness page, it's a revolution, a family, a nation, the Fitnation.
          </p>
        </div>

    <div class="grid grid-cols-2 gap-12 mx-20">
      <!-- Card 1 -->
      <div class="card bg-periwinklegrey text-black rounded">
        <img src="@/assets/images/index/gymseven.jpg" alt="Kettlebell" class="w-full h-48 object-cover" />
        <div class="p-4">
          <h2 class="text-2xl font-semibold">Mind Muscle Connection</h2>
            <p class="text-gray-600 mt-2">
             Get fit and strong with our wide array of exercises for each muscle group, with something that matters the most in these, a correct form.
            </p>
          <Button class="btn bg-tiber text-greysuit mt-4 rounded" href="/workouts">Learn More</Button>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="card bg-periwinklegrey text-black rounded">
        <img src="@/assets/images/calories/caloriethree.jpg" alt="Jumper" class="w-full h-48 object-cover" />
        <div class="p-4">
          <h2 class="text-2xl font-semibold">Calorie Countdown</h2>
            <p class="text-gray-600 mt-2">
             Each calorie counts, hence, something that helps you keep track of your calories, and helps you achieve your goals.
            </p>
          <Button class="btn bg-tiber text-greysuit mt-4 rounded" href="/calorie">Learn More</Button>
        </div>
      </div>

      <!-- Card 3 -->
      <div class="card bg-periwinklegrey text-black rounded">
        <img src="@/assets/images/meditation/meditationone.jpg" alt="Yoga" class="w-full h-48 object-cover" />
        <div class="p-4">
          <h2 class="text-2xl font-semibold">Zen Zone Meditation</h2>
            <p class="text-gray-600 mt-2">
              Training on the inside is as necessary for a healthy lifestyle as training on the outside. Here's something that helps you achieve that.
            </p>
          <Button class="btn bg-tiber text-greysuit mt-4 rounded" href="/meditation">Learn More</Button>
        </div>
      </div>

      <!-- Card 4 -->
      <div class="card bg-periwinklegrey text-black rounded">
        <img src="@/assets/images/index/musclethree.jpg" alt="Barbell" class="w-full h-48 object-cover" />
          <div class="p-4">
            <h2 class="text-2xl font-semibold">Strong & Sculpted</h2>
              <p class="text-gray-600 mt-2">
                Maximize your strength gains and muscle definition with some of the most widely-used, efficient and hand-crafted workouts.
              </p>
              <Button class="btn bg-tiber text-greysuit mt-4 rounded" href="/workouts">Learn More</Button>
          </div>
      </div>
    </div>
    </div>
  </div>

    <div class="bg-williamgreen flex flex-col justify-center items-center py-4 ">
      <h1 class="text-periwinklegrey text-6xl font-orelega font-bold pb-4">Personalized Plans</h1>
        <p class="text-periwinklegrey text-lg font-golox mt-4 pb-2">
          With Fitnation, you'll receive custom workout plans tailored to your goals, fitness level, and schedule. Start your fitness journey the right way.
        </p>
      <div class="flex mt-8 pb-4">
        <Button class="btn bg-tiber text-greysuit mr-4 rounded" href="/auth">Get Started</Button>
        <Button class="btn bg-greysuit text-tiber rounded" href="/auth">Learn More</Button>
      </div>

      <questions class="py-18" />
    </div>

  <Footer />
</template>

<style scoped>

/* I know that using tailwindcss at half the places and stylescoped at the other doesnt make a lot of sense but the code was throwing errors */
.hero {
    background: url("@/assets/images/index/gymfive.jpg");
    background-position: center;
    background-repeat: no-repeat;
    background-size: 100%;
    background-blend-mode: color-dodge;
    position: relative;
}

/* CSS, first text */
.super-big-text {
  font-size: 14rem; 
  font-weight: bold; 
}

/* CSS, second text */
.text-4xl.font-bold {
  font-size: 2.5rem;
  font-weight: bold;
}

.vertical-center-container {
  display: flex;
  flex-direction: column;
  align-items: flex-start; 
  margin-top: 10px;
}

</style>
