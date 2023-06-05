<template>
  <!-- HERO SECTION -->
  <section class="hero text-off-white bg-navy-blue h-screen w-screen flex flex-col items-center justify-center" id="hero">
    <div id="hero-container" class="flex max-w-content-small md:max-w-content-medium lg:max-w-content-large items-center">
        <div id="hero-text-container" class="inline">
            <h4 class="font-h4 text-h4-mobile pt-2.5 pb-2.5 md:text-h4-tablet lg:text-h4-laptop"><span class="text-primary">Hey there 👋!</span></h4>
            <hr class="w-20 border-b-2 border-secondary" />
            <h3 class="font-h3 text-h3-mobile pt-2.5 pb-2.5 md:text-h3-tablet lg:text-h3-laptop">Luke Hendriks.</h3>
            <h4 class="font-h4 text-h4-mobile opacity-50 pt-2.5 pb-2.5 md:text-h4-tablet lg:text-h4-laptop">Nice to meet you!</h4>
            <label class="font-p text-p-mobile opacity-50 first-letter:pt-2.5 pb-2.5 md:text-p-tablet lg:text-p-laptop">I am a <span class="text-primary">ICT & Infrastructure</span> & <span class="text-primary">Cyber Security</span> student at Fontys University of applied sciences, passionate about programming!</label>
            <div class="flex flex-row">
              <button class="flex mt-12 mr-6 mb-12 p-3 border-4 rounded-xl text-primary border-primary hover:bg-primary hover:text-off-white" onclick="window.open('https://www.linkedin.com/in/luke-h-421515225')">
                <span class="text-h6-mobile md:text-h6-tablet lg:text-h6-laptop">Contact me!</span>
                <svg class="h-5 w-5 md:h-6 md:w-6 lg:h-8 lg:w-8 ml-1.5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" stroke-width="3" stroke="currentColor" fill="none">
                  <path d="M26.67,38.57l-.82,11.54A2.88,2.88,0,0,0,28.14,49l5.5-5.26,11.42,8.35c2.08,1.17,3.55.56,4.12-1.92l7.49-35.12h0c.66-3.09-1.08-4.33-3.16-3.55l-44,16.85C6.47,29.55,6.54,31.23,9,32l11.26,3.5L45.59,20.71c1.23-.83,2.36-.37,1.44.44Z" 
                  stroke-linecap="round"/>
                </svg>
              </button>
              <a class="flex mt-12 mb-12 pt-3.5 rounded-xl text-off-white hover:text-primary hover:cursor-pointer justify-center" onclick="window.open('https://github.com/l3keboy')">
                <span class="text-h6-mobile md:text-h6-tablet lg:text-h6-laptop">View my GitHub!</span>
              </a>
            </div>
        </div>
        <img src="/assets/images/memoji.png" alt="Luke Hendriks" class="hidden md:inline md:w-48 md:h-48 lg:w-80 lg:h-80" />
    </div>
  </section>
</template>