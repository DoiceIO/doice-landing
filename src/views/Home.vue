<template>
  <div class="bg-gray-800">
    <div class="text-white">
      <div class="w-full max-w-6xl mx-auto">
        <div class="text-center py-16">
          <h1 class="text-4xl font-bold">Self-Hosted Rooms To Hang With Your Friends</h1>
          <p
            class="text-xl w-full max-w-xs md:max-w-full mx-auto"
          >Stream games, watch YouTube, host virtual parties. Your all-in-one space.</p>
          <div class="flex justify-center mt-5">
            <a
              href="https://demo.doice.io"
              target="_blank"
              class="bg-blue-600 px-6 py-4 mr-4 rounded shadow-md hover:shadow-xl duration-100 transform hover:scale-105"
            >Free Demo</a>
            <a
              href="https://gist.github.com/TrystonPerry/ec91687b77adff8a8c72f611e3221e82"
              target="_blank"
              class="bg-gray-700 px-6 py-4 rounded shadow-md hover:shadow-xl duration-100 transform hover:scale-105"
            >Install Guide</a>
          </div>
        </div>

        <div
          class="relative overflow-hidden max-w-full"
          style="padding-bottom:56.25%; padding-top: 30px; height:0;"
        >
          <iframe
            src="https://www.youtube.com/embed/1Nf5P4eP9OI"
            frameborder="0"
            allowfullscreen
            auotplay
            muted
            class="absolute top-0 left-0 w-full h-full"
          ></iframe>
        </div>
      </div>

      <!-- Features -->
      <div class="mt-12 p-4 bg-gray-900">
        <div class="w-full max-w-6xl mx-auto">
          <h2
            class="text-3xl text-center max-w-xl mx-auto font-bold my-12"
          >With All The Features A Modern Chat App Should Have</h2>

          <ul class="md:flex flex-wrap mt-6 text-center">
            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fas fa-desktop bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Screen Share</h2>
              <p
                class="text-left"
              >Stream your desktop, games, or videos with sub-second delay and crisp video quality. Multiple users can screen share in a single room at once.</p>
            </li>

            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fab fa-youtube bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Synchronized Video Player</h2>
              <p
                class="text-left"
              >Queue up YouTube, Twitch, or .mp4 videos to binge watch with your friends and have a laugh. Our video player stays synchronized with all users.</p>
            </li>

            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fas fa-headset bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Voice Chat</h2>
              <p
                class="text-left"
              >An easy place to hang out with as many friends as you like. Customize how many can join your room to whatever you like. Whether you want to hang with a few friends or host a community, Doice has you covered!</p>
            </li>

            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fas fa-feather bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Lightweight</h2>
              <p
                class="text-left"
              >Whether it's the clean design or the optimized code, Doice strives to be powerful yet simple at the same time. Every feature is clearly planned out before launching.</p>
            </li>

            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fas fa-cog bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Customizable By Default</h2>
              <p
                class="text-left"
              >Built with customization in mind, you can configure your Doice server to operate in any way you'd like. We hope you can find creative use cases for it!</p>
            </li>

            <li class="md:w-6/12 lg:w-4/12 p-6 mb-8">
              <i class="fab fa-chrome bg-blue-600 p-4 text-xl rounded-full"></i>
              <h2 class="text-2xl my-2 font-bold">Web Browser Friendly</h2>
              <p
                class="text-left"
              >Built from the ground up in JavaScript, Doice will work in all modern web browsers including: Google Chrome, Firefox, Opera and Microsoft Edge (2019)</p>
            </li>
          </ul>
        </div>
      </div>

      <div class="py-12 px-6 mx-auto max-w-xl">
        <h2 class="text-3xl font-bold mb-2">Subscribe to our Newsletter</h2>
        <p
          class="mb-4"
        >Want the latest news on Doice updates or community content? We'll send it straight to your inbox. We won't spam or post more than once per week.</p>
        <EmailSubscribe />

        <h2 class="text-3xl text-center mt-16">Ready To Get Started?</h2>
        <div class="flex justify-center mt-5">
          <a
            href="https://demo.doice.io"
            target="_blank"
            class="bg-blue-600 px-6 py-4 mr-4 rounded shadow-md hover:shadow-xl duration-100 transform hover:scale-105"
          >Free Demo</a>
          <a
            href="https://gist.github.com/TrystonPerry/ec91687b77adff8a8c72f611e3221e82"
            target="_blank"
            class="bg-gray-700 px-6 py-4 rounded shadow-md hover:shadow-xl duration-100 transform hover:scale-105"
          >Install Guide</a>
        </div>
      </div>

      <footer class="bg-gray-900">
        <div class="flex max-w-6xl mx-auto p-4">
          <span>© 2020 Tryston Perry, all rights reserved</span>
          <div class="flex-grow"></div>
          <a href="https://github.com/DoiceIO" class="mr-2">
            <i class="fab fa-github"></i>
          </a>
          <a href="https://twitter.com/DoiceIO">
            <i class="fab fa-twitter"></i>
          </a>
        </div>
      </footer>
    </div>
  </div>
</template>

<script>
import EmailSubscribe from "@/components/EmailSubscribe";

// @ is an alias to /src
export default {
  components: {
    EmailSubscribe,
  },
};
</script>
