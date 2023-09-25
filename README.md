<p align="center">
  <img src="" alt="Hello Word 👋, I'm Matheus Stopinski ✨😎  I'm a 🚀 French developer 🚀 ❤️ creative and happy ❤️">
</p>

import Vue from "vue";
import App from "./App.vue";
import Typewriter from "typewriter-effect/dist/core";
import GraphemeSplitter from "grapheme-splitter";

Vue.config.productionTip = false;

new Vue({
  render: h => h(App)
}).$mount("#app");

const innerdemo = document.getElementById("inner-demo-2");

const stringSplitter = string => {
  const splitter = new GraphemeSplitter();
  return splitter.splitGraphemes(string);
};

const typewriter = new Typewriter(innerdemo, {
  loop: true,
  delay: 45,
  stringSplitter
});

typewriter
  .typeString("Hi 👋, I'm Matheus Stopinski ✨😎")
  .pauseFor(1000)
  .deleteAll()
  .typeString("I'm a 🚀 French developer 🚀")
  .pauseFor(1000)
  .deleteAll()
  .typeString("❤️ creative and happy ❤️")
  .pauseFor(1000)
  .deleteAll()
  .start();




<h2 align="center">In love with this front-end world, what motivates me most is bringing my creativity to life!</h2 >
<br>

- 🔭 I'm currently working on [Site Indigena](https://github.com/MatheusStopinski/MasterOfInterfaces/tree/Site_Indigena)

- 💬 Ask me about: **Technology, front-end, mobile development and metaverse! I would be happy to talk about 😃

- ⚡ Fun fact: **I've been meditating for 10 years, I practice martial arts, I'm writing a book and I'm very creative, no matter what I do!**
