<script>
  import { scrollTo, scrollRef, scrollTop } from 'svelte-scrolling'
</script>

<body class="bg-[#101317] font-lexend">
  <div class="flex items-center justify-center min-h-screen">
    <div class="lg:flex gap-x-10 px-10 items-center justify-center">
      <img src="/images/av-rec.png" alt="avatar" class="lg:w-[450px] lg:h-[450px] w-[100px] h-[100px]"/>
      <div>
        <h1 class="text-white text-7xl font-extrabold mt-2">Hello!</h1>
        <span class="font-extrabold text-white">17 // Software Engineer @ Patterson Labs, LLC</span>
        <p class="text-[#C2BBBB] text-md max-w-xl">
          I'm <span class="font-bold">Leon</span>, a student from Poland with a passion for software development!
          <span class="font-bold">I'm currently working on:</span> <a class="text-blue-400 hover:underline" href="https://firepanel.r3dlabs.com">FirePanel</a> 🔥 for <a class="text-blue-400 hover:underline" href="https://r3dlabs.com">R3dLabs</a>
        </p>
        <div>
          <div class="flex mt-2">
						<img src="/icons/discord.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="https://discordapp.com/users/314424536256872449">borox1337</a>
					</div>

          <div class="flex">
						<img src="/icons/mail.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="mailto:borox.biznes@gmail.com">leon.borowiec@gmail.com</a>
					</div>

          <div class="flex">
						<img src="/icons/pay.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="https://paypal.me/8LB3">paypal.me/8LB3</a>
					</div>
        </div>
        <div class="lg:space-x-10">
          <!-- <a use:scrollTo={'contact'} href="/">
            <button class="w-[200px] h-[80px] bg-[#14222D] rounded-[10px] font-bold text-white text-xl mt-5">
              Contact me
            </button>
          </a> -->
          
          <!-- <a use:scrollTo={'projects'} href="/">
            <button class="w-[200px] h-[80px] border-[#14222D] border-4 rounded-[10px] font-bold text-white text-xl mt-5">
              My projects
            </button>
          </a> -->
        </div>
      </div>
    </div>
  </div>

  <!-- <div class="flex items-center justify-center min-h-screen" >
    <div class="mt-[300px]" use:scrollRef={'projects'}>
      <h1 class="text-white text-5xl font-extrabold text-center" >My work</h1>
      <div class="grid grid-cols-1 gap-y-8 mt-8 px-20">
        <div class="bg-[#15191E] transition-all duration-500 bg-gradient-to-t to-[#15191E] via-[#15191E] from-[#3E70DD] bg-size-200 bg-pos-0 hover:bg-pos-100 lg:w-[900px] w-full lg:h-[600px] h-[400px] rounded-[20px] border-2 border-[#19212B] lg:py-20 py-10 px-20">
          <h1 class="font-bold text-white text-5xl pl-6">Websites</h1>
          <p class="text-[#C2BBBB] font-normal pl-6">Here you can find some of my projects related to web development. Each website/design with description. </p>
          <img src="/thumbnails/web2.png" alt="websites-thumbnail" class="mt-5" />
        </div>

        <div class="bg-[#15191E] transition-all duration-500 bg-gradient-to-t to-[#15191E] via-[#15191E] from-[#263654] bg-size-200 bg-pos-0 hover:bg-pos-100 lg:w-[900px] w-full lg:h-[600px] h-[400px] rounded-[20px] border-2 border-[#19212B] lg:py-20 py-10 px-20">
          <h1 class="font-bold text-white text-5xl pl-6">Streaming Supplies</h1>
          <p class="text-[#C2BBBB] font-normal pl-6">Technical services for streamers. Twitch extensions, chatbots, interactive widgets, and anything that can improve their stream. </p>
          <img src="/thumbnails/streaming-supplies.png" alt="websites-thumbnail" class="mt-5" />
        </div>
      </div>
      <div class="flex items-center justify-center">
        <a href="https://github.com/borox345">
          <button class="w-[200px] h-[80px] border-[#14222D] border-4 rounded-[10px] font-extrabold text-white text-xl mt-5">
            See more!
          </button>
        </a>
      </div>
    </div>
  </div> -->

  <!-- <div class="flex items-center justify-center min-h-screen" use:scrollRef={'contact'}>
    <div class="">
      <div class="bg-[#15191E] w-[600px] h-[250px] rounded-xl px-8 py-6 gap-x-5 items-center justify-center mt-8 flex">
        <div>
          <h1 class="text-white font-extrabold text-4xl">Want to work with me?</h1>
          <p class="text-[#C2BBBB] font-normal">Feel free to reach out! Whether you have questions, opportunities, or just want to connect, I'd love to hear from you.</p>
          <div class="flex mt-2">
						<img src="/icons/discord.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="https://discordapp.com/users/314424536256872449">borox1337</a>
					</div>

          <div class="flex">
						<img src="/icons/mail.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="mailto:borox.biznes@gmail.com">leon.borowiec@gmail.com</a>
					</div>

          <div class="flex">
						<img src="/icons/pay.svg" alt="Localization icon" class="mr-2 w-6 h-6"><a class="text-graynew font-bold hover:underline text-[#C2BBBB]" href="https://paypal.me/8LB3">paypal.me/8LB3</a>
					</div>
        </div>
      </div>
    </div>
  </div> -->
</body>
