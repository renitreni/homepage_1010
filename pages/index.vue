<script lang="ts" setup>
import Hero from "../components/Hero.vue";
</script>

<template>
  <div>
    <Hero></Hero>
    <!-- Start block -->
    <section class="bg-gray-50 dark:bg-gray-800">
      <div
        class="space-y-12 lg:space-y-20 mx-auto px-4 lg:px-6 py-8 lg:py-24 max-w-screen-xl"
      >
        <!-- Row -->
        <div class="items-center gap-8 xl:gap-16 lg:grid lg:grid-cols-2">
          <div class="text-gray-500 sm:text-lg dark:text-gray-400">
            <h2
              class="mb-4 font-extrabold text-3xl text-gray-900 dark:text-white tracking-tight"
            >
              Specializing in comprehensive human resources solutions
            </h2>
            <p class="mb-8 font-light lg:text-xl">
              Their services typically include talent acquisition, employee
              training and development, benefits management, compliance
              consulting, and performance evaluation.
            </p>
            <!-- List -->
            <ul
              role="list"
              class="space-y-5 border-gray-200 dark:border-gray-700 my-7 pt-8 border-t"
            >
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Talent Acquisition and Development</span
                >
              </li>
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Employee Engagement and Performance Management</span
                >
              </li>
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Compliance and Risk Management</span
                >
              </li>
            </ul>
            <p class="mb-8 font-light lg:text-xl">
              Deliver exceptional HR solutions seamlessly—without the complexity
              of traditional HR management systems.
            </p>
          </div>
          <!-- <img
            class="lg:flex hidden mb-4 lg:mb-0 rounded-lg w-full"
            src="public/images/feature-1.png"
            alt="dashboard feature image"
          /> -->
        </div>
        <!-- Row -->
        <div class="items-center gap-8 xl:gap-16 lg:grid lg:grid-cols-2">
          <img
            class="lg:flex hidden mb-4 lg:mb-0 rounded-lg w-full"
            src="public/images/passport.jpg"
            alt="feature image 2"
          />
          <div class="text-gray-500 sm:text-lg dark:text-gray-400">
            <h2
              class="mb-4 font-extrabold text-3xl text-gray-900 dark:text-white tracking-tight"
            >
              We invest in unlocking human potential.
            </h2>
            <p class="mb-8 font-light lg:text-xl">
              Deliver seamless HR solutions quickly—without the complexity of
              traditional systems. Accelerate vital HR tasks, streamline
              workflows, and implement changes effortlessly.
            </p>
            <!-- List -->
            <ul
              role="list"
              class="space-y-5 border-gray-200 dark:border-gray-700 my-7 pt-8 border-t"
            >
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Optimized HR workflows</span
                >
              </li>
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Knowledge management solutions</span
                >
              </li>
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Development workflow</span
                >
              </li>
              <li class="flex space-x-3">
                <!-- Icon -->
                <svg
                  class="flex-shrink-0 w-5 h-5 text-purple-500 dark:text-purple-400"
                  fill="currentColor"
                  viewBox="0 0 20 20"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z"
                    clip-rule="evenodd"
                  ></path>
                </svg>
                <span
                  class="font-medium text-base text-gray-900 dark:text-white leading-tight"
                  >Knowledge management</span
                >
              </li>
            </ul>
            <p class="font-light lg:text-xl">
              Empower your team to deliver outstanding HR experiences—free from
              the limitations of conventional systems.
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- End block -->
  </div>
</template>