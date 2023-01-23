---
# try also 'default' to start simple
# background: /assets/images/vue-wallpaper.png
# apply any windi css classes to the current slide
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
---

<div class="flex justify-between items-center">
  <div>
    <span class="!m-0 text-light-200">#TechTalk</span>
    <h1 class="!m-0 font-extrabold text-transparent text-8xl bg-clip-text bg-gradient-to-r from-[#3db17e] to-[#366f68]">
    VueUse
    </h1>
    <h4>
    Collection of Essential Vue Composition Utilities
    </h4>
  </div>

  <div class="relative mr-[100px]">
    <div 
      class="
        absolute top-[50%] left-[50%]
        rounded-full
        w-[192px] h-[192px]
        bg-[#41b88380]
      " 
      style="
        filter: blur(72px);
        transform: translate(-50%, -50%)
      "
    ></div>
    <img src="/assets/images/vueuse-icon.svg" class="h-[150px] " />
  </div>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

<div class="mb-5">
  <h1 class="!m-0 font-extrabold text-transparent text-8xl bg-clip-text bg-gradient-to-r from-[#42d392] to-[#647eff]">Why VueUse?</h1>
</div>

<div class="text-light-200">
    <v-clicks>
      <p>
        🎛 <b>Feature Rich</b> - 200+ functions for you to choose from
      </p>
    </v-clicks>
    <v-clicks>
      <p>🚀 <b>Seamless migration</b> - Works for both Vue 3 and 2</p>
    </v-clicks>
    <v-clicks>
      <p>⚡ <b>Fully tree shakeable</b> - Only take what you want</p>
    </v-clicks>
    <v-clicks>
      <p>🦾 <b>Type Strong</b> - Written in TypeScript, with full TS docs</p>
    </v-clicks>
    <v-clicks>
      <p>🛠️ <b>Flexible</b> - assing refs as arguments, fully customizable, configurable event filters and targets</p>
    </v-clicks>
    <v-clicks>
      <p>☁️ <b>No bundler required</b> - Usable via CDN, without any bundlers</p>
    </v-clicks>
    <v-clicks>
      <p>🔋 <b>SSR Friendly</b> - Works perfectly with server-side rendering/generation</p>
    </v-clicks>
    <v-clicks>
      <p>🎪 <b>Interactive demos</b> - Documentation of functions also come with interactive demos!</p>
    </v-clicks>
    <v-clicks>
      <p>🔌 <b>Add-ons</b> - Support various add-ons like Router, Firebase, RxJS, etc.</p>
    </v-clicks>
</div>

<!--
Here is another comment.
-->

---

<div class="mb-5">
  <h1 class="!m-0 font-extrabold text-transparent text-8xl bg-clip-text bg-gradient-to-r from-[#42d392] to-[#647eff]">What's the context of this talk?</h1>
</div>

<div class="leading-relaxed text-light-200">
   In this talk, we’ll sample some hand picked functions to give you an idea of what’s possible with VueUse. Along the way we'll examine not only how they work but some practical applications for how you might use them. By the end of the talk, hopefully I would have equipped you with a pretty awesome tool set and wet your appetite to utilize VueUse in your own Vue.js projects.
</div>
