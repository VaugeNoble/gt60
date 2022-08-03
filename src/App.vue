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
      <div class="grid px-4 sm:px-6 sm:inline-grid sm:gap-24  sm:grid-cols-2 lg:px-8">
        <h1 class="text-7xl font-extrabold tracking-tight justify-self-center self-center  sm:ml-24 text-white sm:text-7xl md:text-7xl lg:text-8xl">Glenn <br> Turns</h1>
        <h1 class="text-[180px] font-extrabold tracking-tight justify-self-center self-center  sm:mr-24 text-white md:text-[180px] lg:text-[240px]">60</h1>
            </div>
            <h1 id="headline1" class="text-4xl sm:-mt-8 sm:mb-4 font-mono font-semibold tracking-tight text-center self-center pb-4  text-white">In</h1>
      </div>
      <!-- timer -->
    <div>

    <div class="relative max-w-4xl   mx-4 sm:mx-auto sm:px-6   lg:px-8">
      <div class="relative py-4 px-4 bg-white  rounded-xl shadow-2xl  lg:px-16 ">
        <div id="countdown1" class="flex justify-center ">
            <ul >
                <li class="inline-block p-4 text-2xl text-center font-bold"><span id="days" class="block text-6xl"></span>Days</li>
                <li class="inline-block p-4 text-2xl text-center font-bold "><span id="hours" class="block text-6xl"></span>Hours</li>
                <li class=" p-4 text-2xl text-center hidden sm:inline-block font-bold"><span id="minutes" class="block text-6xl"></span>Minutes</li>
                <li class=" p-4 text-2xl text-center hidden sm:inline-block font-bold"><span id="seconds" class="block text-6xl"></span>Seconds</li>
                <div>
                   <li class=" p-4 text-2xl text-center inline-block font-bold sm:hidden "><span id="minutes2" class="block text-6xl"></span>Minutes</li>
                    <li class=" p-4 text-2xl text-center inline-block font-bold sm:hidden"><span id="seconds2" class="block text-6xl"></span>Seconds</li>
                </div>
            </ul>
        </div>
            </div> 
            
    <div class=" relative w-max mx-auto py-8  text-white text-center sm:py-0 "><h1 class="p-4 pt-11 sm:text-4xl text-3xl  inline-block font-bold  ">  Come back when the timer hits zero <br> to see messages and more!  </h1></div>
   
           <div class="w-full  pt-16">
    <div class=" mx-auto w-full rounded-md bg-white p-2">
      <Disclosure v-slot="{ open }">
        <a href="#gForm"><DisclosureButton
          class=" flex w-full justify-between rounded-lg text-blueDusk/95 px-4 py-2 text-left text-2xl font-bold hover:bg-blueDusk/20 focus:outline-none focus-visible:ring focus-visible:ring-blueDusk focus-visible:ring-opacity-75"
        > <span>Leave a birthday message for Glenn!</span> 
          <!-- <span>Leave a birthday message for Glenn!</span> -->
          <ChevronUpIcon
            :class="open ? 'rotate-180 transform' : ''"
            class="h-5 w-5 text-blueDusk/95"
          />
        </DisclosureButton></a>
        <DisclosurePanel class="sm:px-4 pt-4 pb-2 text-sm text-gray-500">
              <div id="gForm" class=" border-t-4  border-blueDusk/95  sm:pt-4"><iframe class= " mx-auto w-full h-[760px] md:w-[640px] sm:h-[700px] " src="https://docs.google.com/forms/d/e/1FAIpQLSefeo9KjC3IFR5Y_13KDnSWNFF9AOONgfsvHoCsDcJqZhSopg/viewform?embedded=true"  frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
</div>
        </DisclosurePanel>
      </Disclosure>
    
    </div>
  </div>

  <!--  -->

         
      </div>
    </div>
    

  <!-- width="640" height="640" -->
</template>




<style>
 
</style>
