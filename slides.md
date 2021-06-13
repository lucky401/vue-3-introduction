---
theme: default
title: 'Introduction new feature in Vue 3'
download: true
monaco: false
highlighter: Prism
routerMode: 'hash'
colorSchema: 'dark'
info: |
  ## Introduction new feature in Vue 3
  By Lucky Dewa Satria.
---

<style>
@import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
h1{
  font-family: 'Press Start 2P', sans-serif;
}
</style>

<div class="text-center">
  <img src="/vue-logo.png" alt="vue" class="image-render-edge block mx-auto w-xs" title="Vue.js"  />
  <h1 class="font-light">Vue.js</h1>
</div>

---

<h1 class="text-center">Vue vs react</h1>

<div class="grid grid-cols-2 gap-2 mt-14">
  <div class="text-center flex flex-col justify-between">
    <img src="/vue-logo.png" alt="vue" class="block mx-auto w-1/2" title="Vue.js"/>
    <h2>2014</h2>
    <p class="flex justify-center"> <logos-github-octocat class="text-white" /> 184k</p>
  </div>
  <div class="text-center flex flex-col justify-between">
    <img src="/react-logo.png" alt="React" class="block mx-auto w-1/2" title="React"/>
    <h2>2013</h2>
    <p class="flex justify-center"> <logos-github-octocat class="text-white" /> 169k</p>
  </div>
</div>

<span class="italic text-gray-500 text-sm">\*Last Updated 30 May 2021</span>

---

# NPM Download Trends

<span class="italic text-gray-500 text-sm">\*Last Updated 30 May 2021</span>

<img border="rounded" src="/download-npm.png" alt="9gag" class="h-xs shadow-2xl" title="NPM Trends"/>

---

<div class="h-screen flex flex-col content-center">
  <h1 class="text-center">Big Companies Using Vue</h1>

  <div border="rounded" class="bg-white mt-14">
    <div  class="flex justify-around p-5">
      <img src="/9gag.png" alt="9gag" class="h-20" title="9gag"/>
      <img src="/apple.png" alt="apple" class="h-20 " title="Apple"/>
      <img src="/alibaba.png" alt="alibaba" class="h-20" title="Alibaba"/>
      <img src="/behance.png" alt="behance" class="h-20" title="Behance"/>
      <img src="/bukalapak.png" alt="bukalapak" class="h-20" title="Bukalapak"/>
    </div>
    <div class="flex justify-around p-5">
      <img src="/facebook.png" alt="facebook" class="h-20" title="Facebook"/>
      <img src="/font-awesome.png" alt="font-awesome" class="h-20 " title="Font Awesome"/>
      <img src="/gitlab.png" alt="gitlab" class="h-20" title="Gitlab"/>
      <img src="/investree.png" alt="investree" class="h-20" title="Investree"/>
      <img src="/netflix.png" alt="netflix" class="h-20" title="Netflix"/>
    </div>
  </div>
</div>

---

<div class="h-screen content-center">
  <h1 class="text-center my-42 h-20 leading-loose">Vue is Easy to <span class="text-yellow-500"> Use <br/> <br/> and Learn </span> </h1>
</div>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-yellow-500"> Easy to  Use and Learn </span> </h1>

<img border="rounded" src="/most-liked-vue.png" alt="Most liked aspect of Vue" class="w-2xl block mx-auto shadow-2xl" title="Most liked aspect of Vue"/>

<span class="italic text-gray-500 text-sm text-center block">https://2018.stateofjs.com/front-end-frameworks/vuejs/</span>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-yellow-500"> Easy to  Use and Learn </span> </h1>

<img border="rounded" src="/most-liked-react.png" alt="Most liked aspect of React" class="w-2xl block mx-auto shadow-2xl" title="Most liked aspect of React"/>

<span class="italic text-gray-500 text-sm text-center block">https://2018.stateofjs.com/front-end-frameworks/react/</span>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-yellow-500"> Easy to  Use and Learn </span> </h1>
<div class="relative">
  <img border="rounded" src="/the-most-inmportant.png" alt="The most inportant reason" class="w-2xl shadow-2xl" title="The most inportant reason"/>
</div>
<span class="italic text-gray-500 text-sm text-center block mt-4">https://www.monterail.com/state-of-vue-2021-report/</span>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-yellow-500"> Easy to  Use and Learn </span> </h1>
<div class="relative">
  <img border="rounded" src="/the-most-inmportant.png" alt="The most inportant reason" class="w-2xl opacity-70 shadow-2xl" title="The most inportant reason"/>
  <img border="rounded" src="/advantage.png" alt="advantage" class="w-2xl absolute top-0 right-0 shadow-2xl" title="advantage"/>
</div>
<span class="italic text-gray-500 text-sm text-center block mt-4">https://www.monterail.com/state-of-vue-2021-report/</span>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-green-600"> Good! </span> </h1>
<ul class="w-lg mt-15 block mx-auto text-lg" style="font-family: 'Press Start 2P', sans-serif">
  <li>Lightweight (20KB min+gzip)</li>
  <br>
  <li>Performant</li>
</ul>

---

<h1 class="text-center" style="font-size:24px">Vue is <span class="text-yellow-500"> Options </span> based </h1>

<div class="w-sm mx-auto mt-8">

```js {all}
new Vue({
  data: {
    message: 'Hello World!',
    count: 0,
  },
  computed: {
    fullname() {
      /* ... */
    },
  },
  methods: {
    increment() {
      this.count++;
    },
  },
});
```

</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <h1 class="text-center mb-0 tracking-tighter">Vue <span class="text-yellow-500"> 3 </span> </h1>
</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <h1 class="text-center mb-0 tracking-tighter">Vue <span class="text-yellow-500"> 3 </span> </h1>
  <div class="grid grid-rows-5 gap-y-5 text-lg mt-12">
    <span><noto-ant class="inline"/> smaller + <emojione-person-running class="inline"/> faster</span>
    <span><twemoji-star class="inline"/> new features</span>
    <span><openmoji-brick class="inline"/> exposes lower level APIs</span>
    <span><noto-triangular-ruler class="inline"/> improved TypeScript supoort</span>
    <span><fxemoji-bank class="inline"/> more maintainable codebase</span>
  </div>
</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <h1 class="text-center mb-0 tracking-tighter"> No Reactivity <br> <br> Caveats <noto-eyes class="inline text-6xl"/></h1>
</div>

---

<h1 class="text-center" style="font-size:24px">Current <span class="text-purple-400"> Reactivity Caveats </span></h1>
<div class="grid grid-rows-3 w-lg mx-auto gap-y-8 text-sm mt-12 text-green-500"  style="font-family: 'Press Start 2P', sans-serif">
  <span>- setting a new array item</span>
  <span>- adding a new object</span>
  <span>- deleting an object property</span>
</div>

---

<h1 class="text-center" style="font-size:24px">Setting a new array item</h1>

<div class="w-sm mx-auto mt-8">

```js {1-2|4-5|all}
// Vue 2
Vue.set(this.users, index, 'Antonio');

// Vue 3
this.users[index] = 'Antonio';
```

</div>

---

<h1 class="text-center" style="font-size:24px">Setting a new object property</h1>

<div class="w-sm mx-auto mt-8">

```js {1-2|4-5|all}
// Vue 2
Vue.set(this.user, age, 32);

// Vue 3
this.user.age = 32;
```

</div>

---

<h1 class="text-center" style="font-size:24px">Deleting an object property</h1>

<div class="w-sm mx-auto mt-8">

```js {1-2|4-5|all}
// Vue 2
Vue.delete(this.user, age, 32);

// Vue 3
delete this.user.age;
```

</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <h1 class="text-center mb-0 tracking-tighter"> Teleports <twemoji-hole class="inline text-6xl"/></h1>
</div>

---

<h1 class="text-center" style="font-size:24px">Teleport: Source</h1>

<div class="w-sm mx-auto mt-8">

```html {all|4}
<template>
  <div>
    <router-view>
    <div id="teleport-target"></div>
  <div>
</template>
```

</div>

---

<h1 class="text-center" style="font-size:24px">Teleport: Source</h1>

<div class="w-sm mx-auto mt-8">

```html {all|3|4-6}
<template>
  <div>
    <button @click="isRendered = !isRendered">
      Render content
    </button>
    <Teleport to="#teleport-target">
      <div>Hello World!</div>
    </Teleport>
  <div>
</template>
```

</div>

---

<Tele />

---

<h1 class="text-center" style="font-size:24px">Teleport: Use Cases</h1>

<div grid="~ gap-y-6" class="w-sm mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div>  <span class="text-yellow-500">modals</span>, <span class="text-yellow-500">notifications</span>, and <span class="text-yellow-500">popups</span> </div>
  <div> layout content like within<span class="text-yellow-500">sidebar</span>, <span class="text-yellow-500">menu</span>, and <span class="text-yellow-500">footer</span> </div>
</div>

---

<h1 class="text-center" style="font-size:24px">Sound familiar? <emojione-neutral-face class="inline text-5xl"/></h1>
<img border="rounded" src="/multiple-root.png" alt="The most inportant reason" class="w-2xl shadow-2xl mx-auto" title="The most inportant reason"/>

---

<h1 class="text-center" style="font-size:24px">In Vue 3 <span class="text-yellow-500">it Works </span> </h1>
<div class="grid grid-cols-2 mt-8 items-center">
  <div class="w-sm">

```html {all}
<template>
  <div>
    <div>Hello</div>
    <div>World!</div>
  <div>
</template>
```

<span class="italic text-gray-500 text-sm block mt-4">Vue 2</span>

  </div>

  <div class="w-sm">

```html {all}
<template>
  <div>Hello</div>
  <div>World!</div>
</template>
```

<span class="italic text-gray-500 text-sm block mt-4">Vue 3</span>

  </div>
</div>

---

<h1 class="text-center" style="font-size:24px">Multiple <span class="text-yellow-500">v-model</span>s </h1>
<div class="grid grid-rows-2 mt-8 justify-center">
  <div class="w-lg">
  
```html {all}
<template>
  <CustomForm v-model="name" />
</template>
```

<span class="italic text-gray-500 text-sm block mt-4">Vue 2</span>

  </div>

  <div class="w-lg">

```html {all}
<template>
  <CustomForm v-model:name="name" v-model:email="email" />
</template>
```

<span class="italic text-gray-500 text-sm block mt-4">Vue 3</span>

  </div>
</div>

---

<h1 class="text-center" style="font-size:24px"><openmoji-brick class="inline text-6xl"/> Composition API</h1>

<div grid="~ gap-y-6" class="w-2xl mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div><fxemoji-squarednew class="inline"/> Advanced Feature </div>
  <v-click>
    <div><carbon-add-filled class="inline"/> Addition to the current API</div>
    <div><emojione-ambulance class="inline"/> Options API is <span class="text-green-400">not</span> being deprecated</div>
  </v-click>
</div>

---

<h1 class="text-center" style="font-size:24px">Why Composition API</h1>

<div grid="~ gap-y-6" class="w-sm mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div><flat-color-icons:folder class="inline"/> Code organiztion </div>
  <v-click>
    <div><system-uicons:reuse class="inline text-green-300"/> Logic Reuse</div>
  </v-click>
</div>

---

<h1 class="text-center" style="font-size:24px">Composition API <span class="text-purple-400">Benefits</span></h1>

<div grid="~ gap-y-6" class="w-lg mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div><carbon-dot-mark class="inline text-green-300"/> Extremly Flexible </div>
  <div><carbon-dot-mark class="inline text-green-300"/> Clear source of properties</div>
  <div><carbon-dot-mark class="inline text-green-300"/> Performance</div>
  <div><carbon-dot-mark class="inline text-green-300"/> No namespace collision</div>
</div>

---

<h1 class="text-center" style="font-size:24px">Good Fit For</h1>

<div grid="~ gap-y-6" class="w-2xl mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <v-clicks>
    <div>component code grows <span class="text-yellow-400">too long</span></div>
    <div><span class="text-yellow-400">team</span> that work on the <span class="text-yellow-400">same (big) components</span></div>
    <div><span class="text-yellow-400">reuse component options</span> without using mixins</div>
    <div>When <span class="text-yellow-400">TypeScript</span> support is important</div>
  </v-clicks>
  <div class="text-center"><span class="text-purple-400">(own opinion)</span></div>
</div>

---

<h1 class="text-center" style="font-size:24px"><span class="text-yellow-400">Drawbacks</span> of Composition API</h1>

<div grid="~ gap-y-6" class="w-2xl mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div class="text-center"><span class="text-purple-400">(own opinion)</span></div>
  <v-clicks>
    <div><carbon-dot-mark class="inline text-yellow-300"/> Overhead of introducing <span class="text-yellow-400">refs</span></div>
    <div><carbon-dot-mark class="inline text-yellow-300"/> learning curve</div>
  </v-clicks>
</div>

---

<h1 class="text-center" style="font-size:24px">Consider</h1>

<div grid="~ gap-y-6" class="w-2xl mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <v-clicks>
    <div><span class="text-yellow-400">No</span> need to <span class="text-yellow-400">rewrite yout vue 2 app</span></div>
    <div><span class="text-yellow-400">No</span> need to <span class="text-yellow-400">use it in a simple component</span></div>
  </v-clicks>
  <div class="text-center"><span class="text-purple-400">(own opinion)</span></div>
</div>

---

<h1 class="text-center" style="font-size:24px">Suspense</h1>

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <span class="text-center block text-xl leading-loose" style="font-family: 'Press Start 2P', sans-serif">
    Renders some <span class="text-yellow-400">fallback content</span> instead of a component <span class="text-yellow-400">until a condition is met</span>
  </span>
</div>

---

<h1 class="text-center" style="font-size:24px">Suspense</h1>

<div class="mt-10 mx-auto w-sm">
  
```html {1,8|5-7|2-4}
<Suspense>
  <template #default>
    <UserProfile />
  </template>
  <template>
    <div>Loading...</div>
  </template>
</Suspense>
```

</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <span class="text-center block text-6xl leading-loose text-yellow-400" style="font-family: 'Press Start 2P', sans-serif">
    Filters
  </span>
</div>

---

<h1 class="text-center" style="font-size:24px">#nofilter</h1>

<div class="mt-10 mx-auto w-sm relative">
  <ant-design:close-outlined class="absolute top-4 right-10 text-6xl text-red-500"/>

```html {all}
<template>
  <div>{{ amount | dollars }}</div>
</template>
```

</div>

---

<h1 class="text-center" style="font-size:24px">#nofilter</h1>

<div class="mt-10 mx-auto w-sm relative">
  <akar-icons:check class="absolute top-4 right-10 text-6xl text-green-500"/>

```html {all}
<template>
  <div>{{ dollars(amount) }}</div>
</template>
```

</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <span class="text-center block text-2xl leading-loose" style="font-family: 'Press Start 2P', sans-serif">
    No more dilemas <noto-party-popper class="inline" />
  </span>
</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <span class="text-center block text-2xl leading-loose" style="font-family: 'Press Start 2P', sans-serif">
    Quite some more <span class="text-yellow-400">changes</span>
  </span>
  <div grid="~ gap-y-6" class="w-lg mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
    <div><carbon-dot-mark class="inline text-green-300"/> Fragments </div>
    <div><carbon-dot-mark class="inline text-green-300"/> Emits Component Option</div>
    <div><carbon-dot-mark class="inline text-green-300"/> create custom renderers</div>
    <div><carbon-dot-mark class="inline text-green-300"/> Global mounting API change</div>
    <div><carbon-dot-mark class="inline text-green-300"/> ...</div>
  </div>
</div>

---

<div class="absolute top-1/2 left-1/2 transform-gpu -translate-x-1/2 -translate-y-1/2">
  <span class="text-center block text-2xl leading-loose" style="font-family: 'Press Start 2P', sans-serif">
    Vue 3 will not break your apps <emojione-v1:white-heavy-check-mark class="inline" />
  </span>
</div>

---

<h1 class="text-center" style="font-size:24px">Why <span class="text-purple-400">upgrade</span> to <span class="text-yellow-400">Vue 3</span>?</h1>

<div grid="~ gap-y-6" class="w-3xl mx-auto mt-8 leading-loose" style="font-family: 'Press Start 2P', sans-serif">
  <div><carbon-dot-mark class="inline text-green-300"/> Massive performance improvements </div>
  <div><carbon-dot-mark class="inline text-green-300"/> Exceptional reusability possibilities</div>
  <div><carbon-dot-mark class="inline text-green-300"/> New Features</div>
  <div><carbon-dot-mark class="inline text-green-300"/> New design patterns for scale</div>
  <div><carbon-dot-mark class="inline text-green-300"/> TypeScript</div>
</div>

---

<h1 style="font-size:16px">Thanks, Any feedback would be appreciated</h1>
<div class="flex w-sm my-10 items-center">
  <img src="/lucky.jpg" class="h-20 rounded-full shadow-2xl">
  <div class="ml-5">
    <span class="block mb-2" style="font-family: 'Press Start 2P', sans-serif">Lucky DS</span>
    <span class="block mb-2">Frontend Engineer</span>
    <a href="tel:085156501865" class="text-xs">085156501865</a>
  </div>
</div>

<div style="font-family: 'Press Start 2P', sans-serif">Tech Stack</div>

<div border="rounded" class="bg-white mt-2">
  <div class="flex justify-around p-5">
    <img src="/vue-logo.png" alt="vue" class="h-20" title="vue"/>
    <img src="/slide_dev.png" alt="slidev" class="h-20 " title="slidev"/>
    <img src="/cloudfare.png" alt="cloudfare" class="h-20" title="cloudfare"/>
    <img src="/github.png" alt="github" class="h-20" title="github"/>
    <img src="/vite.svg" alt="vite" class="h-20" title="vite"/>
  </div>
</div>
