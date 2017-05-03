##  <span style="color: #e49436;">Quick and Easy -  NPM Modules</span>
<div style="color:grey;font-size: 0.6em">
Be smart and make a node module!
</div>

---

### <span style="color: #e49436; text-transform: none">WHAT WE NEED, AND, WHY</span>

+++
#### Avoid code repetition
- <span style="color: #666666">There're lot of code repeated in our repos<span>
- <span style="color: #666666">Break them into small utilities, with unit tests<span>

+++
#### More open source activities
- <span style="color: #666666">Good chance to contribute to open source<span>
- <span style="color: #666666">NODE community is active<span>
- <span style="color: #666666">We get development/bug-fixes for free<span>
- <span style="color: #666666">But, should actively maintain the projects<span>

+++
#### Be creative and smart
- <span style="color: #666666">Look in our code -- find repeating patterns<span>
- <span style="color: #666666">Don't like the other library/module ? Make a better one<span>
- <span style="color: #666666">Be creative<span>

---

### <span style="color: #e49436; text-transform: none">BOOTSTRAPPING IS HARD</span>

+++
### It's 2017
  - Write code in ES6
  - Babel, Babel plugins, Typescript
  - Webpack, Rollup, Gulp, Browserify 
  - **TDD:** AVA, Mocha, Jest

+++ 
### The List Goes on ...
  - .npmrc, .babelrc, .jshintrc, .eslintrc
  - Prettier, JSFormatter ... 

---

### <span style="color: #e49436; text-transform: none">SOLUTION ?</span>

Start with a simple seed/boilerplate template.

+++?image=assets/npm-module.png
<div style="padding: 10px; background-color: #000">
<h2><span style="color: #e49436">Meet npm-module<span></h2>
[https://github.com/shidhincr/npm-module](https://github.com/shidhincr/npm-module)
</div>
+++
- Opinionated ( The libraries for build/test/bundle ) are already chosen.
- Zero configuration
- Just 3 npm scripts
- Will be moved to Namshi repo soon.

---
### Let's Start

+++?image=assets/clone.png
+++
### Install: Just run the command `yarn`
![install](assets/yarn-install.png)
+++?image=assets/edit-changes.png
+++?image=assets/scripts.png
+++?image=assets/test.png
+++
### Build
![build](assets/build.png)
+++
### Build
![rollup](assets/rollup-config.png)
+++?image=assets/code-package-json.png
+++
### ICONS
![build](assets/flat-icon0.png)
![rollup](assets/flat-icon1.png)

---
### Release and Publish to NPM
Using `np` and `release`
![build](assets/release.png)
---

## <span style="color: #e49436; text-transform: none">THANKS</span>

### [@shidhincr](https://twitter.com/shidhincr)