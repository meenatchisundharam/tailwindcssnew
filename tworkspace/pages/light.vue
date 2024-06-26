<template>
  <nav class="p-5 sticky top-0 z-50 bg-black">
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
         href="/"
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
     <img
       loading="lazy"
       class="h-full w-full object-cover absolute top-0 left-0"
       src="https://images.unsplash.com/photo-1717426793419-2aef630b8435?q=80&w=1385&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D"
     />
     <div class="relative">
       <div class="bg-opacity-50 p-4 rounded-md">
         <p
           data-aos="fade-up"
           data-aos-offset="100"
           data-aos-delay="100"
           data-aos-duration="1000"
           data-aos-easing="ease-in-out"
           class="pt-9 z-20 bg-custom-gradient bg-clip-text py-4 pb-1 text-center text-xl text-transparent sm:text-3xl md:text-3xl lg:text-3xl xl:text-4xl"
         >
           One-stop Shopify Theme
         </p>
       </div>

       <div class="">
         <h1
           class="z-20 text-center text-4xl font-bold text-white sm:py-4 sm:text-4xl md:text-4xl lg:text-7xl xl:py-5 xl:font-semibold"
         >
           Prime Quality <br />
           Premium Design
         </h1>
       </div>
       <p
         class="z-20 p-5 py-7 text-center text-gray-400 md:pt-0 md:text-lg lg:py-5 xl:px-72 sm:px-36"
       >
         Craft a beautiful and high-converting Shopify store with Kalles
         multipurpose theme.Optimized for eCommerce, speed and user
         experiences.
       </p>
       <div
         class="sm:absolute sm:left-[25%] sm:flex sm:flex-row sm:gap-4 md:absolute md:left-[25%] md:flex md:flex-row lg:absolute lg:left-[30%] xl:absolute xl:left-[35%] xl:py-7"
       >
         <div class="flex">
           <div class="effect-custom m-auto rounded-2xl">
             <a
               href="sundhar"
               class="relative flex items-center justify-center gap-1 rounded-md border-2 py-2 border-gray-300 bg-black font-medium text-white backdrop-blur-3xl hover:bg-gray-800 sm:py-2 lg:py-3 md:py-3 xl:py-3"
             >
               <i
                 class="fa-solid fa-wand-magic-sparkles h-5 w-5 text-white"
               ></i>
               <span class="cta_text z-10 text-white md:text-xl xl:text-xl"
                 >Explore Demos</span
               >
               <div
                 class="absolute inset-0 flex items-center justify-center overflow-hidden"
               >
                 <span
                   class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-violet-700 to-indigo-700"
                 ></span>
                 <span
                   class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-indigo-700 to-cyan-500 delay-150"
                 ></span>
                 <span
                   class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-cyan-500 to-violet-700 delay-300"
                 ></span>
               </div>
             </a>
           </div>
         </div>
         <div
           class="group flex items-center justify-center gap-1 py-4 font-bold text-white md:ml-10"
         >
           <i
             class="fa-brands fa-shopify h-5 w-5 text-center text-white md:text-xl xl:text-2xl group-hover:text-cyan-600"
           ></i>
           <span
             class="sm:text-lg md:text-xl lg:text-xl xl:text-xl group-hover:text-cyan-600"
             >Open store free</span
           >
         </div>
       </div>
       <div class="relative md:py-16 xl:py-24">
         <p
           class="-mt-5 p-5 text-center text-gray-400 sm:py-20 sm:px-32 md:text-lg md:py-8 lg:py-14 xl:pt-7 xl:px-96"
         >
           Get 3 months trial Shopify with 1$/month, exclusive Shopify deal for
           The4's customers
         </p>
       </div>
       <div class="bg-black"></div>
     </div>
     <svg
       viewBox="0 0 1240 1252"
       fill="none"
       xmlns="http://www.w3.org/2000/svg"
       class="absolute inset-0 z-10 h-full w-full"
     >
       <g class="eff-1 eff" filter="url(#filter0_f_1390_2298)">
         <path
           d="M885.857 160.25L1024.14 911.075C1026.99 926.564 1042.13 936.591 1057.5 933.177V933.177C1072.87 929.763 1082.34 914.271 1078.37 899.031L885.857 160.25Z"
           fill="url(#paint0_linear_1390_2298)"
         ></path>
       </g>
       <g class="eff-2 eff" filter="url(#filter1_f_1390_2298)">
         <path
           d="M353.786 160.25L215.507 911.075C212.655 926.564 197.517 936.591 182.143 933.177V933.177C166.768 929.763 157.298 914.271 161.269 899.031L353.786 160.25Z"
           fill="url(#paint1_linear_1390_2298)"
         ></path>
       </g>
       <g class="eff-3 eff" filter="url(#filter2_f_1390_2298)">
         <path
           d="M620 163L648.095 1063.01C648.59 1078.87 635.868 1092 620 1092V1092C604.132 1092 591.41 1078.87 591.905 1063.01L620 163Z"
           fill="url(#paint2_linear_1390_2298)"
         ></path>
       </g>
       <defs>
         <filter
           id="filter0_f_1390_2298"
           x="725.857"
           y="0.249634"
           width="513.422"
           height="1093.6"
           filterUnits="userSpaceOnUse"
           color-interpolation-filters="sRGB"
         >
           <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
           <feBlend
             mode="normal"
             in="SourceGraphic"
             in2="BackgroundImageFix"
             result="shape"
           ></feBlend>
           <feGaussianBlur
             stdDeviation="80"
             result="effect1_foregroundBlur_1390_2298"
           ></feGaussianBlur>
         </filter>
         <filter
           id="filter1_f_1390_2298"
           x="0.363525"
           y="0.249634"
           width="513.422"
           height="1093.6"
           filterUnits="userSpaceOnUse"
           color-interpolation-filters="sRGB"
         >
           <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
           <feBlend
             mode="normal"
             in="SourceGraphic"
             in2="BackgroundImageFix"
             result="shape"
           ></feBlend>
           <feGaussianBlur
             stdDeviation="80"
             result="effect1_foregroundBlur_1390_2298"
           ></feGaussianBlur>
         </filter>
         <filter
           id="filter2_f_1390_2298"
           x="431.891"
           y="3"
           width="376.218"
           height="1249"
           filterUnits="userSpaceOnUse"
           color-interpolation-filters="sRGB"
         >
           <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
           <feBlend
             mode="normal"
             in="SourceGraphic"
             in2="BackgroundImageFix"
             result="shape"
           ></feBlend>
           <feGaussianBlur
             stdDeviation="80"
             result="effect1_foregroundBlur_1390_2298"
           ></feGaussianBlur>
         </filter>
         <linearGradient
           id="paint0_linear_1390_2298"
           x1="857.643"
           y1="178"
           x2="1057.5"
           y2="933.177"
           gradientUnits="userSpaceOnUse"
         >
           <stop stop-color="rgba(255,255,255,0.5)"></stop>
           <stop
             offset="1"
             stop-color="rgba(255,255,255,0.5)"
             stop-opacity="0.95"
           ></stop>
         </linearGradient>
         <linearGradient
           id="paint1_linear_1390_2298"
           x1="382"
           y1="178"
           x2="182.143"
           y2="933.177"
           gradientUnits="userSpaceOnUse"
         >
           <stop stop-color="rgba(255,255,255,0.5)"></stop>
           <stop
             offset="1"
             stop-color="rgba(255,255,255,0.5)"
             stop-opacity="0.95"
           ></stop>
         </linearGradient>
         <linearGradient
           id="paint2_linear_1390_2298"
           x1="651.578"
           y1="176.155"
           x2="608.641"
           y2="1091.47"
           gradientUnits="userSpaceOnUse"
         >
           <stop stop-color="rgba(255,255,255,0.5)"></stop>
           <stop
             offset="1"
             stop-color="rgba(255,255,255,0.5)"
             stop-opacity="0.95"
           ></stop>
         </linearGradient>
       </defs>
     </svg>
   </div>

   <div class="bg-black hidden lg:block">
     <div class="p-2 ml-auto lg:mr-16 xl:ml-40">
       <!-- Desktop view -->
       <div class="lg:relative">
         <div
           class="relative w-[1000px] h-[700px] border-gray-900 shadow-lg border-t-[30px] border-l-[15px] border-r-[15px] border-b-[15px] rounded-xl"
         >
           <div
             id="border"
             class="shadow-x w-full h-full border border-gray-500 rounded-xl relative"
           >
             <div
               class="absolute top-[-20px] left-[5px] flex flex-row items-center"
             >
               <div id="spandots" class="flex flex-row items-center gap-[5px]">
                 <span
                   class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"
                 ></span>
                 <span
                   class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"
                 ></span>
                 <span
                   class="h-[10px] w-[10px] border-[1px] border-gray-500 rounded-full"
                 ></span>
               </div>
             </div>
             <div id="content" class="flex justify-between pl-8">
               <div id="left" class="w-auto">
                 <div id="logo" class="py-10 ml-2">
                   <a href="/">
                     <img
                       loading="lazy"
                       src="https://themes.the4.co/kalles-5/assets/images/logo/logo_white.svg"
                       alt="Kalles logo brand"
                       class="d-none"
                     />
                     <svg
                       width="104"
                       height="32"
                       viewBox="0 0 104 32"
                       fill="currentColor"
                       xmlns="http://www.w3.org/2000/svg"
                     >
                       <path
                         id="bayleys"
                         fill-rule="evenodd"
                         clip-rule="evenodd"
                         stroke-dasharray="1200 1000"
                         d="M21.71 30.6424L12.7888 19.8206L21.516 8.99875H13.7206L7.24306 17.6872V1.93935H0.608398V30.6424H7.24112V21.4497L13.7206 30.6424H21.7109H21.71ZM28.7655 8.72723C27.073 8.70139 25.4092 9.16617 23.9752 10.0654C22.5236 11.0054 21.3672 12.3366 20.6394 13.9054C19.7855 15.7578 19.3675 17.7814 19.4176 19.8206C19.3715 21.8531 19.7893 23.8695 20.6394 25.7163C21.363 27.293 22.5199 28.6315 23.9752 29.5757C25.4092 30.475 27.073 30.9397 28.7655 30.9139C30.2661 30.9555 31.7471 30.565 33.0321 29.789C34.2032 29.0604 35.1235 27.9912 35.6697 26.7248V30.6424H42.2637V8.99487H35.6697V12.9124C35.1233 11.6462 34.203 10.577 33.0321 9.8482C31.7466 9.07376 30.2657 8.6847 28.7655 8.72723ZM30.8988 14.5454C31.5387 14.5245 32.1756 14.64 32.7675 14.8841C33.3593 15.1281 33.8924 15.4953 34.3315 15.9612C35.2666 17.0223 35.7472 18.4084 35.6697 19.8206C35.7406 21.226 35.2605 22.6036 34.3315 23.6606C33.8954 24.1315 33.3633 24.5034 32.7711 24.751C32.1788 24.9986 31.5404 25.1161 30.8988 25.0957C30.26 25.1221 29.623 25.0112 29.0308 24.7703C28.4386 24.5294 27.905 24.1642 27.4661 23.6994C26.5478 22.623 26.0821 21.2329 26.1667 19.8206C26.0822 18.4083 26.5479 17.0182 27.4661 15.9418C27.905 15.477 28.4386 15.1118 29.0308 14.8709C29.623 14.63 30.26 14.519 30.8988 14.5454ZM44.5715 1.93935V30.6424H51.2043V1.93935H44.5715ZM54.0474 1.93935V30.6424H60.6801V1.93935H54.0474ZM84.139 19.2387C84.1772 17.3241 83.716 15.4325 82.8009 13.7503C81.9249 12.1759 80.6113 10.8892 79.019 10.046C77.2577 9.17521 75.3186 8.72383 73.3537 8.7272C71.3888 8.73056 69.4514 9.18858 67.693 10.0654C66.057 10.9382 64.7147 12.2739 63.8336 13.9054C62.8784 15.7277 62.4045 17.7638 62.4566 19.8206C62.409 21.873 62.8898 23.9033 63.853 25.7163C64.7369 27.3506 66.0781 28.6918 67.7124 29.5757C69.3435 30.3999 71.136 30.8549 72.9626 30.9086C74.7893 30.9622 76.6055 30.6131 78.2821 29.886C79.7032 29.242 80.9523 28.2719 81.9281 27.0545C82.8783 25.8658 83.5181 24.4596 83.7899 22.9624H76.7693C76.5721 23.7234 76.1204 24.3941 75.4893 24.863C74.7797 25.3741 73.9196 25.6335 73.0457 25.6C71.9854 25.6391 70.9529 25.2554 70.1754 24.5333C69.3265 23.5659 68.8821 22.309 68.9342 21.023H83.9451C84.068 20.436 84.1329 19.8384 84.139 19.2387ZM77.4297 18.2303H68.974C68.9896 17.0326 69.4775 15.8895 70.3315 15.0497C71.164 14.314 72.2467 13.9254 73.357 13.9636C74.4336 13.9318 75.4815 14.3135 76.2855 15.0303C76.7 15.4465 77.0175 15.9492 77.2153 16.5024C77.4131 17.0555 77.4863 17.6455 77.4297 18.2303ZM93.3124 8.72723C91.0847 8.58676 88.8773 9.22429 87.0675 10.5309C86.3568 11.0894 85.7867 11.8065 85.4028 12.6249C85.0189 13.4432 84.8318 14.34 84.8566 15.2436C84.7841 16.5245 85.1844 17.7874 85.9815 18.7927C86.6994 19.6368 87.6204 20.2843 88.6578 20.6739C89.9479 21.1333 91.2703 21.4963 92.6142 21.76C93.8002 21.995 94.962 22.3391 96.0847 22.7878C96.4086 22.9108 96.6858 23.1322 96.8771 23.421C97.0685 23.7098 97.1644 24.0513 97.1514 24.3975C97.1612 24.6556 97.1141 24.9128 97.0136 25.1507C96.913 25.3886 96.7615 25.6016 96.5696 25.7745C96.0858 26.1556 95.4772 26.3423 94.8629 26.2981C93.9216 26.3398 92.9913 26.0818 92.2059 25.5612C91.8645 25.314 91.5816 24.9947 91.3772 24.6261C91.1727 24.2574 91.0518 23.8484 91.0229 23.4278H84.6229C84.7583 24.5215 85.1133 25.5766 85.6665 26.5298C86.2197 27.4829 86.9598 28.3145 87.8423 28.9745C89.9131 30.3591 92.3751 31.0392 94.8629 30.9139C96.4021 30.9499 97.9325 30.6728 99.3613 30.0993C100.524 29.6385 101.532 28.8586 102.27 27.8497C102.946 26.8845 103.299 25.7305 103.279 24.5527C103.348 23.2362 102.934 21.9398 102.115 20.9066C101.379 20.0297 100.431 19.3555 99.3613 18.9478C98.0303 18.4674 96.6699 18.0723 95.2886 17.7648C94.1384 17.5454 93.014 17.2074 91.9335 16.7563C91.622 16.644 91.3526 16.4386 91.1618 16.168C90.971 15.8974 90.868 15.5747 90.8668 15.2436C90.8519 14.9849 90.8966 14.7262 90.9975 14.4874C91.0984 14.2487 91.2527 14.0363 91.4486 13.8666C91.9433 13.5105 92.5472 13.3389 93.1553 13.3818C94.0137 13.3503 94.8565 13.6176 95.5398 14.1381C96.1843 14.6596 96.6183 15.3967 96.7616 16.2133H102.968C102.627 14.091 101.532 12.1628 99.884 10.783C98.0088 9.33585 95.678 8.60673 93.3124 8.72723Z"
                       />
                     </svg>
                   </a>
                 </div>
                 <!-- Navigation -->
                 <div
                   id="nav-home"
                   class="my-2 hover:border rounded-lg border-gray-500 active:current cursor-pointer"
                   :class="{
                     'border-gray-500 border text-white':
                       activePage === 'home',
                   }"
                   @click="changeImage('home')"
                 >
                   <div class="text-gray-400 flex items-center gap-3 p-2">
                     <div class="flex-wrap">
                       <i
                         class="fa-solid fa-house px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white"
                         :class="{
                           'bg-blue-500 text-white': activePage === 'home',
                         }"
                       ></i>
                     </div>
                     <span
                       class="hover:text-white font-bold"
                       :class="{ 'text-white': activePage === 'home' }"
                       >Home Page</span
                     >
                     <div
                       id="arrow"
                       class="ml-auto hover:text-white active:text-white"
                     >
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
                   :class="{
                     'border-gray-500 border text-white':
                       activePage === 'product',
                   }"
                   @click="changeImage('product')"
                 >
                   <div class="text-gray-400 flex items-center gap-3 p-2">
                     <div class="flex-wrap">
                       <i
                         class="fa-solid fa-store px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                         :class="{
                           'bg-blue-500 text-white': activePage === 'product',
                         }"
                       ></i>
                     </div>
                     <span
                       class="hover:text-white font-bold"
                       :class="{ 'text-white': activePage === 'product' }"
                       >Product Page</span
                     >
                     <div
                       id="arrow"
                       class="ml-auto hover:text-white active:text-white"
                     >
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
                   :class="{
                     'border-gray-500 border  text-white':
                       activePage === 'collection',
                   }"
                   @click="changeImage('collection')"
                 >
                   <div class="text-gray-400 flex items-center gap-3 p-2">
                     <div class="flex-wrap">
                       <i
                         class="fa-solid fa-list px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                         :class="{
                           'bg-blue-500 text-white':
                             activePage === 'collection',
                         }"
                       ></i>
                     </div>
                     <span
                       class="hover:text-white font-bold"
                       :class="{ 'text-white': activePage === 'collection' }"
                       >Collection Page</span
                     >
                     <div
                       id="arrow"
                       class="ml-auto hover:text-white active:text-white"
                     >
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
                   :class="{
                     'border-gray-500 border text-white':
                       activePage === 'Blog',
                   }"
                   @click="changeImage('Blog')"
                 >
                   <div class="text-gray-400 flex items-center gap-3 p-2">
                     <div class="flex-wrap">
                       <i
                         class="fa-brands fa-blogger px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                         :class="{
                           'bg-blue-500 text-white': activePage === 'Blog',
                         }"
                       ></i>
                     </div>
                     <span
                       class="hover:text-white font-bold"
                       :class="{ 'text-white': activePage === 'Blog' }"
                       >Blog</span
                     >
                     <div
                       id="arrow"
                       class="ml-auto hover:text-white active:text-white"
                     >
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
                   :class="{
                     'border-gray-500 border text-white':
                       activePage === 'More',
                   }"
                   @click="changeImage('More')"
                 >
                   <div class="text-gray-400 flex items-center gap-3 p-2">
                     <div class="flex-wrap">
                       <i
                         class="fa-solid fa-ellipsis px-2 py-1 border border-gray-500 rounded hover:bg-blue-500 hover:text-white font-bold"
                         :class="{
                           'bg-blue-500 text-white': activePage === 'More',
                         }"
                       ></i>
                     </div>
                     <span
                       class="hover:text-white font-bold"
                       :class="{ 'text-white': activePage === 'More' }"
                       >More</span
                     >
                     <div
                       id="arrow"
                       class="ml-auto hover:text-white active:text-white"
                     >
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
                 <div
                   class="flex gap-3 p-4 mt-16 py-5 border border-gray-600 rounded-xl"
                 >
                   <div>
                     <img
                       class=""
                       src="https://themes.the4.co/kalles-5/assets/images/banner/power_lite.svg"
                     />
                   </div>
                   <div class="flex flex-col">
                     <h1 class="text-white font-bold text-wrap">
                       Power Elite Author on
                     </h1>
                     <span
                       ><img
                         loading="lazy"
                         width="90"
                         height="17"
                         src="https://themes.the4.co/kalles-5/assets/images/banner/market.png"
                         alt
                     /></span>
                   </div>
                 </div>
               </div>
               <!-- right content -->
               <div
                 id="right"
                 class="py-5 px-5 mt-36 mr-10 ml-5 border border-gray-500 rounded-lg right-content flex justify-end"
               >
                 <div
                   id="desktopmobile"
                   class="flex gap-3 items-center absolute top-[23%] left-[62%] border border-gray-500 rounded-lg py-2 px-3"
                 >
                   <i
                     class="fa-solid fa-desktop px-1 py-1 rounded-md text-white cursor-pointer"
                     :class="{
                       'bg-blue-500 border-gray-500 border text-white':
                         activePage === 'desktop',
                     }"
                     @click="changeImage('desktop')"
                   ></i>
                   <i
                     class="fa-solid fa-mobile px-1 py-1 rounded-md text-white cursor-pointer"
                     :class="{
                       'bg-blue-500 border-gray-500 border text-white':
                         activePage === 'mobile',
                     }"
                     @click="changeImage('mobile')"
                   ></i>
                 </div>

                 <img
                   :src="bannerImage"
                   alt="Banner Image"
                   class="right-ima ge w-[550px] h-[430px] object-cover rounded-xl p- mt-8"
                 />
               </div>
             </div>
           </div>
         </div>
       </div>
     </div>
   </div>

   <!-- Mobile view -->
   <div class="bg-black">
     <img
     src="https://themes.the4.co/kalles-5/assets/images/banner/banner_mobile.png"
     class="p-5 mt-34 sm:mt-10 md:-mt-1 object-cover rounded-xl cursor-none shadow-2xl bg-black lg:hidden"
   />
   </div>

   <div class="">
     <!-- video -->
     <div id="bgvideo" class="-mt-3 p-5 bg-black py-10 order-2 ">
       <div
         id="bgvideo"
         class="m-auto relative w-full h-[500px] rounded-2xl shadow-3xl bg-gray-900 xl:w-full xl:py-24"
       >
         <video
           class="p-5 rounded-3xll w-full h-full xl:w-screen xl:h-[450px] xl:-mt-16 object-cover"
           autoplay
           muted
           loop
           src="https://themes.the4.co/kalles-5/assets/video/video_bg.mp4"
           type="video/mp4"
         >
           Your browser does not support the video tag.
         </video>
         <div
           class="absolute inset-0 flex flex-col items-center justify-center top-11"
         >
           <div class="py-2">
             <img
               src="https://themes.the4.co/kalles-5/assets/images/banner/head.png"
               alt=""
             />
           </div>
           <h1 class="text-white text-wrap text-center font-bold text-2xl">
             Commerce Coach Certificate
           </h1>
           <div class="flex items-center gap-3 mt-3">
             <span class="text-white text-2xl font-bold">from</span>
             <img
               src="https://themes.the4.co/kalles-5/assets/images/banner/shopify_brands.png"
             />
           </div>
           <div class="flex-none mt-4">
             <a href="" class="text-white underline">Learn more</a>
           </div>
           <div class="grid grid-cols-4 lg:grid-cols-8 mt-4 p-4">
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
       <span class="text-sm text-center text-white invisible group-hover:visible">Power <br>Elite <br>Author</span>
     </div>

             <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="32" height="36" viewBox="0 0 32 36" fill="none">
<g clip-path="url(#clip0_1240_1684)">
<path d="M31.9936 23.5897C31.9936 24.7476 31.1412 26.2299 30.0773 26.8597L17.6439 35.092C16.689 35.7281 15.0931 35.7281 14.1382 35.092L1.80733 26.8597C0.743442 26.2235 0 24.7476 0 23.5897V11.9794C0 10.8215 0.743442 9.33919 1.80733 8.70937L14.2471 0.477139C15.2021 -0.159046 16.7979 -0.159046 17.7529 0.477139L30.1927 8.70937C31.1476 9.34556 32 10.8215 32 11.9794V23.5897H31.9936Z" fill="#99C267" />
<path d="M29.101 26.0835C30.088 25.5045 30.8699 24.1558 30.8699 23.0934V12.5009C30.8699 11.4385 30.0815 10.0898 29.1971 9.51084L17.6866 1.9975C17.2316 1.70486 16.6291 1.55853 16.0203 1.5649V34.0358C16.5907 34.0294 17.1547 33.8831 17.5841 33.6032L29.101 26.0835Z" fill="#80B341" />
<path d="M17.5615 21.6556H16.0298V14.7276H15.9785L13.9917 15.9872V14.5876L16.0938 13.2452H17.5551V21.6556H17.5615Z" fill="white" />
<path d="M19.797 13.2452H23.0399C24.8793 13.2452 25.783 14.1741 25.783 15.4274C25.783 16.4516 25.1293 17.0242 24.3025 17.215V17.2977C25.2062 17.3423 26.1162 18.093 26.1162 19.3653C26.1162 20.6759 25.1677 21.6556 23.2258 21.6556H19.797V13.2452ZM22.8477 16.8206C23.6488 16.8206 24.2512 16.3625 24.2512 15.6246C24.2512 14.9757 23.7834 14.5049 22.8797 14.5049H21.3287V16.827H22.8477V16.8206ZM22.9823 20.3832C24.0974 20.3832 24.5589 19.9125 24.5589 19.2445C24.5589 18.4938 23.9692 17.9212 23.0271 17.9212H21.3352V20.3832H22.9823Z" fill="white" />
<path d="M11.4015 13.519C10.2222 12.1448 6.39607 14.8104 6.4153 18.2458C6.4153 18.284 6.40248 18.3158 6.38325 18.3413C6.36402 18.3667 6.33198 18.3922 6.29994 18.3985C6.26789 18.4049 6.22944 18.4049 6.19739 18.3922C6.16535 18.3794 6.13971 18.354 6.12048 18.3285C5.72313 17.4761 5.67186 16.5091 5.97949 15.6248C5.9923 15.5929 5.9923 15.5548 5.98589 15.5166C5.97308 15.4848 5.94744 15.453 5.9154 15.4339C5.88335 15.4148 5.8449 15.4085 5.81285 15.4148C5.7744 15.4212 5.74235 15.4403 5.72313 15.4721C5.08864 16.1528 4.74255 17.0434 4.74255 17.9659C4.74255 20.3834 6.76138 21.6876 8.45335 21.6494C13.6638 21.5349 12.459 14.7468 11.4015 13.519Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1684">
<rect width="32" height="36" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-sm text-center text-white invisible group-hover:visible text-wrap">Milestone<br> Member</span>
     </div>

             <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
<g clip-path="url(#clip0_1240_1692)">
<path d="M30 22.499C30 23.599 29.251 24.999 28.335 25.61L16.665 33.39C15.749 34 14.251 34 13.335 33.39L1.665 25.61C0.749 24.999 0 23.6 0 22.499V11.501C0 10.401 0.749 9.00097 1.665 8.38997L13.335 0.609966C14.251 -3.41833e-05 15.749 -3.41833e-05 16.665 0.609966L28.335 8.38997C29.251 9.00097 30 10.4 30 11.501V22.499Z" fill="#C94E4B" />
<path d="M20.089 18.283C17.668 15.321 12.803 15.163 10.154 17.891C8.76504 19.322 8.12304 21.126 9.32704 22.879C10.273 24.257 11.407 24.733 13.018 24.327C13.521 24.201 14.038 24.056 14.615 24.056H14.897C15.451 24.114 15.943 24.323 16.405 24.513C16.707 24.637 17.016 24.763 17.34 24.818C18.049 24.947 18.81 24.56 19.395 24.191C21.619 22.786 21.699 20.252 20.089 18.283ZM11.331 13.224C11.772 13.438 12.264 13.565 12.754 13.584C14.913 13.584 15.493 6.74797 12.948 7.17697C11.705 7.38597 10.808 8.86097 10.286 9.88097C9.58304 11.258 9.80504 12.485 11.331 13.224ZM10.714 15.419C10.6 14.171 8.50904 11.366 7.03004 12.403C5.52204 13.546 5.70204 16.729 7.36404 17.709C8.53904 18.401 10.595 16.573 10.714 15.419C10.682 15.077 10.629 16.235 10.714 15.419ZM16.688 13.764C17.893 13.943 19.878 13.229 19.933 11.775C19.933 10.401 18.316 6.84097 16.509 7.50597C14.775 8.06197 14.81 13.486 16.688 13.764ZM23.988 14.536C23.921 13.755 23.574 13.028 22.999 12.494C22.202 11.82 21.1 12.776 20.561 13.335C19.535 14.397 18.718 15.619 19.856 16.877C20.41 17.49 21.511 18.37 22.412 18.008C23.598 17.533 24.086 15.668 23.988 14.536Z" fill="white" />
<path d="M15 1.15198C15.429 1.15198 15.834 1.25798 16.11 1.44198L27.78 9.22198C28.419 9.64798 29 10.734 29 11.501V22.499C29 23.266 28.419 24.352 27.781 24.778L16.111 32.558C15.835 32.742 15.43 32.848 15.001 32.848C14.572 32.848 14.167 32.742 13.891 32.558L2.221 24.778C1.581 24.352 1 23.266 1 22.499V11.501C1 10.734 1.581 9.64798 2.219 9.22198L13.889 1.44198C14.166 1.25798 14.571 1.15198 15 1.15198ZM15 0.151978C14.397 0.151978 13.793 0.304978 13.335 0.609978L1.665 8.38998C0.749 9.00098 0 10.4 0 11.501V22.499C0 23.599 0.749 24.999 1.665 25.61L13.335 33.39C13.793 33.695 14.396 33.848 15 33.848C15.604 33.848 16.207 33.695 16.665 33.39L28.335 25.61C29.251 24.999 30 23.6 30 22.499V11.501C30 10.401 29.251 9.00098 28.335 8.38998L16.665 0.609978C16.207 0.304978 15.603 0.151978 15 0.151978Z" fill="#C94E4B" />
<path d="M28.767 27.061C29.159 26.564 29.385 25.936 29.385 25.253C29.385 23.252 27.746 21.854 25.399 21.854C24.187 21.854 23.055 22.297 22.318 23.029C21.902 22.307 21.157 21.962 20.407 21.962C19.905 21.962 19.412 22.141 18.899 22.51L17.153 23.786C16.553 24.231 16.252 24.771 16.252 25.397C16.252 26.449 17.065 27.272 18.104 27.272C18.283 27.272 18.464 27.245 18.639 27.194V30.566C18.639 32.028 19.679 32.693 20.646 32.693C21.282 32.693 21.943 32.398 22.326 31.786C23.128 32.442 24.167 32.801 25.386 32.801C27.474 32.801 29.588 31.53 29.588 29.102C29.589 28.324 29.282 27.604 28.767 27.061Z" fill="#C94E4B" />
<path d="M19.483 23.323C19.867 23.047 20.167 22.963 20.407 22.963C20.839 22.963 21.654 23.143 21.654 24.378V30.567C21.654 31.538 20.97 31.694 20.646 31.694C20.323 31.694 19.639 31.538 19.639 30.567V25.338L18.727 26.046C18.511 26.214 18.284 26.274 18.104 26.274C17.624 26.274 17.252 25.902 17.252 25.399C17.252 25.135 17.371 24.872 17.743 24.596L19.483 23.323ZM24.127 27.173C24.127 26.921 24.247 26.393 25.015 26.393C26.023 26.393 26.334 25.925 26.334 25.434C26.334 24.822 25.818 24.498 25.267 24.498C24.847 24.498 24.559 24.666 24.259 25.026C24.079 25.242 23.852 25.422 23.48 25.422C22.989 25.422 22.592 25.063 22.592 24.571C22.592 24.295 22.689 24.079 22.941 23.803C23.492 23.203 24.427 22.855 25.399 22.855C26.898 22.855 28.385 23.623 28.385 25.254C28.385 26.189 27.785 26.885 26.958 27.101V27.137C27.929 27.365 28.589 28.157 28.589 29.104C28.589 30.963 26.945 31.803 25.387 31.803C24.308 31.803 23.396 31.491 22.748 30.855C22.473 30.579 22.352 30.315 22.352 30.016C22.352 29.5 22.772 29.117 23.263 29.117C23.575 29.117 23.79 29.261 24.151 29.62C24.499 29.968 24.846 30.112 25.291 30.112C25.866 30.112 26.526 29.824 26.526 29.033C26.526 28.433 26.034 27.966 25.014 27.966C24.247 27.964 24.127 27.436 24.127 27.173Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1692">
<rect width="30" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-white text-sm text-center invisible group-hover:visible text-wrap">Author<br> Level <br>13</span>
     </div>

             <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
<g clip-path="url(#clip0_1240_1700)">
<path d="M30 22.3C30 23.4 29.3 24.8 28.3 25.4L16.6 33.2001C15.7 33.8 14.2 33.8 13.3 33.2001L1.7 25.5C0.8 24.9 0 23.5 0 22.4V11.4C0 10.3 0.7 8.90005 1.7 8.30005L13.4 0.500049C14.3 -0.0999512 15.8 -0.0999512 16.7 0.500049L28.4 8.30005C29.3 8.90005 30.1 10.3 30.1 11.4V22.3H30Z" fill="#8360A8" />
<path d="M15 15.5C19.4 15.5 23 11.9 23 7.50005C23 6.30005 22.7 5.20005 22.3 4.20005L20.2 2.80005C21.3 4.00005 22 5.70005 22 7.50005C22 11.4 18.9 14.5 15 14.5C11.1 14.5 8 11.4 8 7.50005C8 5.70005 8.7 4.00005 9.8 2.80005L7.7 4.20005C7.3 5.20005 7 6.30005 7 7.50005C7 11.9 10.6 15.5 15 15.5Z" fill="white" />
<path d="M15 27.3C14.3 27.3 13.7 27.2001 13.2 27C12.8 26.8 12.4 26.5 12 26L11.7 25.9L9.30002 27H9.20001C9.00001 27 8.80001 26.9001 8.70001 26.7001C8.60001 26.5 8.50002 26.2001 8.60002 26L11.1 19V16.4C11.1 11.2 13.6 6.30005 15.2 6.30005C16.8 6.30005 19.3 11.2 19.3 16.4V19L21.8 26C21.9 26.2001 21.8 26.5 21.7 26.7001C21.6 26.9001 21.4 27 21.2 27H21L18.6 26L18 26.1C17.7 26.6 17.3 27 16.8 27.1C16.3 27.2 15.7 27.3 15 27.3Z" fill="white" />
<path d="M15 6.80005C16 6.80005 18.6 11.1 18.6 16.4C18.6 17.1 18.6 18.1 18.5 19.1L21 26.2001C21 26.3001 21 26.5 20.9 26.5L18.4 25.4L17.8 25.6C17.5 26.1 17.2 26.4 16.8 26.5C16.4 26.7001 15.8 26.7001 15.2 26.7001C14.6 26.7001 14 26.6 13.6 26.5C13.2 26.4 12.9 26 12.6 25.6L12 25.3L9.50005 26.4C9.00005 26.5 9.00005 26.3001 9.00005 26.2001L11.5 19.1V16.4C11.4 11.1 14 6.80005 15 6.80005ZM15 5.80005C12.7 5.80005 10.4 11.9 10.4 16.4V18.9L8.00005 25.8C7.90005 26.3 8.00005 26.7001 8.20005 27C8.40005 27.3 8.80005 27.5 9.10005 27.5H9.30005L9.50005 27.4L11.7 26.5C12.1 27 12.5 27.4 13 27.6C13.5 27.8 14.2 27.9 14.9 27.9C15.6 27.9 16.3 27.8 16.8 27.6C17.3 27.4 17.7 27.1 18.1 26.6L20.3 27.5L20.5 27.6H20.7C21.1 27.6 21.4 27.4 21.6 27.1C21.8 26.8 21.9 26.3 21.8 26L19.4 19.1V16.6C19.6 11.9 17.3 5.80005 15 5.80005Z" fill="#8360A8" />
<path d="M15 17.3C15.8284 17.3 16.5 16.6285 16.5 15.8C16.5 14.9716 15.8284 14.3 15 14.3C14.1716 14.3 13.5 14.9716 13.5 15.8C13.5 16.6285 14.1716 17.3 15 17.3Z" fill="#8360A8" />
<path d="M11 9.5C11.5523 9.5 12 9.05228 12 8.5C12 7.94772 11.5523 7.5 11 7.5C10.4477 7.5 10 7.94772 10 8.5C10 9.05228 10.4477 9.5 11 9.5Z" fill="white" />
<path d="M13 5.5C13.5523 5.5 14 5.05228 14 4.5C14 3.94772 13.5523 3.5 13 3.5C12.4477 3.5 12 3.94772 12 4.5C12 5.05228 12.4477 5.5 13 5.5Z" fill="white" />
<path d="M15 1C15.4 1 15.8 1.1 16.1 1.3L27.8 9.1C28.4 9.5 29 10.6 29 11.4V22.4C29 23.2 28.4 24.3 27.8 24.7L16.1 32.5C15.8 32.7 15.4 32.8 15 32.8C14.6 32.8 14.2 32.7 13.9 32.5L2.2 24.6C1.6 24.2 1 23.1 1 22.3V11.3C1 10.5 1.6 9.4 2.2 9L13.9 1.2C14.2 1.1 14.6 1 15 1ZM15 0C14.4 0 13.8 0.2 13.3 0.5L1.7 8.2C0.7 8.8 0 10.2 0 11.3V22.3C0 23.4 0.7 24.8 1.7 25.4L13.4 33.2C13.9 33.5 14.5 33.7 15.1 33.7C15.7 33.7 16.3 33.5 16.8 33.2L28.5 25.4C29.4 24.8 30.2 23.4 30.2 22.3V11.3C30.2 10.2 29.5 8.8 28.5 8.2L16.7 0.5C16.2 0.2 15.6 0 15 0Z" fill="#8360A8" />
<path d="M28.2 32.8C28 32.8 27.6 32.8 27.2 32.4C27 32.2 26.8 31.9 26.8 31.3V30.4L26.3 31.6C26 32.3 25.5 32.7 24.9 32.7C24.3 32.7 23.8 32.3 23.5 31.6L23 30.6V31.4C23 32.4 22.3 32.8 21.7 32.8C21.1 32.8 20.4 32.4 20.4 31.4V26.2C20.4 25.1 21.2 24.6 21.9 24.6C22.6 24.6 23.2 25 23.5 25.9L24.9 29.1L26.3 25.9C26.7 25 27.2 24.6 27.9 24.6C28.7 24.6 29.4 25.1 29.4 26.2V31.4C29.5 32.4 28.8 32.8 28.2 32.8Z" fill="white" />
<path d="M28 25.1C28.3 25.1 29 25.3 29 26.2V31.4C29 32.2 28.4 32.3 28.2 32.3C27.9 32.3 27.4 32.2 27.4 31.4V28.1L25.9 31.5C25.6 32.2 25.3 32.3 25 32.3C24.7 32.3 24.3 32.2 24.1 31.5L22.7 28.1V31.4C22.7 32.2 22.2 32.3 21.9 32.3C21.6 32.3 21.1 32.2 21.1 31.4V26.2C21.1 25.2 21.8 25.1 22.1 25.1C22.4 25.1 22.9 25.2 23.3 26.1L25.1 30.4L26.9 26.1C27.2 25.2 27.7 25.1 28 25.1ZM28 24.1C27.1 24.1 26.4 24.6 25.9 25.7L25 27.3L24 25.7C23.5 24.6 22.8 24.1 21.9 24.1C20.9 24.1 19.9 24.8 19.9 26.2V31.4C19.9 32.6 20.8 33.3 21.7 33.3C22.3 33.3 22.9 33 23.3 32.4C23.7 33 24.2 33.3 24.9 33.3C25.6 33.3 26.2 33 26.5 32.3C26.6 32.5 26.7 32.6 26.8 32.7C27.1 33 27.6 33.2 28.1 33.2C29 33.2 29.9 32.6 29.9 31.3V26.1C30 24.7 29 24.1 28 24.1Z" fill="#8360A8" />
<path d="M16.5 34V29.3C16.5 28.5 15.8 27.8 15 27.8C14.2 27.8 13.5 28.5 13.5 29.3V34H16.5Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1700">
<rect width="30" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-white text-sm text-center invisible group-hover:visible text-wrap">Top<br> Monthly<br> Author</span>
     </div>
            <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
<g clip-path="url(#clip0_1240_1714)">
<path d="M30 22.3C30 23.4 29.3 24.8 28.3 25.4L16.6 33.2001C15.7 33.8 14.2 33.8 13.3 33.2001L1.7 25.5C0.8 24.9 0 23.5 0 22.4V11.4C0 10.3 0.7 8.90005 1.7 8.30005L13.4 0.500049C14.3 -0.0999512 15.8 -0.0999512 16.7 0.500049L28.4 8.30005C29.3 8.90005 30.1 10.3 30.1 11.4V22.3H30Z" fill="#8360A8" />
<path d="M15 27.3C14.3 27.3 13.7 27.2001 13.2 27C12.8 26.8 12.4 26.5 12 26L11.7 25.9L9.30002 27H9.20001C9.00001 27 8.80001 26.9001 8.70001 26.7001C8.60001 26.5 8.50002 26.2001 8.60002 26L11.1 19V16.4C11.1 11.2 13.6 6.30005 15.2 6.30005C16.8 6.30005 19.3 11.2 19.3 16.4V19L21.8 26C21.9 26.2001 21.8 26.5 21.7 26.7001C21.6 26.9001 21.4 27 21.2 27H21L18.6 26L18 26.1C17.7 26.6 17.3 27 16.8 27.1C16.3 27.2 15.7 27.3 15 27.3Z" fill="white" />
<path d="M15 6.80005C16 6.80005 18.6 11.1 18.6 16.4C18.6 17.1 18.6 18.1 18.5 19.1L21 26.2001C21 26.3001 21 26.5 20.9 26.5L18.4 25.4L17.8 25.6C17.5 26.1 17.2 26.4 16.8 26.5C16.4 26.7001 15.8 26.7001 15.2 26.7001C14.6 26.7001 14 26.6 13.6 26.5C13.2 26.4 12.9 26 12.6 25.6L12 25.3L9.50005 26.4C9.00005 26.5 9.00005 26.3001 9.00005 26.2001L11.5 19.1V16.4C11.4 11.1 14 6.80005 15 6.80005ZM15 5.80005C12.7 5.80005 10.4 11.9 10.4 16.4V18.9L8.00005 25.8C7.90005 26.3 8.00005 26.7001 8.20005 27C8.40005 27.3 8.80005 27.5 9.10005 27.5H9.30005L9.50005 27.4L11.7 26.5C12.1 27 12.5 27.4 13 27.6C13.5 27.8 14.2 27.9 14.9 27.9C15.6 27.9 16.3 27.8 16.8 27.6C17.3 27.4 17.7 27.1 18.1 26.6L20.3 27.5L20.5 27.6H20.7C21.1 27.6 21.4 27.4 21.6 27.1C21.8 26.8 21.9 26.3 21.8 26L19.4 19.1V16.6C19.6 11.9 17.3 5.80005 15 5.80005Z" fill="#8360A8" />
<path d="M15 17.3C15.8284 17.3 16.5 16.6285 16.5 15.8C16.5 14.9716 15.8284 14.3 15 14.3C14.1716 14.3 13.5 14.9716 13.5 15.8C13.5 16.6285 14.1716 17.3 15 17.3Z" fill="#8360A8" />
<path d="M16.5 34V29.3C16.5 28.5 15.8 27.8 15 27.8C14.2 27.8 13.5 28.5 13.5 29.3V34H16.5ZM26.3 32.8C25.5 32.8 25 32.4 24.7 31.5L24 29.1L23.3 31.5C23 32.3 22.5 32.8 21.7 32.8C20.9 32.8 20.4 32.4 20.1 31.5L18.5 26.4C18.4 26.2 18.4 26 18.4 25.9C18.4 25.1 19 24.5 19.8 24.5C20.2 24.5 20.9 24.7 21.2 25.7L21.8 28L22.4 26C22.7 25 23.2 24.5 24 24.5C24.8 24.5 25.3 25 25.6 26L26.2 28L26.8 25.6C27 24.9 27.5 24.5 28.1 24.5C28.9 24.5 29.4 25.1 29.4 25.8C29.4 26 29.4 26.1 29.3 26.3L27.7 31.4C27.6 32.4 27 32.8 26.3 32.8Z" fill="white" />
<path d="M28.2 25.1001C28.6 25.1001 29 25.4001 29 25.9001C29 26.0001 29 26.1001 28.9 26.3001L27.3 31.4001C27 32.2001 26.5 32.3001 26.2 32.3001C25.9 32.3001 25.4 32.2001 25.1 31.4001L24 27.5001L22.8 31.4001C22.6 32.2001 22.1 32.3001 21.7 32.3001C21.3 32.3001 20.9 32.2001 20.6 31.4001L19 26.3001C19 26.1001 18.9 26.0001 18.9 25.9001C18.9 25.4001 19.3 25.0001 19.8 25.0001C20.1 25.0001 20.5 25.1001 20.7 25.8001L21.8 29.8001L22.9 26.1001C23.2 25.1001 23.7 25.0001 24 25.0001C24.3 25.0001 24.8 25.1001 25.1 26.1001L26.2 29.8001L27.3 25.8001C27.5 25.2001 27.9 25.1001 28.2 25.1001ZM28.2 24.1001C27.3 24.1001 26.6 24.7001 26.4 25.6001L26.2 26.2001L26.1 25.9001C25.7 24.4001 24.7 24.1001 24 24.1001C23.3 24.1001 22.3 24.4001 21.9 25.9001L21.8 26.2001L21.7 25.7001C21.4 24.7001 20.8 24.1001 19.8 24.1001C18.8 24.1001 17.9 24.9001 17.9 26.0001C17.9 26.2001 17.9 26.4001 18 26.7001L19.6 31.8001C19.9 32.9001 20.7 33.4001 21.7 33.4001C22.7 33.4001 23.4 32.8001 23.7 31.7001L24 30.9001L24.3 31.7001C24.6 32.8001 25.3 33.3001 26.3 33.3001C27.3 33.3001 28 32.7001 28.3 31.7001L29.9 26.6001C30 26.3001 30 26.1001 30 25.9001C30 24.9001 29.2 24.1001 28.2 24.1001Z" fill="#8360A8" />
</g>
<defs>
<clipPath id="clip0_1240_1714">
<rect width="30" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-sm text-center text-white invisible group-hover:visible text-wrap">Weekly <br>Top<br> Seller</span>
     </div>
            <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="31" height="34" viewBox="0 0 31 34" fill="none">
<g clip-path="url(#clip0_1240_1723)">
<path d="M28.3 25.6L16.6 33.4C15.7 34 14.2 34 13.3 33.4L1.7 25.6C0.7 25 0 23.6 0 22.5V11.5C0 10.4 0.7 9.00002 1.7 8.40002L13.4 0.600024C14.3 2.44081e-05 15.8 2.44081e-05 16.7 0.600024L28.4 8.40002C29.3 9.00002 30.1 10.4 30.1 11.5V22.5C30.1 23.6 29.3 25 28.3 25.6Z" fill="#56A4CA" />
<path d="M16.5 15.1H20L10 27L13.5 18.9H10L20 7L16.5 15.1Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1723">
<rect width="31" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-sm text-center text-white invisible group-hover:visible text-wrap">Trendsetter</span>
     </div>
           <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
<g clip-path="url(#clip0_1240_1727)">
<path d="M30 22.499C30 23.599 29.251 24.999 28.335 25.61L16.665 33.39C15.749 34 14.251 34 13.335 33.39L1.665 25.61C0.749 24.999 0 23.6 0 22.499V11.501C0 10.401 0.749 9.00097 1.665 8.38997L13.335 0.609966C14.251 -3.41833e-05 15.749 -3.41833e-05 16.665 0.609966L28.335 8.38997C29.251 9.00097 30 10.4 30 11.501V22.499Z" fill="#F95858" />
<path d="M15.13 21.368C14.425 22.504 12.945 22.85 11.808 22.144C10.672 21.438 10.326 19.958 11.032 18.822L12.389 16.657C12.84 15.93 13.807 15.704 14.533 16.156C14.999 16.445 15.618 16.3 15.908 15.834C16.197 15.369 16.052 14.749 15.587 14.46C13.928 13.43 11.723 13.946 10.694 15.604L9.33605 17.769C8.05205 19.837 8.68705 22.555 10.755 23.84C11.78 24.476 12.981 24.641 14.083 24.383C15.186 24.126 16.174 23.449 16.826 22.421C17.115 21.955 16.971 21.336 16.505 21.046C16.039 20.757 15.42 20.902 15.13 21.368ZM19.249 10.164C17.181 8.879 14.463 9.515 13.178 11.583C12.889 12.049 13.033 12.668 13.499 12.957C13.965 13.246 14.584 13.102 14.874 12.636C15.579 11.499 17.059 11.154 18.196 11.859C19.332 12.565 19.678 14.045 18.972 15.182L17.615 17.347C17.167 18.088 16.201 18.314 15.47 17.848C15.005 17.559 14.386 17.703 14.096 18.169C13.807 18.635 13.952 19.254 14.417 19.543C15.256 20.064 16.209 20.192 17.1 19.983C17.991 19.775 18.79 19.238 19.31 18.4L20.653 16.238C21.952 14.167 21.317 11.449 19.249 10.164Z" fill="white" />
<path d="M15 1.15198C15.429 1.15198 15.834 1.25798 16.11 1.44198L27.78 9.22198C28.419 9.64798 29 10.734 29 11.501V22.499C29 23.266 28.419 24.352 27.781 24.778L16.111 32.558C15.835 32.742 15.43 32.848 15.001 32.848C14.572 32.848 14.167 32.742 13.891 32.558L2.221 24.778C1.581 24.352 1 23.266 1 22.499V11.501C1 10.734 1.581 9.64798 2.219 9.22198L13.889 1.44198C14.166 1.25798 14.571 1.15198 15 1.15198ZM15 0.151978C14.397 0.151978 13.793 0.304978 13.335 0.609978L1.665 8.38998C0.749 9.00098 0 10.4 0 11.501V22.499C0 23.599 0.749 24.999 1.665 25.61L13.335 33.39C13.793 33.695 14.396 33.848 15 33.848C15.604 33.848 16.207 33.695 16.665 33.39L28.335 25.61C29.251 24.999 30 23.6 30 22.499V11.501C30 10.401 29.251 9.00098 28.335 8.38998L16.665 0.609978C16.207 0.304978 15.603 0.151978 15 0.151978Z" fill="#F95858" />
<path d="M26.389 25.765C27.277 25.504 27.688 24.726 27.688 23.993C27.688 23.096 27.071 22.13 25.717 22.13H22.406C21.139 22.13 20.358 22.895 20.316 24.176L20.208 26.831C20.176 27.54 20.447 27.982 20.681 28.226L20.916 28.428C20.291 28.74 19.871 29.374 19.871 30.122C19.871 30.635 20.093 31.164 20.479 31.575C21.246 32.375 22.458 32.848 23.726 32.848C26.242 32.848 28 31.19 28 28.814C28 27.476 27.401 26.403 26.389 25.765Z" fill="#F95858" />
<path d="M21.315 24.209C21.339 23.478 21.675 23.13 22.406 23.13H25.716C26.544 23.13 26.688 23.705 26.688 23.993C26.688 24.281 26.544 24.856 25.716 24.856H23.15L23.078 26.2C23.33 26.14 23.678 26.116 23.929 26.116C25.632 26.116 27 27.027 27 28.814C27 30.878 25.393 31.849 23.726 31.849C22.694 31.849 21.759 31.465 21.207 30.89C21.015 30.686 20.871 30.397 20.871 30.122C20.871 29.606 21.279 29.223 21.807 29.223C22.046 29.223 22.251 29.282 22.622 29.678C22.886 29.954 23.258 30.146 23.702 30.146C24.385 30.146 24.973 29.727 24.973 28.91C24.973 27.903 24.062 27.615 23.234 27.615C22.874 27.615 22.61 27.651 22.406 27.688C22.227 27.724 22.094 27.747 21.951 27.747C21.734 27.747 21.171 27.663 21.207 26.872L21.315 24.209Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1727">
<rect width="30" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-sm text-center text-white invisible group-hover:visible text-wrap">Affiliate <br> Level 5</span>
     </div>
           <div class="flex flex-col items-center gap-2 cursor-pointer group">
       <svg xmlns="http://www.w3.org/2000/svg" width="30" height="34" viewBox="0 0 30 34" fill="none">
<g clip-path="url(#clip0_1240_1734)">
<path d="M30 22.499C30 23.599 29.251 24.999 28.335 25.61L16.665 33.39C15.749 34 14.251 34 13.335 33.39L1.665 25.61C0.749 24.999 0 23.6 0 22.499V11.501C0 10.401 0.749 9.00097 1.665 8.38997L13.335 0.609966C14.251 -3.41833e-05 15.749 -3.41833e-05 16.665 0.609966L28.335 8.38997C29.251 9.00097 30 10.4 30 11.501V22.499Z" fill="#C94E4B" />
<path d="M28 15V11H25V10H24V7H20V8.5C20 9.328 19.328 10 18.5 10C17.672 10 17 9.328 17 8.5V7H13V8.5C13 9.328 12.328 10 11.5 10C10.672 10 10 9.328 10 8.5V7H6V10H5V11H2V15H3.5C4.328 15 5 15.672 5 16.5C5 17.328 4.328 18 3.5 18H2V22H5V23H6V26H10V24.5C10 23.672 10.672 23 11.5 23C12.328 23 13 23.672 13 24.5V26H17V24.5C17 23.672 17.672 23 18.5 23C19.328 23 20 23.672 20 24.5V26H24V23H25V22H28V18H26.5C25.672 18 25 17.328 25 16.5C25 15.672 25.672 15 26.5 15H28ZM24 22H6V11H24V22ZM8 13H12V14H8V13ZM8 13H9V16H8V13ZM8 15H11V16H8V15ZM11 15H12V18H11V15ZM8 17H12V18H8V17ZM13 14H17V15H13V14ZM13 15H14V17H13V15ZM13 17H17V18H13V17Z" fill="white" />
<path d="M15 1.15198C15.429 1.15198 15.834 1.25798 16.11 1.44198L27.78 9.22198C28.419 9.64798 29 10.734 29 11.501V22.499C29 23.266 28.419 24.352 27.781 24.778L16.111 32.558C15.835 32.742 15.43 32.848 15.001 32.848C14.572 32.848 14.167 32.742 13.891 32.558L2.221 24.778C1.581 24.352 1 23.266 1 22.499V11.501C1 10.734 1.581 9.64798 2.219 9.22198L13.889 1.44198C14.166 1.25798 14.571 1.15198 15 1.15198ZM15 0.151978C14.397 0.151978 13.793 0.304978 13.335 0.609978L1.665 8.38998C0.749 9.00098 0 10.4 0 11.501V22.499C0 23.599 0.749 24.999 1.665 25.61L13.335 33.39C13.793 33.695 14.396 33.848 15 33.848C15.604 33.848 16.207 33.695 16.665 33.39L28.335 25.61C29.251 24.999 30 23.6 30 22.499V11.501C30 10.401 29.251 9.00098 28.335 8.38998L16.665 0.609978C16.207 0.304978 15.603 0.151978 15 0.151978Z" fill="#C94E4B" />
<path d="M27.7959 25.148C27.7959 23.147 26.1569 21.75 23.8099 21.75C22.5409 21.75 21.3469 22.224 20.6149 23.02C20.3289 23.332 20.0039 23.777 20.0039 24.464C20.0039 25.44 20.7349 26.216 21.6999 26.307C21.5909 26.549 21.5389 26.811 21.5389 27.067C21.5389 27.39 21.6219 27.723 21.7939 28.013L21.6749 28.009C20.6209 28.009 19.7629 28.861 19.7629 29.909C19.7629 30.479 19.9949 31 20.4529 31.456C21.2809 32.269 22.4349 32.696 23.7979 32.696C25.8859 32.696 27.9999 31.426 27.9999 28.998C27.9999 28.218 27.6939 27.498 27.1779 26.955C27.5699 26.459 27.7959 25.831 27.7959 25.148Z" fill="#C94E4B" />
<path d="M22.5389 27.067C22.5389 26.815 22.6589 26.287 23.4259 26.287C24.4339 26.287 24.7459 25.82 24.7459 25.328C24.7459 24.716 24.2299 24.392 23.6779 24.392C23.2579 24.392 22.9709 24.56 22.6709 24.92C22.4909 25.136 22.2629 25.316 21.8909 25.316C21.3989 25.316 21.0039 24.956 21.0039 24.464C21.0039 24.188 21.0999 23.972 21.3519 23.697C21.9029 23.097 22.8389 22.75 23.8099 22.75C25.3099 22.75 26.7959 23.517 26.7959 25.148C26.7959 26.084 26.1969 26.779 25.3689 26.995V27.031C26.3409 27.258 26.9999 28.05 26.9999 28.998C26.9999 30.857 25.3569 31.696 23.7979 31.696C22.7189 31.696 21.8069 31.384 21.1599 30.749C20.8839 30.473 20.7639 30.209 20.7639 29.909C20.7639 29.393 21.1839 29.009 21.6749 29.009C21.9869 29.009 22.2029 29.154 22.5629 29.513C22.9109 29.861 23.2579 30.005 23.7019 30.005C24.2779 30.005 24.9369 29.717 24.9369 28.925C24.9369 28.326 24.4459 27.858 23.4259 27.858C22.6589 27.858 22.5389 27.331 22.5389 27.067Z" fill="white" />
</g>
<defs>
<clipPath id="clip0_1240_1734">
<rect width="30" height="34" fill="white" />
</clipPath>
</defs>
</svg>
       <span class="text-sm text-center text-white invisible group-hover:visible text-wrap">Collector <br> Level 3</span>
     </div>

           </div>
         </div>
       </div>
     </div>
   </div>
 </section>


 <section id="gridlayouts" class="bg-black py-5">
 <div id="inner grid">
   <div id="headtext" class="p-5 grid xl:grid-cols-2">
     <div class="">
       <div id="textcolor" class="flex place-content-center gap-2 xl:place-content-start xl:text-xl">
       <i class="text-white bg-custom-gradient">i</i>
      <h3 class="text-white bg-custom-gradient bg-clip-text text-transparent">WHY CHOOSE KALLES ?</h3>
     </div>
     <div id="text" class="py-3">
       <h1 class="text-center text-white text-2xl font-bold xl:text-start xl:text-5xl">Stand Out From The Crowd<span class="hidden xl:inline"><br></span>
            With Premium Features</h1>
     </div>
     </div>
     <div class="xl:place-content-end">
       <h1 class="text-gray-500 text-center font-bold xl:text-start xl:text-xl xl:float-end ">Enjoy the exclusive features that make<span class="hidden xl:inline"><br></span>
                 building your web pages a joyful moment.<span class="hidden xl:inline"><br></span>
                 All in one theme!</h1>
     </div>
   </div>
   <div id="layouts"></div>
   <div id="shopify"></div>
 </div>
</section>


<section id="gridlayouts" class="bg-black py-5">
 <div id="inner-grid">
   <div id="headtext" class="p-5 grid xl:grid-cols-2">
     <div class="">
       <div id="textcolor" class="flex place-content-center gap-2 xl:place-content-start xl:text-xl">
         <i class="text-white bg-custom-gradient">i</i>
         <h3 class="text-white bg-custom-gradient">WHY CHOOSE KALLES ?</h3>
       </div>
       <div id="text" class="py-3">
         <h1 class="text-center text-white text-2xl font-bold xl:text-start xl:text-5xl">Stand Out From The Crowd<span class="hidden xl:inline"><br></span>With Premium Features</h1>
       </div>
     </div>
     <div class="xl:place-content-end">
       <h1 class="text-gray-500 text-center font-bold xl:text-start xl:text-xl xl:float-end ">Enjoy the exclusive features that make<span class="hidden xl:inline"><br></span>building your web pages a joyful moment.<span class="hidden xl:inline"><br></span>All in one theme!</h1>
     </div>
   </div>
   <div id="layouts" class="p-5 grid md:grid-cols-3 sm:grid-cols-2 gap-6">
     <div id="flex" class="p-4 bg-gray-900 rounded-lg shadow-2xl sm:flex sm:gap-7 md:col-span-2 sm:col-span-2">
       <div>
         <h1 class="bg-custom-gradient text-5xl font-semibold text-white">50 +</h1>
         <h1 class="mt-3 text-2xl font-bold text-white">High -quality<span class="md:hidden inline"> <br></span> demos</h1>
         <div class="flex mt-5">
           <div class="effect-custom rounded-2xl">
             <a href="sundhar" class="relative flex items-center justify-center gap-1 rounded-md border-2 p-3 py-2 border-gray-500 bg-black font-medium text-white backdrop-blur-3xl hover:bg-gray-800 sm:py-2 lg:py-3 md:py-3 xl:py-3">
               <i class="fa-solid fa-table-cells-large h-5 w-5 text-white z-10"></i>
               <span class="cta_text z-10 text-white md:text-xl xl:text-xl">Explore Demos</span>
               <div class="absolute inset-0 flex items-center justify-center overflow-hidden">
                 <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-violet-700 to-indigo-700"></span>
                 <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-indigo-700 to-cyan-500 delay-150"></span>
                 <span class="h-full w-full animate-pulse bg-opacity-40 bg-gradient-to-r from-cyan-500 to-violet-700 delay-300"></span>
               </div>
             </a>
           </div>
         </div>
       </div>
       <div class="mt-5 sm:ml-12">
         <img src="https://themes.the4.co/kalles-5/assets/images/grid1/item1.png" class="object-cover sm:h-auto sm:w-full">
       </div>
     </div>

     <div id="powerlite" class="p-4 bg-gray-900 rounded-lg shadow-2xl xl:col-span-1">
       <img src="https://themes.the4.co/kalles-5/assets/images/grid1/item2_i.png" alt="" class="object-fit object-center h-auto w-auto rounded-full">
       <div class="relative bottom-16 xl:bottom-32">
         <div class="text-center">
           <span class="text-white">Developed by<a href="" class="bg-custom-gradient"> Power <br>Elite</a></span>
           <span class="text-white"> on Envato Market</span>
         </div>
         <div id="rating-image" class="text-white mt-5 flex gap-4 place-content-center">
           <div class="shadow-2xl bg-gray-800 rounded-xl px-1 flex items-center gap-5">
             <i class="fa-solid fa-table-cells-large h-5 w-5 text-white z-10"></i>
             <span>32.000+<span class="md:hidden inline"> <br></span> Sales</span>
           </div>
           <div class="shadow-2xl bg-gray-800 rounded-xl px-1 flex items-center gap-5">
             <i class="fa-solid fa-table-cells-large h-5 w-5 text-white z-10"></i>
             <span>5.0 Stars<span class="md:hidden inline"> <br></span> Ratings</span>
           </div>
         </div>
       </div>
     </div>

     <div id="shopify" class="p-4 bg-gray-900 rounded-lg shadow-2xl xl:col-span-1 cursor-pointer">
       <img src="https://themes.the4.co/kalles-5/assets/images/grid1/item3.png" alt="" class="object-fit object-center h-full w-full">
       <div class="relative bottom-32 xl:bottom-44">
         <div class="ml-5">
           <a href="" class="bg-custom-gradient text-xl">Supported by</a><br>
           <span class="text-white text-xl">Commerce Coach</span>
           <h1 class="text-gray-500 text-lg font-bold mt-4">Server <span class="text-white font-bold">100k+</span> customers</h1>
         </div>
       </div>
     </div>

     <div id="demos" class="p-4 bg-gray-900 rounded-lg shadow-2xl xl:col-span-1">
       <div class="absolute z-10 ml-5">
<h3 class="text-white xl:mt-5" data-wow-delay="0.2s" data-wow-duration="1s"><span class="text-white text-lg">One Click<svg class="" xmlns="http://www.w3.org/2000/svg" width="119" height="6" viewBox="0 0 119 6" fill="none">
<path d="M119 0.885906C118.394 0.845638 117.839 0.845638 117.233 0.845638C116.627 0.845638 116.072 0.805369 115.466 0.765101C114.153 0.684564 112.891 0.563758 111.578 0.483222C109.104 0.322148 106.58 0.161074 104.106 0.120805C101.834 0.0402685 99.5117 0 97.2397 0C96.6339 0 96.028 0 95.4726 0C93.2007 0.0402685 90.9287 0.0402685 88.6568 0.0805369C83.3555 0.201342 78.0038 0.322148 72.7026 0.52349C67.5023 0.724832 62.3021 0.926175 57.1523 1.16779C54.6279 1.28859 52.053 1.4094 49.5286 1.5302C46.7518 1.73154 43.975 1.85235 41.2486 2.01342C35.5435 2.37584 29.8888 2.69799 24.1837 3.0604C19.2359 3.38255 14.3386 3.8255 9.44124 4.38926C6.31099 4.79195 3.13025 5.2349 0 5.67785C3.58464 5.87919 7.21977 5.95973 10.8549 6C13.2278 6 15.6008 5.95973 17.9232 5.91946C19.4378 5.87919 20.9525 5.79866 22.5176 5.71812C23.4769 5.67785 24.3857 5.59732 25.2944 5.51678C27.7684 5.31544 30.2927 5.15436 32.7667 4.95302C35.6445 4.75168 38.4718 4.51007 41.3496 4.30872C44.2779 4.10738 47.2567 3.90604 50.185 3.7047C52.8104 3.54362 55.4862 3.38255 58.1621 3.22148C60.737 3.0604 63.3623 2.9396 65.9372 2.81879C68.5626 2.69799 71.1375 2.57718 73.7628 2.45638C76.4387 2.33557 79.0641 2.2953 81.7399 2.21477C86.5868 2.05369 91.4336 2.01342 96.3309 1.97315C99.0573 1.97315 101.733 1.89262 104.459 1.81208C107.135 1.73154 109.811 1.65101 112.437 1.5302C113.497 1.48993 114.608 1.44966 115.668 1.36913C116.173 1.32886 116.728 1.28859 117.233 1.20805C117.687 1.12752 118.142 1.00671 118.596 0.966443C118.748 0.926175 118.849 0.885906 119 0.885906Z" fill="url(#paint0_linear_696_1269)" />
<defs>
<linearGradient id="paint0_linear_696_1269" x1="15.0633" y1="6" x2="24.3252" y2="-24.5103" gradientUnits="userSpaceOnUse">
<stop stop-color="#CE1BFB" />
<stop offset="1" stop-color="#35E6CC" />
</linearGradient>
</defs>
</svg></span><span class="text-lg">Import demo and more...</span></h3>
</div>
       <img src="https://themes.the4.co/kalles-5/assets/images/grid1/item4.png" alt="" class="object-fit object-center h-full w-auto relative">
     </div>

     <div id="powerlite" class="p-4 bg-gray-900 rounded-lg shadow-2xl xl:col-span-1">
       <img src="https://themes.the4.co/kalles-5/assets/images/grid1/item2_i.png" alt="" class="object-fit object-center h-auto w-auto rounded-full">
       <div class="relative bottom-16 xl:bottom-32">
         <div class="text-center">
           <span class="text-white">Developed by<a href="" class="bg-custom-gradient"> Power <br>Elite</a></span>
           <span class="text-white"> on Envato Market</span>
         </div>
         <div id="rating-image" class="text-white mt-5 flex gap-4 place-content-center">
           <div class="shadow-2xl bg-gray-800 rounded-xl px-1 flex items-center gap-5">
             <i class="fa-solid fa-table-cells-large h-5 w-5 text-white z-10"></i>
             <span>32.000+<span class="md:hidden inline"> <br></span> Sales</span>
           </div>
           <div class="shadow-2xl bg-gray-800 rounded-xl px-1 flex items-center gap-5">
             <i class="fa-solid fa-table-cells-large h-5 w-5 text-white z-10"></i>
             <span>5.0 Stars<span class="md:hidden inline"> <br></span> Ratings</span>
           </div>
         </div>
       </div>
     </div>
   </div>
   <div id="shopify"></div>
 </div>
</section>
</template>

<script setup>
import { ref } from "vue";
const open = ref(false);
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
   background: linear-gradient(81deg, #CE1BFB 10.86%, #35E6CC 89.96%);
   -webkit-background-clip: text;
   -webkit-text-fill-color: transparent;
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