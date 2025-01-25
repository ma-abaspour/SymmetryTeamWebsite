<template>
    <div class="max-w-md mx-auto p-5 bg-gray-800 rounded-lg shadow-md mt-8">
    <h2 class="text-lg font-medium text-gray-200 text-center mb-4">Contact Us</h2>
    <form class="space-y-3">
      <div>
        <label for="name" class="block text-xs text-gray-400 mb-1">Your Name</label>
        <input
          type="text"
          id="name"
          class="w-full px-3 py-1 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-1 focus:ring-teal-400 text-sm"
        />
      </div>
      <div>
        <label for="email" class="block text-xs text-gray-400 mb-1">Your Email Address</label>
        <input
          type="email"
          id="email"
          class="w-full px-3 py-1 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-1 focus:ring-teal-400 text-sm"
        />
      </div>
      <div>
        <label for="message" class="block text-xs text-gray-400 mb-1">Your Message</label>
        <textarea
          id="message"
          rows="3"
          class="w-full px-3 py-1 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-1 focus:ring-teal-400 text-sm"
        ></textarea>
      </div>
      <button
        type="submit"
        class="w-full bg-teal-500 text-gray-900 font-medium py-2 rounded hover:bg-teal-600 transition text-sm"
      >
        Submit
      </button>
    </form>
  </div>


</template>