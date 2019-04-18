<template>
  <div class="my-8">
    <div class="mb-12">
      <img src="@/assets/slide1.jpg" alt="mandalorian" class="rounded">
    </div>

    <div class="categories flex items-center -mx-4 mb-12">
      <div class="w-1/5 px-4">
        <a href="#" class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900">
          <img src="@/assets/disney_logo.svg" alt="disney">
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a href="#" class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900">
          <img src="@/assets/pixar_logo.svg" alt="pixar">
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a href="#" class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900">
          <img src="@/assets/marvel_logo.svg" alt="marvel">
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a href="#" class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900">
          <img src="@/assets/star_wars_logo.svg" alt="marvel">
        </a>
      </div>
      <div class="w-1/5 px-4">
        <a href="#" class="bg-gray-800 h-32 flex justify-center items-center shadow-custom border border-gray-700 rounded-lg p-4 hover:bg-gray-900">
          <img src="@/assets/national_geographic_logo.svg" alt="marvel">
        </a>
      </div>
    </div> <!-- end categories -->

    <div class="recommended px-6 mb-12">
      <h3 class="text-gray-500 mb-1">Recommended For You</h3>
      <div class="flex items-center">
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/star_wars_a_new_hope.jpg" alt="star wars"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/snow_white.jpg" alt="snow white"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/black_panther.jpg" alt="black panther"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/zootopia.jpg" alt="zootopia"></a>
        </div>
        <div class="shadow-xl">
          <a href="#"><img src="@/assets/one_strange_rock.jpg" alt="one strange rock"></a>
        </div>
      </div>
    </div> <!-- end recommended -->

    <div class="continue-watching px-6 mb-12">
      <h3 class="text-gray-500 mb-1">Continue Watching</h3>
      <div class="flex items-center">
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/the_sound_of_music.jpg" alt="sound of music"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/high_school_musical.jpg" alt="high school musical"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/cinderella.jpg" alt="cinderella"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/avengers_infinity_war.jpg" alt="avengers infinity war"></a>
        </div>
        <div class="shadow-xl">
          <a href="#"><img src="@/assets/remember_the_titans.jpg" alt="remember the titans"></a>
        </div>
      </div>
    </div> <!-- end continue-watching -->

    <div class="disney-plus-originals px-6 mb-12">
      <h3 class="text-gray-500 mb-1">Disney+ Originals</h3>
      <div class="flex items-center">
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/lady_and_the_tramp.jpg" alt="lady and the tramp"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/the_mandalorian.jpg" alt="the_mandalorian"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/high_school_musical.jpg" alt="high school musical"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/forky_asks_a_question.jpg" alt="forky asks a question"></a>
        </div>
        <div class="shadow-xl">
          <a href="#"><img src="@/assets/marvel_hero_project.jpg" alt="marvel hero project"></a>
        </div>
      </div>
    </div> <!-- end disney-plus-originals -->

    <div class="trending-now px-6 mb-12">
      <h3 class="text-gray-500 mb-1">Trending Now</h3>
      <div class="flex items-center">
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/avengers_endgame.jpg" alt="avengers_endgame"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/avengers_infinity_war.jpg" alt="avengers infinity war"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/black_panther.jpg" alt="black panther"></a>
        </div>
        <div class="shadow-xl mr-6">
          <a href="#"><img src="@/assets/star_wars_a_new_hope.jpg" alt="star wars"></a>
        </div>
        <div class="shadow-xl">
          <a href="#"><img src="@/assets/zootopia.jpg" alt="zootopia"></a>
        </div>
      </div>
    </div> <!-- end trending-now -->

  </div>
</template>

<script>


export default {
  name: 'home',
}
</script>
