<template>
  <div class="py-20">
    <div class="text-gray-600 body-font relative">
      <div class="absolute inset-0 bg-gray-300">
        <iframe width="100%" height="700" frameborder="0" scrolling="no" marginheight="0" marginwidth="0"
          src="https://maps.google.com/maps?width=100%25&amp;height=600&amp;hl=en&amp;q=7%C2%B003'07.5%22S%20107%C2%B032'35.3%22E&amp;ie=UTF8&amp;t=&amp;z=14&amp;iwloc=B&amp;output=embed"
          style="filter: grayscale(1) contrast(1.2) opacity(0.4);"></iframe>
      </div>
      <div class="container px-5 py-24 mx-auto flex">
        <div
          class="lg:w-1/3 md:w-1/2 bg-white rounded-lg p-8 flex flex-col md:ml-auto w-full mt-10 md:mt-0 relative z-5 shadow-md">
          <h2 class="text-gray-900 text-lg mb-1 font-medium title-font font-semibold">Kontak Kami</h2>
          <p class="leading-relaxed mb-5 text-gray-600">Ajukan pertanyaanmu untuk informasi lebih lanjut.</p>
          <div class="relative mb-4">
            <label for="email" class="leading-7 text-sm text-gray-600">Email</label>
            <input type="email" id="email" name="email"
              class="w-full bg-white rounded border border-gray-300 focus:border-yellow-500 focus:ring-2 focus:ring-yellow-200 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out">
          </div>
          <div class="relative mb-4">
            <label for="message" class="leading-7 text-sm text-gray-600">Message</label>
            <textarea id="message" name="message"
              class="w-full bg-white rounded border border-gray-300 focus:border-yellow-500 focus:ring-2 focus:ring-yellow-200 h-32 text-base outline-none text-gray-700 py-1 px-3 resize-none leading-6 transition-colors duration-200 ease-in-out"></textarea>
          </div>
          <button
            class="text-white bg-yellow-500 border-0 py-2 px-6 focus:outline-none hover:bg-yellow-600 rounded text-lg">Kirim</button>
          <p class="text-xs text-gray-500 mt-3">Kami akan balas pesanmu sesegera mungkin.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>