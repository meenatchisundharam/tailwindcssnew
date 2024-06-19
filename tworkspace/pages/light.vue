<template>
  <nav class="p-5 sticky top-0 z-1 bg-black">
    <div class="flex">
        <a href="#" class=" lg:ml-5">
            <h1 class="text-4xl font-extrabold text-white md:text-[32px] xl:text-[42px] md:font-bold xl:font-bold">kalles</h1>
        </a>
        <button id="menu-button" class="lg:hidden mt-2 ml-auto" @click="open = !open">
            <i class="fa-solid fa-bars text-white text-2xl" v-if="!open"></i>
            <i class="fa-solid fa-xmark text-white text-2xl" v-else></i>
        </button>
        <div id="menu"
        :class="{'hidden': !open}"
        role="menubar"
        class="hidden lg:flex lg:flex-row lg:items-center lg:justify-center xl:ml-auto">
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Demos</a>
             <div class="lg:flex lg:flex-col lg:items-center">
          <span class="lg:bg-blue-500 lg:text-xs lg:text-white lg:px-2 lg:rounded-full lg:ml-auto -mt-3">New</span>
  <a href="#" class=" text-gray-200 text-[17px] font-medium -mt-1 hover:text-cyan-600">Special Deal</a>
        </div>
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="#"
        >Features</a>
            <div class="lg:flex lg:flex-col lg:items-center">
          <span class="lg:bg-red-500 lg:text-xs lg:text-white lg:px-3 lg:rounded-full lg:ml-14 -mt-3">Hot</span>
          <a href="#" class="px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600 -mt-1">Performance</a>
        </div>
            <a
          role="menuitem"
          class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Support</a>
             <a
          role="menuitem"
          class="py-2 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600"
          href="/"
        >Open Free Store</a>
 <div class="effect-custom rounded-2xl relative bg-slate-950 xl:ml-28 xl:mr-6">
  <a href="sundhar" class="flex items-center justify-center relative gap-1 py-2  backdrop-blur-3xl border-gray-300 bg-black border-2 text-white font-medium rounded-md hover:bg-gray-800 xl:py-3 xl:px-4">
    <svg class="cta_icon mr-2 z-10 text-white" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
      <path d="M4.16686 11.6667H15.1133C15.9573 11.6667 16.3793 11.6667 16.7153 11.5093C17.0112 11.3707 17.2599 11.1481 17.4304 10.8693C17.6238 10.5528 17.6705 10.1333 17.7637 9.29448L18.2512 4.90695C18.2796 4.65073 18.2939 4.52262 18.2527 4.42346C18.2165 4.33638 18.1518 4.26414 18.0693 4.21856C17.9753 4.16666 17.8464 4.16666 17.5886 4.16666H3.7502M1.66675 1.66666H2.70711C2.92763 1.66666 3.03789 1.66666 3.12415 1.7086C3.2001 1.74552 3.26303 1.80464 3.30461 1.87813C3.35185 1.96161 3.35873 2.07166 3.37248 2.29175L4.12768 14.3749C4.14144 14.595 4.14831 14.7051 4.19555 14.7885C4.23713 14.862 4.30007 14.9211 4.37601 14.9581C4.46227 15 4.57253 15 4.79305 15H15.8334M6.25008 17.9167H6.25842M13.7501 17.9167H13.7584M6.66675 17.9167C6.66675 18.1468 6.4802 18.3333 6.25008 18.3333C6.01996 18.3333 5.83341 18.1468 5.83341 17.9167C5.83341 17.6865 6.01996 17.5 6.25008 17.5C6.4802 17.5 6.66675 17.6865 6.66675 17.9167ZM14.1667 17.9167C14.1667 18.1468 13.9802 18.3333 13.7501 18.3333C13.52 18.3333 13.3334 18.1468 13.3334 17.9167C13.3334 17.6865 13.52 17.5 13.7501 17.5C13.9802 17.5 14.1667 17.6865 14.1667 17.9167Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></path>
    </svg>
    <span class="cta_text text-white z-10">Buy Now $89</span>
    <div class="absolute inset-0 overflow-hidden flex justify-center items-center">
      <span class="w-full h-full bg-gradient-to-r from-violet-700 to-indigo-700 animate-pulse bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-indigo-700 to-cyan-500 animate-pulse delay-150 bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-cyan-500 to-violet-700 animate-pulse delay-300 bg-opacity-40"></span>
    </div>
  </a>
</div>
  </div>
        <div v-if="open" role="menubar" class="flex flex-col gap-2 z-10 max-h-screen absolute bg-black/80 backdrop-blur bg-opacity-70 overflow-hidden w-80 right-0 top-[75px] text-center place-items-start shadow-xl p-4 lg:hidden">
            <i @click="open = false" class="fa-solid fa-xmark self-end lg:hidden"></i>
          <a href="#" class="">
        <h1 class="text-4xl font-extrabold text-white ml-20">kalles</h1>
      </a>
            <a role="menuitem" class="py-3 px-6 text-white text-[17px] font-medium hover:text-cyan-600" href="/">Demos</a>

            <a href="#" class="px-5 text-gray-200 text-[17px] font-medium -mt-1 hover:text-cyan-600">Special Deal</a>

            <a role="menuitem" class="py-3 px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600" href="/">Features</a>

            <a href="#" class="px-6 text-gray-200 text-[17px] font-medium hover:text-cyan-600 ">Performance</a>

            <a role="menuitem" class="py-3 px-6 text-white font-medium text-[17px] hover:text-cyan-600" href="/">Support</a>

            <a role="menuitem" class="px-6 text-white font-medium text-[17px] hover:text-cyan-600" href="/">Open Store Free</a>
            <div class="effect-custom rounded-2xl relative bg-slate-950 w-full px-7 ml-4 py-4">
  <a href="sundhar" class="flex items-center justify-center relative gap-1 py-2  backdrop-blur-3xl border-gray-300 bg-black border-2 text-white font-medium rounded-md hover:bg-gray-800 xl:py-3 xl:px-4">
    <svg class="cta_icon mr-2 z-10 text-white" xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 20 20" fill="none">
      <path d="M4.16686 11.6667H15.1133C15.9573 11.6667 16.3793 11.6667 16.7153 11.5093C17.0112 11.3707 17.2599 11.1481 17.4304 10.8693C17.6238 10.5528 17.6705 10.1333 17.7637 9.29448L18.2512 4.90695C18.2796 4.65073 18.2939 4.52262 18.2527 4.42346C18.2165 4.33638 18.1518 4.26414 18.0693 4.21856C17.9753 4.16666 17.8464 4.16666 17.5886 4.16666H3.7502M1.66675 1.66666H2.70711C2.92763 1.66666 3.03789 1.66666 3.12415 1.7086C3.2001 1.74552 3.26303 1.80464 3.30461 1.87813C3.35185 1.96161 3.35873 2.07166 3.37248 2.29175L4.12768 14.3749C4.14144 14.595 4.14831 14.7051 4.19555 14.7885C4.23713 14.862 4.30007 14.9211 4.37601 14.9581C4.46227 15 4.57253 15 4.79305 15H15.8334M6.25008 17.9167H6.25842M13.7501 17.9167H13.7584M6.66675 17.9167C6.66675 18.1468 6.4802 18.3333 6.25008 18.3333C6.01996 18.3333 5.83341 18.1468 5.83341 17.9167C5.83341 17.6865 6.01996 17.5 6.25008 17.5C6.4802 17.5 6.66675 17.6865 6.66675 17.9167ZM14.1667 17.9167C14.1667 18.1468 13.9802 18.3333 13.7501 18.3333C13.52 18.3333 13.3334 18.1468 13.3334 17.9167C13.3334 17.6865 13.52 17.5 13.7501 17.5C13.9802 17.5 14.1667 17.6865 14.1667 17.9167Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round"></path>
    </svg>
    <span class="cta_text text-white z-10">Buy Now $89</span>
    <div class="absolute inset-0 overflow-hidden flex justify-center items-center">
      <span class="w-full h-full bg-gradient-to-r from-violet-700 to-indigo-700 animate-pulse bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-indigo-700 to-cyan-500 animate-pulse delay-150 bg-opacity-40"></span>
      <span class="w-full h-full bg-gradient-to-r from-cyan-500 to-violet-700 animate-pulse delay-300 bg-opacity-40"></span>
    </div>
  </a>
</div>
        </div>
    </div>
</nav>

<section class="p-0 m-0 box-border relative h-screen bg-black">
  <div id="hero div" class="relative bg-gray-900">
    <img loading="lazy" class="h-full w-full object-cover" src="https://images.unsplash.com/photo-1717426793419-2aef630b8435?q=80&w=1385&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" />
    <div class="absolute inset-0 top-20 z-20 xl:top-40">
         <div class="bg-opacity-50 p-4 rounded-md">
        <p data-aos="fade-up" data-aos-offset="100"
           data-aos-delay="100"
  data-aos-duration="1000"
  data-aos-easing="ease-in-out" class="z-20 bg-custom-gradient bg-clip-text py-4 pb-1 text-center text-xl text-transparent sm:text-3xl md:text-3xl lg:text-3xl xl:text-4xl ">
          One-stop Shopify Theme
        </p>
      </div>

      <div class="">
        <h1 class="z-20 text-center text-4xl font-bold text-white sm:py-4 sm:text-4xl md:text-4xl lg:text-7xl xl:py-5 xl:font-semibold">
          Prime Quality <br />
          Premium Design
        </h1>
      </div>
      <p class="z-20 p-5 py-7 text-center text-gray-400 md:pt-0 md:text-lg lg:py-5 xl:px-72 sm:px-36">Craft a beautiful and high-converting Shopify store with Kalles multipurpose theme.Optimized for eCommerce, speed and user experiences.</p>
      <div class="sm:absolute sm:left-[25%] sm:flex sm:flex-row sm:gap-4 md:absolute md:left-[25%] md:flex md:flex-row lg:absolute lg:left-[30%] xl:absolute xl:left-[35%] xl:py-7">
        <div class="flex">
          <div class="effect-custom m-auto rounded-2xl">
            <a href="sundhar" class="relative flex items-center justify-center gap-1 rounded-md border-2 py-2 border-gray-300 bg-black font-medium text-white backdrop-blur-3xl hover:bg-gray-800 sm:py-2 lg:py-3 md:py-3 xl:py-3">
              <i class="fa-solid fa-wand-magic-sparkles h-5 w-5 text-white"></i>
              <span class="cta_text z-10 text-white md:text-xl xl:text-xl">Explore Demos</span>
              <div class="absolute inset-0 flex items-center justify-center overflow-hidden">
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-violet-700 to-indigo-700"></span>
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-indigo-700 to-cyan-500 delay-150"></span>
                <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-cyan-500 to-violet-700 delay-300"></span>
              </div>
            </a>
          </div>
        </div>
        <div class="group flex items-center justify-center gap-1 py-4 font-bold text-white md:ml-10">
        <i class="fa-brands fa-shopify h-5 w-5 text-center text-white md:text-xl xl:text-2xl group-hover:text-cyan-600"></i>
        <span class="sm:text-lg md:text-xl lg:text-xl xl:text-xl group-hover:text-cyan-600">Open store free</span>
    </div>
      </div>
      <div class="relative md:py-16 xl:py-24">
        <p class="-mt-5 p-5 text-center text-gray-400 sm:py-20 sm:px-32 md:text-lg md:py-8 lg:py-14 xl:pt-7 xl:px-96">Get 3 months trial Shopify with 1$/month, exclusive Shopify deal for The4's customers</p>
      </div>
      <div class="bg-black"></div>
    </div>
    <svg viewBox="0 0 1240 1252" fill="none" xmlns="http://www.w3.org/2000/svg" class="absolute inset-0 z-10 h-full w-full">
      <g class="eff-1 eff" filter="url(#filter0_f_1390_2298)">
        <path d="M885.857 160.25L1024.14 911.075C1026.99 926.564 1042.13 936.591 1057.5 933.177V933.177C1072.87 929.763 1082.34 914.271 1078.37 899.031L885.857 160.25Z" fill="url(#paint0_linear_1390_2298)"></path>
      </g>
      <g class="eff-2 eff" filter="url(#filter1_f_1390_2298)">
        <path d="M353.786 160.25L215.507 911.075C212.655 926.564 197.517 936.591 182.143 933.177V933.177C166.768 929.763 157.298 914.271 161.269 899.031L353.786 160.25Z" fill="url(#paint1_linear_1390_2298)"></path>
      </g>
      <g class="eff-3 eff" filter="url(#filter2_f_1390_2298)">
        <path d="M620 163L648.095 1063.01C648.59 1078.87 635.868 1092 620 1092V1092C604.132 1092 591.41 1078.87 591.905 1063.01L620 163Z" fill="url(#paint2_linear_1390_2298)"></path>
      </g>
      <defs>
        <filter id="filter0_f_1390_2298" x="725.857" y="0.249634" width="513.422" height="1093.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <filter id="filter1_f_1390_2298" x="0.363525" y="0.249634" width="513.422" height="1093.6" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <filter id="filter2_f_1390_2298" x="431.891" y="3" width="376.218" height="1249" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
          <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
          <feBlend mode="normal" in="SourceGraphic" in2="BackgroundImageFix" result="shape"></feBlend>
          <feGaussianBlur stdDeviation="80" result="effect1_foregroundBlur_1390_2298"></feGaussianBlur>
        </filter>
        <linearGradient id="paint0_linear_1390_2298" x1="857.643" y1="178" x2="1057.5" y2="933.177" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
        <linearGradient id="paint1_linear_1390_2298" x1="382" y1="178" x2="182.143" y2="933.177" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
        <linearGradient id="paint2_linear_1390_2298" x1="651.578" y1="176.155" x2="608.641" y2="1091.47" gradientUnits="userSpaceOnUse">
          <stop stop-color="rgba(255,255,255,0.5)"></stop>
          <stop offset="1" stop-color="rgba(255,255,255,0.5)" stop-opacity="0.95"></stop>
        </linearGradient>
      </defs>
    </svg>
  </div>
  <div class=" bg-black">
    <div class="p-2 ml-auto lg:mr-16 xl:ml-40">
      <!-- Desktop view -->
      <div class="hidden lg:block lg:relative bg-bla">
        <div class="relative -top-28 w-[1000px] h-[700px] border-gray-900 shadow-lg border-t-[30px] border-l-[15px] border-r-[15px] border-b-[15px] rounded-xl xl:-top-48">
          <div id="border" class="shadow-x w-full h-full border border-gray-500 rounded-xl relative ">
            <div class="absolute top-[-20px] left-[5px] flex flex-row items-center">
              <div id="spandots" class="flex flex-row items-center gap-[5px]">
                <span class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"></span>
                <span class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"></span>
                <span class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"></span>
              </div>
            </div>
            <div id="content" class="flex justify-between pl-8">
              <div id="left" class="w-auto">
                <div id="logo" class="py-10 ml-2">
                  <a href="/">
<img loading="lazy" src="https://themes.the4.co/kalles-5/assets/images/logo/logo_white.svg" alt="Kalles logo brand" class="d-none">
<svg width="104" height="32" viewBox="0 0 104 32" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
<path id="bayleys" fill-rule="evenodd" clip-rule="evenodd" stroke-dasharray="1200 1000" d="M21.71 30.6424L12.7888 19.8206L21.516 8.99875H13.7206L7.24306 17.6872V1.93935H0.608398V30.6424H7.24112V21.4497L13.7206 30.6424H21.7109H21.71ZM28.7655 8.72723C27.073 8.70139 25.4092 9.16617 23.9752 10.0654C22.5236 11.0054 21.3672 12.3366 20.6394 13.9054C19.7855 15.7578 19.3675 17.7814 19.4176 19.8206C19.3715 21.8531 19.7893 23.8695 20.6394 25.7163C21.363 27.293 22.5199 28.6315 23.9752 29.5757C25.4092 30.475 27.073 30.9397 28.7655 30.9139C30.2661 30.9555 31.7471 30.565 33.0321 29.789C34.2032 29.0604 35.1235 27.9912 35.6697 26.7248V30.6424H42.2637V8.99487H35.6697V12.9124C35.1233 11.6462 34.203 10.577 33.0321 9.8482C31.7466 9.07376 30.2657 8.6847 28.7655 8.72723ZM30.8988 14.5454C31.5387 14.5245 32.1756 14.64 32.7675 14.8841C33.3593 15.1281 33.8924 15.4953 34.3315 15.9612C35.2666 17.0223 35.7472 18.4084 35.6697 19.8206C35.7406 21.226 35.2605 22.6036 34.3315 23.6606C33.8954 24.1315 33.3633 24.5034 32.7711 24.751C32.1788 24.9986 31.5404 25.1161 30.8988 25.0957C30.26 25.1221 29.623 25.0112 29.0308 24.7703C28.4386 24.5294 27.905 24.1642 27.4661 23.6994C26.5478 22.623 26.0821 21.2329 26.1667 19.8206C26.0822 18.4083 26.5479 17.0182 27.4661 15.9418C27.905 15.477 28.4386 15.1118 29.0308 14.8709C29.623 14.63 30.26 14.519 30.8988 14.5454ZM44.5715 1.93935V30.6424H51.2043V1.93935H44.5715ZM54.0474 1.93935V30.6424H60.6801V1.93935H54.0474ZM84.139 19.2387C84.1772 17.3241 83.716 15.4325 82.8009 13.7503C81.9249 12.1759 80.6113 10.8892 79.019 10.046C77.2577 9.17521 75.3186 8.72383 73.3537 8.7272C71.3888 8.73056 69.4514 9.18858 67.693 10.0654C66.057 10.9382 64.7147 12.2739 63.8336 13.9054C62.8784 15.7277 62.4045 17.7638 62.4566 19.8206C62.409 21.873 62.8898 23.9033 63.853 25.7163C64.7369 27.3506 66.0781 28.6918 67.7124 29.5757C69.3435 30.3999 71.136 30.8549 72.9626 30.9086C74.7893 30.9622 76.6055 30.6131 78.2821 29.886C79.7032 29.242 80.9523 28.2719 81.9281 27.0545C82.8783 25.8658 83.5181 24.4596 83.7899 22.9624H76.7693C76.5721 23.7234 76.1204 24.3941 75.4893 24.863C74.7797 25.3741 73.9196 25.6335 73.0457 25.6C71.9854 25.6391 70.9529 25.2554 70.1754 24.5333C69.3265 23.5659 68.8821 22.309 68.9342 21.023H83.9451C84.068 20.436 84.1329 19.8384 84.139 19.2387ZM77.4297 18.2303H68.974C68.9896 17.0326 69.4775 15.8895 70.3315 15.0497C71.164 14.314 72.2467 13.9254 73.357 13.9636C74.4336 13.9318 75.4815 14.3135 76.2855 15.0303C76.7 15.4465 77.0175 15.9492 77.2153 16.5024C77.4131 17.0555 77.4863 17.6455 77.4297 18.2303ZM93.3124 8.72723C91.0847 8.58676 88.8773 9.22429 87.0675 10.5309C86.3568 11.0894 85.7867 11.8065 85.4028 12.6249C85.0189 13.4432 84.8318 14.34 84.8566 15.2436C84.7841 16.5245 85.1844 17.7874 85.9815 18.7927C86.6994 19.6368 87.6204 20.2843 88.6578 20.6739C89.9479 21.1333 91.2703 21.4963 92.6142 21.76C93.8002 21.995 94.962 22.3391 96.0847 22.7878C96.4086 22.9108 96.6858 23.1322 96.8771 23.421C97.0685 23.7098 97.1644 24.0513 97.1514 24.3975C97.1612 24.6556 97.1141 24.9128 97.0136 25.1507C96.913 25.3886 96.7615 25.6016 96.5696 25.7745C96.0858 26.1556 95.4772 26.3423 94.8629 26.2981C93.9216 26.3398 92.9913 26.0818 92.2059 25.5612C91.8645 25.314 91.5816 24.9947 91.3772 24.6261C91.1727 24.2574 91.0518 23.8484 91.0229 23.4278H84.6229C84.7583 24.5215 85.1133 25.5766 85.6665 26.5298C86.2197 27.4829 86.9598 28.3145 87.8423 28.9745C89.9131 30.3591 92.3751 31.0392 94.8629 30.9139C96.4021 30.9499 97.9325 30.6728 99.3613 30.0993C100.524 29.6385 101.532 28.8586 102.27 27.8497C102.946 26.8845 103.299 25.7305 103.279 24.5527C103.348 23.2362 102.934 21.9398 102.115 20.9066C101.379 20.0297 100.431 19.3555 99.3613 18.9478C98.0303 18.4674 96.6699 18.0723 95.2886 17.7648C94.1384 17.5454 93.014 17.2074 91.9335 16.7563C91.622 16.644 91.3526 16.4386 91.1618 16.168C90.971 15.8974 90.868 15.5747 90.8668 15.2436C90.8519 14.9849 90.8966 14.7262 90.9975 14.4874C91.0984 14.2487 91.2527 14.0363 91.4486 13.8666C91.9433 13.5105 92.5472 13.3389 93.1553 13.3818C94.0137 13.3503 94.8565 13.6176 95.5398 14.1381C96.1843 14.6596 96.6183 15.3967 96.7616 16.2133H102.968C102.627 14.091 101.532 12.1628 99.884 10.783C98.0088 9.33585 95.678 8.60673 93.3124 8.72723Z" />
</svg>
</a>
                </div>
                <!-- Navigation -->
                <div
                  id="nav-home"
                  class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                  :class="{ 'border-gray-500 border text-white': activePage === 'home' }"
                  @click="changeImage ('home')"
                >
                  <div class="text-gray-400 flex items-center gap-3 p-2">
                    <div class="flex-wrap">
                      <i
                        class="fa-solid fa-house px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white"
                        :class="{ 'bg-blue-500 text-white': activePage === 'home' }"
                      ></i>
                    </div>
                    <span class="hover:text-white font-bold" :class="{ 'text-white': activePage === 'home' }">Home Page</span>
                    <div id="arrow" class="ml-auto hover:text-white active:text-white">
                      <svg
                        class="banner_icon_arrow text-gray-400 hover:text-white font-bold"
                        :class="{ 'text-white': activePage === 'home' }"
                        xmlns="http://www.w3.org/2000/svg"
                        width="12"
                        height="12"
                        viewBox="0 0 12 12"
                        fill="none"
                      >
                        <path
                          d="M4 9.99997L8 5.99997L4 1.99997"
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        ></path>
                      </svg>
                    </div>
                  </div>
                </div>

                <div
                  id="nav-product"
                  class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                  :class="{ 'border-gray-500 border text-white': activePage === 'product' }"
                  @click="changeImage('product')"
                >
                  <div class="text-gray-400 flex items-center gap-3 p-2">
                    <div class="flex-wrap">
                      <i
                        class="fa-solid fa-store px-2 py-1 border border-gray-500 rounded  hover:bg-blue-500 hover:text-white font-bold"
                        :class="{ 'bg-blue-500 text-white': activePage === 'product' }"
                      ></i>
                    </div>
                    <span class="hover:text-white font-bold" :class="{ 'text-white': activePage === 'product' }">Product Page</span>
                    <div id="arrow" class="ml-auto hover:text-white active:text-white">
                      <svg
                        class="banner_icon_arrow text-gray-400 hover:text-white"
                        :class="{ 'text-white': activePage === 'product' }"
                        xmlns="http://www.w3.org/2000/svg"
                        width="12"
                        height="12"
                        viewBox="0 0 12 12"
                        fill="none"
                      >
                        <path
                          d="M4 9.99997L8 5.99997L4 1.99997"
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        ></path>
                      </svg>
                    </div>
                  </div>
                </div>
                <div
                  id="nav-collection"
                  class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                  :class="{ 'border-gray-500 border  text-white': activePage === 'collection' }"
                  @click="changeImage('collection')"
                >
                  <div class="text-gray-400 flex items-center gap-3 p-2">
                    <div class="flex-wrap">
                      <i
                        class="fa-solid fa-list px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                        :class="{ 'bg-blue-500 text-white': activePage === 'collection' }"
                      ></i>
                    </div>
                    <span class="hover:text-white font-bold" :class="{ 'text-white': activePage === 'collection' }">Collection Page</span>
                    <div id="arrow" class="ml-auto hover:text-white active:text-white">
                      <svg
                        class="banner_icon_arrow text-gray-400 hover:text-white"
                         :class="{ 'text-white': activePage === 'collection' }"
                        xmlns="http://www.w3.org/2000/svg"
                        width="12"
                        height="12"
                        viewBox="0 0 12 12"
                        fill="none"
                      >
                        <path
                          d="M4 9.99997L8 5.99997L4 1.99997"
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        ></path>
                      </svg>
                    </div>
                  </div>
                </div>


                <div
                  id="nav-Blog"
                  class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                  :class="{ 'border-gray-500 border text-white': activePage === 'Blog' }"
                  @click="changeImage('Blog')"
                >
                  <div class="text-gray-400 flex items-center gap-3 p-2">
                    <div class="flex-wrap">
                      <i
                        class="fa-brands fa-blogger px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                        :class="{ 'bg-blue-500 text-white': activePage === 'Blog' }"
                      ></i>
                    </div>
                    <span class="hover:text-white font-bold" :class="{ 'text-white': activePage === 'Blog' }">Blog</span>
                    <div id="arrow" class="ml-auto hover:text-white active:text-white">
                      <svg
                        class="banner_icon_arrow text-gray-400 hover:text-white"
                         :class="{ 'text-white': activePage === 'Blog' }"
                        xmlns="http://www.w3.org/2000/svg"
                        width="12"
                        height="12"
                        viewBox="0 0 12 12"
                        fill="none"
                      >
                        <path
                          d="M4 9.99997L8 5.99997L4 1.99997"
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        ></path>
                      </svg>
                    </div>
                  </div>
                </div>


                <div
                  id="nav-More"
                  class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                  :class="{ 'border-gray-500 border text-white': activePage === 'More' }"
                  @click="changeImage('More')"
                >
                  <div class="text-gray-400 flex items-center gap-3 p-2">
                    <div class="flex-wrap">
                      <i
                        class="fa-solid fa-ellipsis px-2 py-1 border border-gray-500 rounded  hover:bg-blue-500 hover:text-white font-bold"
                        :class="{ 'bg-blue-500 text-white': activePage === 'More' }"
                      ></i>
                    </div>
                    <span class="hover:text-white font-bold" :class="{ 'text-white': activePage === 'More' }">More</span>
                    <div id="arrow" class="ml-auto hover:text-white active:text-white">
                      <svg
                        class="banner_icon_arrow text-gray-400 hover:text-white"
                         :class="{ 'text-white': activePage === 'More' }"
                        xmlns="http://www.w3.org/2000/svg"
                        width="12"
                        height="12"
                        viewBox="0 0 12 12"
                        fill="none"
                      >
                        <path
                          d="M4 9.99997L8 5.99997L4 1.99997"
                          stroke="currentColor"
                          stroke-linecap="round"
                          stroke-linejoin="round"
                        ></path>
                      </svg>
                    </div>
                  </div>
                </div>
                <!-- power lite -->
                 <div class="flex gap-3 p-4 mt-16 py-5 border border-gray-600 rounded-xl ">
                  <div>
                    <img class="" src="https://themes.the4.co/kalles-5/assets/images/banner/power_lite.svg"/>
                  </div>
                  <div class="flex flex-col">
                    <h1 class="text-white font-bold text-wrap">Power Elite Author on </h1>
                 <span><img loading="lazy" width="90" height="17" src="https://themes.the4.co/kalles-5/assets/images/banner/market.png" alt></span>
                  </div>
                 </div>
              </div>
              <!-- right content -->
          <div
                id="right"
                class="py-5 px-5 mt-36 mr-10 ml-5 border border-gray-500 rounded-lg right-content flex justify-end"
              >
             <div id="desktopmobile" class="flex gap-3 items-center absolute top-[23%] left-[62%] border border-gray-500 rounded-lg py-2 px-3">
<i class="fa-solid fa-desktop px-1 py-1 rounded-md text-white cursor-pointer"
   :class="{ 'bg-blue-500 border-gray-500 border text-white': activePage === 'desktop' }"
   @click="changeImage('desktop')"></i>
<i class="fa-solid fa-mobile  px-1 py-1 rounded-md text-white cursor-pointer"
   :class="{ 'bg-blue-500 border-gray-500 border text-white': activePage === 'mobile' }"
   @click="changeImage('mobile')"></i>
</div>

                <img
                  :src="bannerImage"
                  alt="Banner Image"
                  class="right-ima
                  ge w-[550px] h-[430px] object-cover rounded-xl p- mt-8"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Mobile view -->
  <div class="flex flex-col">
    <!-- video -->
      <div id="bgvideo" class="-mt-3 p-5 bg-black py-10 order-2 lg:hidden-none">
<div id="bgvideo" class="m-auto relative w-full h-[500px] rounded-2xl shadow-3xl bg-gray-900 xl:w-full xl:py-24 xl:-top-20">
  <video class=" p-5 rounded-3xll w-full h-full xl:w-screen xl:h-[450px] xl:-mt-16 object-cover" autoplay muted loop src="https://themes.the4.co/kalles-5/assets/video/video_bg.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <div class="absolute inset-0 flex flex-col items-center justify-center top-11">
    <div class="py-2">
      <img src="https://themes.the4.co/kalles-5/assets/images/banner/head.png" alt="">
    </div>
    <h1 class="text-white text-wrap text-center font-bold text-2xl">Commerce Coach Certificate</h1>
    <div class="flex items-center gap-3 mt-3">
      <span class="text-white text-2xl font-bold">from</span>
      <img src="https://themes.the4.co/kalles-5/assets/images/banner/shopify_brands.png">
    </div>
    <div class="flex-none mt-4">
      <a href="" class="text-white underline">Learn more</a>
    </div>
    <div class="groupicon flex mt-4 p-4">
      <div class="flex flex-col items-center cursor-pointer group">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
          <g clip-path="url(#clip0_1240_1680)">
            <path d="M30 22.5C30 23.6 29.3 25 28.3 25.6L16.6 33.4C15.7 34 14.2 34 13.3 33.4L1.7 25.6C0.7 25 0 23.6 0 22.5V11.5C0 10.4 0.7 9.00002 1.7 8.40002L13.4 0.600024C14.3 2.44081e-05 15.8 2.44081e-05 16.7 0.600024L28.4 8.40002C29.3 9.00002 30.1 10.4 30.1 11.5V22.5H30Z" fill="#72BF40" />
            <path d="M9 10H21V13H9V10ZM6 15H24V18H6V15ZM3 20H27V23H3V20Z" fill="white" />
          </g>
          <defs>
            <clipPath id="clip0_1240_1680">
              <rect width="30" height="34" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span class="text-white invisible group-hover:visible">Power Elite Author</span>
      </div>


      <div class="flex flex-col items-center gap-2 cursor-pointer group">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
          <g clip-path="url(#clip0_1240_1680)">
            <path d="M30 22.5C30 23.6 29.3 25 28.3 25.6L16.6 33.4C15.7 34 14.2 34 13.3 33.4L1.7 25.6C0.7 25 0 23.6 0 22.5V11.5C0 10.4 0.7 9.00002 1.7 8.40002L13.4 0.600024C14.3 2.44081e-05 15.8 2.44081e-05 16.7 0.600024L28.4 8.40002C29.3 9.00002 30.1 10.4 30.1 11.5V22.5H30Z" fill="#72BF40" />
            <path d="M9 10H21V13H9V10ZM6 15H24V18H6V15ZM3 20H27V23H3V20Z" fill="white" />
          </g>
          <defs>
            <clipPath id="clip0_1240_1680">
              <rect width="30" height="34" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span class="text-white invisible group-hover:visible text-wrap">Power Elite Author</span>
      </div>


       <div class="flex flex-col items-center gap-2 cursor-pointer group">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
          <g clip-path="url(#clip0_1240_1680)">
            <path d="M30 22.5C30 23.6 29.3 25 28.3 25.6L16.6 33.4C15.7 34 14.2 34 13.3 33.4L1.7 25.6C0.7 25 0 23.6 0 22.5V11.5C0 10.4 0.7 9.00002 1.7 8.40002L13.4 0.600024C14.3 2.44081e-05 15.8 2.44081e-05 16.7 0.600024L28.4 8.40002C29.3 9.00002 30.1 10.4 30.1 11.5V22.5H30Z" fill="#72BF40" />
            <path d="M9 10H21V13H9V10ZM6 15H24V18H6V15ZM3 20H27V23H3V20Z" fill="white" />
          </g>
          <defs>
            <clipPath id="clip0_1240_1680">
              <rect width="30" height="34" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span class="text-white invisible group-hover:visible text-wrap">Power Elite Author</span>
      </div>


       <div class="flex flex-col items-center gap-2 cursor-pointer group">
        <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
          <g clip-path="url(#clip0_1240_1680)">
            <path d="M30 22.5C30 23.6 29.3 25 28.3 25.6L16.6 33.4C15.7 34 14.2 34 13.3 33.4L1.7 25.6C0.7 25 0 23.6 0 22.5V11.5C0 10.4 0.7 9.00002 1.7 8.40002L13.4 0.600024C14.3 2.44081e-05 15.8 2.44081e-05 16.7 0.600024L28.4 8.40002C29.3 9.00002 30.1 10.4 30.1 11.5V22.5H30Z" fill="#72BF40" />
            <path d="M9 10H21V13H9V10ZM6 15H24V18H6V15ZM3 20H27V23H3V20Z" fill="white" />
          </g>
          <defs>
            <clipPath id="clip0_1240_1680">
              <rect width="30" height="34" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span class="text-white invisible group-hover:visible text-wrap">Power Elite Author</span>
      </div>
    </div>
  </div>
</div>
</div>
    <div class="lg:hidden order-1 xs:mt-74">
    <div class="bg-black m-auto">
      <img
        src="https://themes.the4.co/kalles-5/assets/images/banner/banner_mobile.png"
        class="p-5 mt-34 sm:mt-10 md:mt-0 object-cover rounded-xl cursor-none shadow-2xl"
      />
    </div>
  </div>

  </div>

</section>
</template>

<script setup>
import { ref } from "vue";

const activePage = ref("home");
const bannerImage = ref("https://themes.the4.co/kalles-5/assets/images/banner/layout/h_d_1.jpg");

const images = {
home: "https://themes.the4.co/kalles-5/assets/images/banner/layout/h_d_1.jpg",
product: "https://themes.the4.co/kalles-5/assets/images/banner/layout/p_d_1.jpg",
collection: "https://themes.the4.co/kalles-5/assets/images/banner/layout/c_d_1.jpg",
Blog: "https://themes.the4.co/kalles-5/assets/images/banner/layout/c_d_2.jpg",
More: "https://themes.the4.co/kalles-5/assets/images/banner/layout/c_d_3.jpg",
desktop: "https://themes.the4.co/kalles-5/assets/images/banner/layout/c_d_3.jpg", 
mobile: "https://themes.the4.co/kalles-5/assets/images/banner/layout/p_d_1.jpg",
};
const changeImage = (page) => {
activePage.value = page;
bannerImage.value = images[page];
};
</script>





<style>
.effect-custom div::before,
.effect-custom div::after {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
  top: 0;
  left: 0;
  background: linear-gradient(270deg, #ff8a00, #e52e71, #7d00ff, #00f9ff, #ff8a00);
  background-size: 400% 100%;
  animation: moveLeftRight 5s ease-in-out infinite;
}

.effect-custom div::after {
  filter: blur(10px);
  z-index: -1;
}

.effect-custom:hover > div > span {
  animation-play-state: paused;
}
.bg-custom-gradient {
          background-image: linear-gradient(81deg, #CE1BFB 10.86%, #35E6CC 89.96%);
        }

@keyframes moveLeftRight {
  0%, 100% { transform: translateX(-100%); }
  50% { transform: translateX(100%); }
}

g.eff {
  animation: line-eff 3s infinite;
  transform-origin: 50% 100%;
  filter: blur(70px);
}

.eff-1 {
  animation-delay: 0.3s;
}

.eff-2 {
  animation-delay: 0.5s;
}

.eff-3 {
  animation-delay: 0.7s;
}

@keyframes line-eff {
  0%,
  100% {
    opacity: 0;
    transform: rotate(0) scale(1) translate3d(0, 0, 0);
  }
  50% {
    opacity: 1;
    transform: rotate(0) scale(1) translate3d(0, 0, 300px);
  }
}
</style>