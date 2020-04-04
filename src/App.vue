<template>
  <div class="antialiased">
    <div class="min-h-screen font-raleway text-gray-100">
      <div
        class="container mx-auto max-w-md sm:max-w-xl md:max-w-2xl lg:max-w-3xl"
      >
        <!-- Header -->
        <div class="mt-32 flex items-center">
          <div class="flex items-center">
            <img
              class="h-16 w-16 mt-1 rounded-full"
              src="/img/profile.jpg"
              alt="profile"
            />
            <span class="ml-8 text-4xl font-bold">
              Alexander A.
              <span class="hidden sm:inline-block">González</span> Fertel
            </span>
          </div>
        </div>
        <div class="mt-8 justify-center">
          <!-- About -->
          <section>
            <p class="text-lg">
              Hello there! <br />
              I'm a 23 years old computer scientist graduated from the
              University of Havana.
            </p>
          </section>
          <hr />
          <!-- Interests -->
          <section>
            <h3 class="mt-3 font-semibold text-xl">
              I am very interested in:
            </h3>
            <ul class="mt-2">
              <li>
                <span>- </span>
                Using
                <a
                  class="red-link"
                  target="_blank"
                  href="https://en.wikipedia.org/wiki/Procedural_generation"
                >
                  Procedural Content Generation
                </a>
                while focusing on its relationship with
                <a
                  class="red-link"
                  target="_blank"
                  href="https://en.wikipedia.org/wiki/Machine_learning"
                >
                  Machine Learning
                </a>
                to develop mixed-initiave tools for artists .
              </li>
              <li>
                <span>- </span>

                Reading about and experimenting with
                <a
                  class="red-link"
                  target="_blank"
                  href="https://en.wikipedia.org/wiki/Cellular_automaton"
                >
                  Cellular Automata
                </a>
                and the <i>new kind of science</i> that
                <a
                  class="red-link"
                  target="_blank"
                  href="https://www.stephenwolfram.com/"
                >
                  Stephen Wolfram
                </a>
                tells us about.
              </li>
              <li>
                <span>- </span>

                <a
                  class="red-link"
                  target="_blank"
                  href="https://en.wikipedia.org/wiki/Functional_programming"
                >
                  Functional Programming
                </a>
                is pervading most of today's mainstream programming languages.
              </li>
              <li>
                <span>- </span>
                Learning about
                <a
                  class="red-link"
                  target="_blank"
                  href="https://en.wikipedia.org/wiki/Program_synthesis"
                >
                  Program Synthesis
                </a>
                and <i>The Abstraction and Reasoning Corpus</i> proposed by
                <a class="red-link" target="_blank" href="https://fchollet.com">
                  François Chollet
                </a>
                .
              </li>
            </ul>
          </section>

          <hr />
          <!-- Work -->
          <section>
            <h3 class="mt-3 font-semibold text-xl">
              Work:
            </h3>
            <p>
              I am currently a frontend developer at
              <a class="red-link" target="_blank" href="https://swagup.com">
                SwagUp
              </a>
              where we use ReactJS, NextJS, Material-UI and others.
              <br />
              This site is built using VueJS and TailwindCSS.
              <br />
              I've combined PCG and ML in my
              <a
                class="red-link"
                target="_blank"
                href="https://github.com/alexfertel/wfc"
              >
                bachelor's thesis
              </a>
              .
              <br />
              <a
                class="red-link"
                target="_blank"
                href="https://comexterinternacional.com"
              >
                Comexter's
              </a>
              official page is also built with VueJS and TailwindCSS.
            </p>
          </section>

          <hr />

          <!-- Contact -->
          <div class="mt-4">
            <p>
              <span class="flex items-center">
                <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
                  <path
                    d="M4 4h16a2 2 0 012 2v12a2 2 0 01-2 2H4a2 2 0 01-2-2V6c0-1.1.9-2 2-2zm16 3.38V6H4v1.38l8 4 8-4zm0 2.24l-7.55 3.77a1 1 0 01-.9 0L4 9.62V18h16V9.62z"
                  />
                </svg>
                <span class="ml-2">alexfertel97@gmail.com</span>
              </span>
              <span class="mt-2 flex items-center">
                <svg class="h-6 w-6 fill-current" viewBox="0 0 512 512">
                  <path
                    d="M256 0C114.636719 0 0 114.636719 0 256s114.636719 256 256 256 256-114.636719 256-256S397.363281 0 256 0zm116.886719 199.601562c.113281 2.519532.167969 5.050782.167969 7.59375 0 77.644532-59.101563 167.179688-167.183594 167.183594h.003906-.003906c-33.183594 0-64.0625-9.726562-90.066406-26.394531 4.597656.542969 9.277343.8125 14.015624.8125 27.53125 0 52.867188-9.390625 72.980469-25.152344-25.722656-.476562-47.410156-17.464843-54.894531-40.8125 3.582031.6875 7.265625 1.0625 11.042969 1.0625 5.363281 0 10.558593-.722656 15.496093-2.070312-26.886718-5.382813-47.140624-29.144531-47.140624-57.597657 0-.265624 0-.503906.007812-.75 7.917969 4.402344 16.972656 7.050782 26.613281 7.347657-15.777343-10.527344-26.148437-28.523438-26.148437-48.910157 0-10.765624 2.910156-20.851562 7.957031-29.535156 28.976563 35.554688 72.28125 58.9375 121.117187 61.394532-1.007812-4.304688-1.527343-8.789063-1.527343-13.398438 0-32.4375 26.316406-58.753906 58.765625-58.753906 16.902344 0 32.167968 7.144531 42.890625 18.566406 13.386719-2.640625 25.957031-7.53125 37.3125-14.261719-4.394531 13.714844-13.707031 25.222657-25.839844 32.5 11.886719-1.421875 23.214844-4.574219 33.742187-9.253906-7.863281 11.785156-17.835937 22.136719-29.308593 30.429687zm0 0"
                  />
                </svg>
                <span class="ml-2">alexagf97</span>
              </span>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
};
</script>

<style src="./assets/tailwind.css"></style>
