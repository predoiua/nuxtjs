

Todo:
Site

how:
- bootstrap - librarie - template de site 

- site generator - jekyll
https://nuxtjs.org/



npx create-nuxt-app citat

http://localhost:3000


cd citat
npm install --save nuxt
mkdir pages
vi pages/index.vue
<template>
  <h1>Hello world!</h1>
</template>
npm run dev

Static generate:
Upgrade nuxt to 2.13.0
Set target: 'static' in your nuxt.config.js
Run nuxt build && nuxt export instead of nuxt generate