<template>
  <section class="text-gray-700 body-font">
    <div class="container px-8 pt-48 pb-24 mx-auto lg:px-4">
      <div
        class="flex flex-col w-full p-8 mx-auto mt-10 border rounded-lg lg:w-2/6 md:w-1/2 md:ml-auto md:mt-0"
      >
        <div class="relative">
          <input
            type="name"
            id="name"
            name="name"
            placeholder="name"
            class="w-full px-4 py-2 mb-4 mr-4 text-base text-blue-700 bg-gray-100 border-transparent rounded-lg focus:border-gray-500 focus:bg-white focus:ring-0"
          />
        </div>
        <div class="relative">
          <input
            type=" email"
            id="email"
            name="email"
            placeholder=" email"
            class="w-full px-4 py-2 mb-4 mr-4 text-base text-blue-700 bg-gray-100 border-transparent rounded-lg focus:border-gray-500 focus:bg-white focus:ring-0"
          />
        </div>
        <div class="relative mb-4">
          <input
            type="password"
            id="password"
            name="password"
            placeholder="password"
            class="w-full px-4 py-2 mb-4 mr-4 text-base text-blue-700 bg-gray-100 border-transparent rounded-lg focus:border-gray-500 focus:bg-white focus:ring-0"
          />
        </div>
        <div class="flex justify-center">
          <button
            class="w-full px-8 py-2 font-semibold text-white transition duration-500 ease-in-out transform rounded-lg shadow-xl lg:w-1/2 bg-gradient-to-r from-blue-700 hover:from-blue-600 to-blue-600 hover:to-blue-700 focus:ring focus:outline-none"
          >
            Sign In
          </button>
          <button
            class="w-full px-8 py-2 font-semibold text-blue-700 transition duration-500 ease-in-out transform bg-white border rounded-lg shadow-xl hover:border-black hover:bg-black hover:text-white lg:ml-4 lg:w-1/2 focus:ring focus:outline-none"
          >
            Sign Up
          </button>
        </div>
        <p class="mx-auto mt-3 text-xs text-gray-500">
          Literally you probably haven't heard of them jean shorts.
        </p>
      </div>
    </div>
  </section>
</template>
