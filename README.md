# vue-scroll-trigger
Forked from liran319 with added options for elem offsets. Useful when you have elements with full screen height.

## Install

#### with `yarn` :
`yarn add @dsgn.tw/vue-scroll-trigger`

#### or with `npm` :
`npm install @dsgn.tw/vue-scroll-trigger --save`

## Usage

```javascript
import vueScrollTrigger from '@dsgn.tw/vue-scroll-trigger'

Vue.use(vueScrollTrigger, {
  activeClass: 'active' // active is the default triggered className
  offsetTop: 100,
  offsetBottom: 100,
});
```
