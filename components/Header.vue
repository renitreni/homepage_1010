<template>
  <header class="fixed w-full">
    <nav class="border-gray-200 bg-white dark:bg-gray-900 py-2.5">
      <div
        class="flex flex-wrap justify-between items-center mx-auto px-4 max-w-screen-xl"
      >
        <a href="#" class="flex items-center">
          <img
            src="public/images/1010-logo.png"
            class="mr-3 h-6 sm:h-9"
            alt="Landwind Logo"
          />
          <span
            class="font-semibold text-xl dark:text-white whitespace-nowrap self-center"
            >1010 Ephesians</span
          >
        </a>
        <div class="flex items-center lg:order-2">
          <button
            data-collapse-toggle="mobile-menu-2"
            type="button"
            class="inline-flex items-center lg:hidden hover:bg-gray-100 dark:hover:bg-gray-700 ml-1 p-2 rounded-lg focus:ring-2 focus:ring-gray-200 dark:focus:ring-gray-600 text-gray-500 text-sm focus:outline-none dark:text-gray-400"
            aria-controls="mobile-menu-2"
            aria-expanded="false"
          >
            <span class="sr-only">Open main menu</span>
            <svg
              class="w-6 h-6"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                clip-rule="evenodd"
              ></path>
            </svg>
            <svg
              class="hidden w-6 h-6"
              fill="currentColor"
              viewBox="0 0 20 20"
              xmlns="http://www.w3.org/2000/svg"
            >
              <path
                fill-rule="evenodd"
                d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                clip-rule="evenodd"
              ></path>
            </svg>
          </button>
        </div>
        <div
          class="lg:flex justify-between items-center lg:order-1 hidden w-full lg:w-auto"
          id="mobile-menu-2"
        >
          <ul
            class="flex lg:flex-row flex-col lg:space-x-8 mt-4 lg:mt-0 font-medium"
          >
            <li>
              <a
                href="#"
                class="block bg-purple-700 lg:bg-transparent py-2 lg:p-0 pr-4 pl-3 rounded text-white lg:text-purple-700 dark:text-white"
                aria-current="page"
                >Home</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block border-gray-100 lg:border-0 dark:border-gray-700 lg:hover:bg-transparent lg:dark:hover:bg-transparent hover:bg-gray-50 dark:hover:bg-gray-700 py-2 lg:p-0 pr-4 pl-3 border-b text-gray-700 lg:hover:text-purple-700 lg:dark:hover:text-white dark:hover:text-white dark:text-gray-400"
                >Company</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block border-gray-100 lg:border-0 dark:border-gray-700 lg:hover:bg-transparent lg:dark:hover:bg-transparent hover:bg-gray-50 dark:hover:bg-gray-700 py-2 lg:p-0 pr-4 pl-3 border-b text-gray-700 lg:hover:text-purple-700 lg:dark:hover:text-white dark:hover:text-white dark:text-gray-400"
                >Marketplace</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block border-gray-100 lg:border-0 dark:border-gray-700 lg:hover:bg-transparent lg:dark:hover:bg-transparent hover:bg-gray-50 dark:hover:bg-gray-700 py-2 lg:p-0 pr-4 pl-3 border-b text-gray-700 lg:hover:text-purple-700 lg:dark:hover:text-white dark:hover:text-white dark:text-gray-400"
                >Features</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block border-gray-100 lg:border-0 dark:border-gray-700 lg:hover:bg-transparent lg:dark:hover:bg-transparent hover:bg-gray-50 dark:hover:bg-gray-700 py-2 lg:p-0 pr-4 pl-3 border-b text-gray-700 lg:hover:text-purple-700 lg:dark:hover:text-white dark:hover:text-white dark:text-gray-400"
                >Team</a
              >
            </li>
            <li>
              <a
                href="#"
                class="block border-gray-100 lg:border-0 dark:border-gray-700 lg:hover:bg-transparent lg:dark:hover:bg-transparent hover:bg-gray-50 dark:hover:bg-gray-700 py-2 lg:p-0 pr-4 pl-3 border-b text-gray-700 lg:hover:text-purple-700 lg:dark:hover:text-white dark:hover:text-white dark:text-gray-400"
                >Contact</a
              >
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>