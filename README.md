<p align="center">
    <img src="sample.jpg" width="450">
</p>

# vue-cosha

Vue cosha is a simple port of the [cosha](https://github.com/robinloeffel/cosha) library for ease of use in Vue projects.

> "Colorful shadows for your images. 🎨"

[cosha](https://npm.robinloeffel.ch/cosha) lets you add **co**lorful **sha**dows to your images. Try it out and look for yourself—the bundle is only less than 1kb small and it couldn't be easier to set up!

## How

```
npm i vue-cosha
```

```js
import Vue from "vue";
import VueCosha from "vue-cosha";

Vue.use(VueCosha);
```

```vue
<!-- regular old img tag -->
<template>
  <img src="my-dope-pic.jpg" alt="mmmhm" v-cosha />
</template>
```

## Nuxt

```
npm i vue-cosha
```

Create a file called `vue-chosha.js` in your plugins folder with the following inside

```js
import Vue from "vue";
import VueCosha from "vue-cosha";

Vue.use(VueCosha);
```

Register the plugin in your `nuxt.config.js`

```js
plugins: [
    '~/plugins/vue-cosha'
],
```

```vue
<!-- regular old img tag -->
<template>
  <img src="my-dope-pic.jpg" alt="mmmhm" v-cosha />
</template>
```

## Config

Everything in the config is optional. The default values are:

```js
import VueCosha from "vue-cosha";

Vue.use(VueCosha, {
  className: "cosha",
  blur: "5px",
  brightness: 1,
  saturation: 1,
  x: 0,
  y: 0,
  index: 0
});
```

If you like this package please support the original developer!
