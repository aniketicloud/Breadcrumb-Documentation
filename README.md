# <a href="https://vuejs.org" target="_blank"><img valign="text-bottom" height="49" src="https://vuejs.org/images/logo.png"></a> breadcrumbs 
> Vue breadcrumbs builds on the official [vue-router](https://github.com/vuejs/vue-router) package to provide simple breadcrumbs. [Demo](https://scrum.github.io/vue-2-breadcrumbs/)

[![Actions Status](https://github.com/Scrum/vue-2-breadcrumbs/workflows/Actions%20Status/badge.svg?style=flat-square)](https://github.com/Scrum/vue-2-breadcrumbs/actions?query=workflow%3A%22CI+tests%22)[![vue2](https://img.shields.io/badge/vue-2.x-brightgreen.svg?style=flat-square)](https://vuejs.org/)[![node](https://img.shields.io/node/v/post-sequence.svg?style=flat-square)]()[![npm version](https://img.shields.io/npm/v/vue-2-breadcrumbs.svg?style=flat-square)](https://www.npmjs.com/package/vue-2-breadcrumbs)[![Dependency Status](https://david-dm.org/scrum/vue-2-breadcrumbs.svg?style=flat-square)](https://david-dm.org/scrum/vue-2-breadcrumbs)[![XO code style](https://badgen.net/xo/status/chalk?style=flat-square)](https://github.com/sindresorhus/xo)[![Coveralls status](https://img.shields.io/coveralls/Scrum/vue-2-breadcrumbs.svg?style=flat-square)](https://coveralls.io/r/Scrum/vue-2-breadcrumbs)

[![npm downloads](https://img.shields.io/npm/dm/vue-2-breadcrumbs.svg?style=flat-square)](https://www.npmjs.com/package/vue-2-breadcrumbs)[![npm](https://img.shields.io/npm/dt/vue-2-breadcrumbs.svg?style=flat-square)](https://www.npmjs.com/package/vue-2-breadcrumbs)[![size](https://badgen.net/bundlephobia/minzip/vue-2-breadcrumbs?color=364a5e&style=flat)](https://www.npmjs.com/package/vue-2-breadcrumbs)

## Support
- Support SSR
- Setting parent route without need to actually nest it in children array
- Customized template
- Dynamic breadcrumbs 
- Dynamic parent 
- Dynamic label 
- Shorthand labeling (`breadcrumb: 'Page Label'`)
- Sub-routing


## Install

```bash
$ npm install vue-2-breadcrumbs
```

> **Note:** This project is compatible with node v10+


## Usage

```js
import Vue from 'vue';
import VueBreadcrumbs from 'vue-2-breadcrumbs';
import App from './App.vue';

Vue.use(VueBreadcrumbs);
```
> Note: After that `<Breadcrumbs/>` component would be at your disposal.