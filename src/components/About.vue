<template>
  <div id="about" class="bg-neutral-700 py-20">
    <div class="flex items-center justify-evenly">
      <div class="w-1/3 tracking-wide">
        <div class="font-bold uppercase tracking-widest text-yellow-300">About me</div>
        <div class="mt-2">Yo! I'm <span class="underline decoration-yellow-300">Pam</span>, a web developer who's been coding for a little over a year now. I fell in love with
          building stuff online and haven't looked back since.</div>
        <div class="mt-2">I'm all about front-end development, where I turn design ideas into living, breathing websites. I don't just
          make them work, I make them look good too. My mission is to create interfaces that are a breeze to use and stick
          in people's minds.</div>
      </div>
      <div class="w-1/2 tracking-wide">
        <div class="grid grid-cols-4 gap-4">
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/HTML5_Badge.svg/768px-HTML5_Badge.svg.png?20110131171049"
              alt="HTML Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">HTML</div>
            <div class="text-xs mt-1 text-neutral-300">7+ years</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/CSS3_logo.svg/800px-CSS3_logo.svg.png"
              alt="CSS Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">CSS</div>
            <div class="text-xs mt-1 text-neutral-300">7+ years</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://cdn.icon-icons.com/icons2/2699/PNG/512/jquery_logo_icon_167804.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">jQuery</div>
            <div class="text-xs mt-1 text-neutral-300">1+ years</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/2300px-React-icon.svg.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">React</div>
            <div class="text-xs mt-1 text-neutral-300">6+ months</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Vue.js_Logo_2.svg/2367px-Vue.js_Logo_2.svg.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">Vue.js</div>
            <div class="text-xs mt-1 text-neutral-300">6+ months</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/640px-PHP-logo.svg.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">PHP</div>
            <div class="text-xs mt-1 text-neutral-300">3+ years</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/2560px-Bootstrap_logo.svg.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">Bootstrap</div>
            <div class="text-xs mt-1 text-neutral-300">5+ years</div>
          </div>
          <div class="relative overflow-hidden skills-card bg-neutral-600 rounded px-4 py-3">
            <img
              class="absolute top-0 -right-4 h-full object-cover opacity-70 w-1/2"
              src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/320px-Tailwind_CSS_Logo.svg.png"
              alt="jQuery Card Background"
            />
            <div class="text-sm tracking-widest font-semibold">Tailwind CSS</div>
            <div class="text-xs mt-1 text-neutral-300">1+ years</div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>

<script>

export default {
  name: 'AboutSection',
}
</script>
