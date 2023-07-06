<template>
  <!-- HERO SECTION -->
  <section class="hero text-off-white bg-navy-blue h-screen w-screen flex flex-col items-center justify-center" id="hero">
    <div id="hero-container" class="flex max-w-content-small md:max-w-content-medium lg:max-w-content-large items-center">
      <div id="hero-text-container" class="inline">
        <h4 class="font-h4 text-h4-mobile pt-2.5 pb-2.5 md:text-h4-tablet lg:text-h4-laptop"><span
            class="text-primary">Hey there 👋!</span></h4>
        <hr class="w-20 border-b-2 border-secondary" />
        <h3 class="font-h3 text-h3-mobile pt-2.5 pb-2.5 md:text-h3-tablet lg:text-h3-laptop">Luke Hendriks.</h3>
        <h4 class="font-h4 text-h4-mobile opacity-50 pt-2.5 pb-2.5 md:text-h4-tablet lg:text-h4-laptop">Nice to meet you!
        </h4>
        <label class="font-p text-p-mobile opacity-50 first-letter:pt-2.5 pb-2.5 md:text-p-tablet lg:text-p-laptop">
          Graduated from
          <span class="text-primary">Fontys University of Applied Sciences</span>
          where I studied
          <span class="text-primary">HBO ICT</span>!
          I have specialised myself in
          <span class="text-primary">Infrastructure</span>
          and
          <span class="text-primary">Cyber Security</span>
          and gained skills in different areas including: Automation, Monitoring, Security, Containerization and
          Development.
        </label>
        <div class="flex flex-col">
          <div class="flex">
            <a class="flex mt-8 mr-6 mb-8 p-3 border-4 rounded-xl text-primary border-primary hover:cursor-pointer hover:bg-primary hover:text-off-white"
              href="https://www.linkedin.com/in/luke-h-421515225" target="_blank" rel="noreferrer">
              <span class="text-h6-laptop hover:cursor-pointer">Get in touch!</span>
            </a>
            <a class="flex pt-3.5 mt-8 rounded-xl text-off-white hover:text-primary hover:cursor-pointer justify-center"
              href="https://github.com/l3keboy" target="_blank" rel="noreferrer">
              <span class="text-h6-mobile md:text-h6-tablet lg:text-h6-laptop">
                <svg width="36" height="36" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M5.99999 0.166672C5.23395 0.166672 4.4754 0.317555 3.76767 0.610708C3.05994 0.90386 2.41688 1.33354 1.8752 1.87522C0.781238 2.96918 0.166656 4.45291 0.166656 6C0.166656 8.57834 1.84082 10.7658 4.15666 11.5417C4.44832 11.5883 4.54166 11.4075 4.54166 11.25C4.54166 11.1158 4.54166 10.7483 4.54166 10.2642C2.92582 10.6142 2.58166 9.4825 2.58166 9.4825C2.31332 8.80584 1.93416 8.625 1.93416 8.625C1.40332 8.26334 1.97499 8.275 1.97499 8.275C2.55832 8.31584 2.86749 8.87584 2.86749 8.87584C3.37499 9.7625 4.23249 9.5 4.56499 9.36001C4.61749 8.98084 4.76916 8.72417 4.93249 8.57834C3.63749 8.4325 2.27832 7.93084 2.27832 5.70834C2.27832 5.06084 2.49999 4.54167 2.87916 4.1275C2.82082 3.98167 2.61666 3.37501 2.93749 2.58751C2.93749 2.58751 3.42749 2.43001 4.54166 3.18251C5.00249 3.05417 5.50416 2.99001 5.99999 2.99001C6.49582 2.99001 6.99749 3.05417 7.45832 3.18251C8.57249 2.43001 9.06249 2.58751 9.06249 2.58751C9.38332 3.37501 9.17916 3.98167 9.12082 4.1275C9.49999 4.54167 9.72166 5.06084 9.72166 5.70834C9.72166 7.93667 8.35666 8.42667 7.05582 8.5725C7.26582 8.75334 7.45832 9.10917 7.45832 9.65167C7.45832 10.4333 7.45832 11.0633 7.45832 11.25C7.45832 11.4075 7.55166 11.5942 7.84916 11.5417C10.165 10.76 11.8333 8.57834 11.8333 6C11.8333 5.23396 11.6824 4.47542 11.3893 3.76768C11.0961 3.05995 10.6665 2.41689 10.1248 1.87522C9.58311 1.33354 8.94004 0.90386 8.23231 0.610708C7.52458 0.317555 6.76603 0.166672 5.99999 0.166672Z"
                    fill="#D7D7D9" />
                </svg>
              </span>
            </a>
            <a class="flex pt-3.5 mt-8 rounded-xl text-off-white hover:text-primary hover:cursor-pointer justify-center ml-8"
              href="https://twitter.com/l3keboy" target="_blank" rel="noreferrer">
              <span class="text-h6-mobile md:text-h6-tablet lg:text-h6-laptop">
                <svg width="36" height="36" viewBox="0 0 14 11" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path
                    d="M13.1017 1.49999C12.6525 1.70416 12.1683 1.83833 11.6667 1.9025C12.18 1.59333 12.5767 1.10333 12.7633 0.514162C12.2792 0.805828 11.7425 1.01 11.1767 1.12666C10.7158 0.624995 10.0683 0.333328 9.33334 0.333328C7.96251 0.333328 6.84251 1.45333 6.84251 2.83583C6.84251 3.03416 6.86585 3.22666 6.90668 3.4075C4.83001 3.3025 2.98085 2.30499 1.75001 0.794162C1.53418 1.16166 1.41168 1.59333 1.41168 2.04833C1.41168 2.9175 1.84918 3.6875 2.52585 4.125C2.11168 4.125 1.72668 4.00833 1.38835 3.83333C1.38835 3.83333 1.38835 3.83333 1.38835 3.85083C1.38835 5.06416 2.25168 6.07916 3.39501 6.30666C3.18501 6.365 2.96335 6.39416 2.73585 6.39416C2.57835 6.39416 2.42085 6.37666 2.26918 6.3475C2.58418 7.33333 3.50001 8.06833 4.60251 8.08583C3.75085 8.7625 2.67168 9.15916 1.49335 9.15916C1.29501 9.15916 1.09668 9.1475 0.898346 9.12416C2.00668 9.83583 3.32501 10.25 4.73668 10.25C9.33334 10.25 11.8592 6.435 11.8592 3.1275C11.8592 3.01666 11.8592 2.91166 11.8533 2.80083C12.3433 2.45083 12.7633 2.0075 13.1017 1.49999Z"
                    fill="#D7D7D9" />
                </svg>
              </span>
            </a>
          </div>
          <div class="flex flex-row">
          </div>
        </div>
      </div>
      <img src="~/assets/images/memoji.png" alt="Luke Hendriks"
        class="hidden md:inline md:w-48 md:h-48 lg:w-80 lg:h-80" />
    </div>
  </section>
</template>