<template>
  <section class="relative block mt-72 py-24 lg:pt-0 bg-gray-200">
    <div
      class="
        bottom-auto
        top-0
        left-0
        right-0
        w-full
        absolute
        pointer-events-none
        overflow-hidden
        -mt-20
      "
      style="height: 80px"
    >
      <svg
        class="absolute bottom-0 overflow-hidden"
        xmlns="http://www.w3.org/2000/svg"
        preserveAspectRatio="none"
        version="1.1"
        viewBox="0 0 2560 100"
        x="0"
        y="0"
      >
        <polygon
          class="text-gray-200 fill-current"
          points="2560 0 2560 100 0 100"
        ></polygon>
      </svg>
    </div>
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap justify-center lg:-mt-64 -mt-48">
        <div class="w-full lg:w-6/12 px-4">
          <div
            class="
              relative
              flex flex-col
              min-w-0
              break-words
              w-full
              mb-6
              shadow-2xl
              rounded-lg
              bg-white
            "
          >
            <form
              name="contact"
              method="POST"
              data-netlify="true"
              data-netlify-recaptcha="true"
            >
              <div class="flex-auto p-5 lg:p-10">
                <h4 class="text-2xl font-semibold">Want to work with us?</h4>

                <p class="leading-relaxed mt-1 mb-4 text-blueGray-500">
                  Complete this form and we will get back to you in 24 hours.
                </p>

                <div class="relative w-full mb-3 mt-8">
                  <p class="hidden">
                    <label>
                      Don’t fill this out if you’re human:
                      <input name="bot-field" />
                    </label>
                  </p>

                  <label
                    class="
                      block
                      uppercase
                      text-blueGray-600 text-xs
                      font-bold
                      mb-2
                    "
                    for="full-name"
                    >Full Name*</label
                  ><input
                    type="text"
                    name="name"
                    required
                    class="
                      border-0
                      px-3
                      py-3
                      placeholder-blueGray-300
                      text-blueGray-600
                      bg-white
                      rounded
                      text-sm
                      shadow
                      focus:outline-none
                      focus:ring
                      w-full
                      ease-linear
                      transition-all
                      duration-150
                    "
                    placeholder="Full Name"
                  />
                </div>

                <div class="relative w-full mb-3">
                  <label
                    class="
                      block
                      uppercase
                      text-blueGray-600 text-xs
                      font-bold
                      mb-2
                    "
                    for="email"
                    >Email*</label
                  ><input
                    type="email"
                    required
                    name="email"
                    class="
                      border-0
                      px-3
                      py-3
                      placeholder-blueGray-300
                      text-blueGray-600
                      bg-white
                      rounded
                      text-sm
                      shadow
                      focus:outline-none
                      focus:ring
                      w-full
                      ease-linear
                      transition-all
                      duration-150
                    "
                    placeholder="Email"
                  />
                </div>

                <div class="relative w-full mb-3">
                  <label
                    class="
                      block
                      uppercase
                      text-blueGray-600 text-xs
                      font-bold
                      mb-2
                    "
                    for="message"
                    >Message*</label
                  ><textarea
                    rows="4"
                    cols="80"
                    required
                    name="message"
                    class="
                      border-0
                      px-3
                      py-3
                      placeholder-blueGray-300
                      text-blueGray-600
                      bg-white
                      rounded
                      text-sm
                      shadow
                      focus:outline-none
                      focus:ring
                      w-full
                    "
                    placeholder="Type a message..."
                  ></textarea>
                </div>

                <div data-netlify-recaptcha="true"></div>

                <div class="text-center mt-6">
                  <base-btn> Send Message </base-btn>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>