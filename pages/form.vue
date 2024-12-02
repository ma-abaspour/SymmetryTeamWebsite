<template>
  <section class="max-w-screen-sm mx-auto pt-8 flex flex-col gap-2" id="target">
    <p class="text-gray-200 font-bold">Proposition Form</p>
    <p class="text-gray-500 px-3 py-1 text-xs md:text-sm">We select projects not solely for their financial return,
      but for their alignment with our intellectual interests. We primarily focus on solving simple problems—or a
      collection of simple problems—using a strictly first-principles and modular approach, aiming for solutions that
      will remain effective for decades to come.</p>

    <textarea rows="1" placeholder="Please introduce yourself." class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <textarea rows="1" placeholder="Tell us about the problem you're trying to solve."
      class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <textarea rows="1" placeholder="How could we contact you?" class="bg-gray-300 rounded mx-2 p-2 text-sm"></textarea>
    <p class="text-gray-500 px-3 py-1 text-xs md:text-sm"> # Please explain at length. You can expand input fields by
      dragging down from the bottom-right corner.
    </p>

    <button type="submit"
      class="bg-blue-500 w-fit text-xs md:text-sm hover:bg-blue-600 text-white font-bold mx-3 py-2 px-4 rounded">Submit</button>
  </section>
</template>