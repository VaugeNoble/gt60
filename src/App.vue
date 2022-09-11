<script setup>
import countdown from './components/countdown.vue'
import {
  Disclosure,
  DisclosureButton,
  DisclosurePanel,
} from '@headlessui/vue'

</script>

<template>

  <!-- Header -->

  <!-- <div class="absolute inset-0 " >
        <img class=" h-screen w-screen object-cover" src="https://images.unsplash.com/photo-1513151233558-d860c5398176?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80" alt="" />
        <div class="absolute inset-0  h-screen bg-gray-800 mix-blend-multiply" aria-hidden="true" />
      </div> -->

  <div class=" relative w-max mx-auto py-8 sm:py-0">
    <div class=" flex flex-col px-4 text-center  justify-center sm:px-6  sm:gap-4   lg:px-8">
      <h1 class="text-7xl font-extrabold tracking-tight  sm:ml-24 text-white sm:text-7xl md:text-7xl lg:text-8xl">
        Happy Birthday </h1>
      <h1
        class="text-7xl font-extrabold tracking-tight justify-self-center sm:ml-24 text-white sm:text-7xl md:text-7xl lg:text-8xl">
        Glenn </h1>



    </div>

  </div>
  <!-- timer -->
  <div>

    <div class="relative max-w-4xl   mx-4 sm:mx-auto sm:px-6   lg:px-8">
      <!-- <div class="relative py-4 px-4 bg-white  rounded-xl shadow-2xl  lg:px-16 ">
        <div id="countdown1" class="flex justify-center ">
          <ul>
            <li class="inline-block p-4 text-2xl text-center font-bold"><span id="days"
                class="block text-6xl"></span>Days</li>
            <li class="inline-block p-4 text-2xl text-center font-bold "><span id="hours"
                class="block text-6xl"></span>Hours</li>
            <li class=" p-4 text-2xl text-center hidden sm:inline-block font-bold"><span id="minutes"
                class="block text-6xl"></span>Minutes</li>
            <li class=" p-4 text-2xl text-center hidden sm:inline-block font-bold"><span id="seconds"
                class="block text-6xl"></span>Seconds</li>
            <div>
              <li class=" p-4 text-2xl text-center inline-block font-bold sm:hidden "><span id="minutes2"
                  class="block text-6xl"></span>Minutes</li>
              <li class=" p-4 text-2xl text-center inline-block font-bold sm:hidden"><span id="seconds2"
                  class="block text-6xl"></span>Seconds</li>
            </div>
          </ul>
        </div>
        <div id="content1" class="flex justify-center ">Hello</div>
      </div>

      <div class=" relative w-max mx-auto py-8  text-white text-center sm:py-0 ">
        <h1 class="p-4 pt-11 sm:text-4xl text-3xl  inline-block font-bold  "> Come back when the timer hits zero <br> to
          see messages and more! </h1>
      </div> -->

      <!-- <div class="w-full  pt-16">
        <div class=" mx-auto w-full rounded-md bg-white p-2">
          <Disclosure v-slot="{ open }">
            <a href="#gForm">
              <DisclosureButton
                class=" flex w-full justify-between rounded-lg text-blueDusk/95 px-4 py-2 text-left text-2xl font-bold hover:bg-blueDusk/20 focus:outline-none focus-visible:ring focus-visible:ring-blueDusk focus-visible:ring-opacity-75">
                <span>Leave a birthday message for Glenn!</span>

                <ChevronUpIcon :class="open ? 'rotate-180 transform' : ''" class="h-5 w-5 text-blueDusk/95" />
              </DisclosureButton>
            </a>
            <DisclosurePanel class="sm:px-4 pt-4 pb-2 text-sm text-gray-500">
              <div id="gForm" class=" border-t-4  border-blueDusk/95  sm:pt-4"><iframe
                  class=" mx-auto w-full h-[760px] md:w-[640px] sm:h-[700px] "
                  src="https://docs.google.com/forms/d/e/1FAIpQLSefeo9KjC3IFR5Y_13KDnSWNFF9AOONgfsvHoCsDcJqZhSopg/viewform?embedded=true"
                  frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
              </div>
            </DisclosurePanel>
          </Disclosure>

        </div>
      </div> -->

      <!--  -->
      <ul role="list"
        className="mx-auto mt-16 grid max-w-2xl grid-cols-1 gap-6 sm:gap-8 lg:mt-20 lg:max-w-none lg:grid-cols-3">

        <li>
          <ul role="list" className="flex flex-col gap-y-6 sm:gap-y-8">

            <li>
              <figure className="relative rounded-2xl bg-white p-6 shadow-xl shadow-slate-900/10">
                <QuoteIcon className="absolute top-6 left-6 fill-slate-100" />
                <blockquote className="relative">
                  <p className="text-md font-bold text-slate-900">
                    Tank you for feeding me. And for taking me outside for me to go poo. And for scratching my earz. And
                    for pwaying tug wuff me
                  </p>
                </blockquote>
                <figcaption className="relative mt-3 flex items-center justify-between border-t border-slate-100 pt-3">
                  <div>
                    <div className="font-display text-base text-slate-900">
                      Bailey
                    </div>
                    <div className="mt-1 text-sm text-slate-500">
                      Family
                    </div>
                  </div>

                </figcaption>
              </figure>
            </li>

          </ul>
        </li>
        <li>
          <ul role="list" className="flex flex-col gap-y-6 sm:gap-y-8">

            <li>
              <figure className="relative rounded-2xl bg-white p-6 shadow-xl shadow-slate-900/10">
                <QuoteIcon className="absolute top-6 left-6 fill-slate-100" />
                <blockquote className="relative">
                  <p className="text-md font-bold text-slate-900">
                    Thank you for the insightful theological discussions and the openness to discuss hard topics. Thank
                    you for being a really cool guy.
                  </p>
                </blockquote>
                <figcaption className="relative mt-3 flex items-center justify-between border-t border-slate-100 pt-3">
                  <div>
                    <div className="font-display text-base text-slate-900">
                      Randolph Brunet
                    </div>
                    <div className="mt-1 text-sm text-slate-500">
                      Friend
                    </div>
                  </div>

                </figcaption>
              </figure>
            </li>

          </ul>
        </li>
        <li>
          <ul role="list" className="flex flex-col gap-y-6 sm:gap-y-8">

            <li>
              <figure className="relative rounded-2xl bg-white p-6 shadow-xl shadow-slate-900/10">
                <QuoteIcon className="absolute top-6 left-6 fill-slate-100" />
                <blockquote className="relative">
                  <p className="text-md font-bold text-slate-900">
                    Happy birthday Glen! Celebrate well. Be careful at your age. No sudden movements...but dance and
                    have fun. We cannot believe you are this old. Love you and pray for many great years ahead for you
                    🙏 ❤
                  </p>
                </blockquote>
                <figcaption className="relative mt-3 flex items-center justify-between border-t border-slate-100 pt-3">
                  <div>
                    <div className="font-display text-base text-slate-900">
                      Jim and Pam Wilcox
                    </div>
                    <div className="mt-1 text-sm text-slate-500">
                      Friend
                    </div>
                  </div>

                </figcaption>
              </figure>
            </li>

          </ul>
        </li>

      </ul>

    </div>
  </div>


  <!-- width="640" height="640" -->
</template>




<style>

</style>
