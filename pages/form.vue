<template>
  <!-- <section class="max-w-screen-sm mx-auto pt-8 flex flex-col gap-2" id="target">
    <p class="text-gray-200 font-bold">Contact Form</p>

    <textarea rows="1" placeholder="Please introduce yourself." class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <textarea rows="1" placeholder="Your message." class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <textarea rows="1" placeholder="How could we contact you?" class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <p class="text-gray-500 px-3 py-1 text-xs md:text-sm"> # You can expand input fields by dragging down from the bottom-right corner.</p>

    <button type="submit" class="bg-blue-500 w-fit text-xs md:text-sm hover:bg-blue-600 text-white font-bold mx-3 py-2 px-4 rounded">Submit</button>
  </section> -->


    <div class="max-w-md mx-auto p-6 bg-gray-800 rounded-lg shadow-md mt-10">
    <h2 class="text-2xl font-semibold text-gray-200 mb-6">Contact Us</h2>
    <form class="space-y-4">
      <div>
        <label for="name" class="block text-gray-300 text-sm mb-1">Your Name</label>
        <input
          type="text"
          id="name"
          placeholder="Enter your name"
          class="w-full px-4 py-2 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-teal-400"
        />
      </div>
      <div>
        <label for="email" class="block text-gray-300 text-sm mb-1">Email Address</label>
        <input
          type="email"
          id="email"
          placeholder="you@example.com"
          class="w-full px-4 py-2 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-teal-400"
        />
      </div>
      <div>
        <label for="message" class="block text-gray-300 text-sm mb-1">Your Message</label>
        <textarea
          id="message"
          rows="4"
          placeholder="Write your message here..."
          class="w-full px-4 py-2 bg-gray-700 text-gray-200 border border-gray-600 rounded focus:outline-none focus:ring-2 focus:ring-teal-400 resize-none"
        ></textarea>
      </div>
      <button
        type="submit"
        class="w-full bg-teal-500 text-gray-900 font-semibold py-2 px-4 rounded hover:bg-teal-600 transition"
      >
        Submit
      </button>
    </form>
  </div>


</template>