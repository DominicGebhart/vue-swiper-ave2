## CHANGELOG of Vue-Swiper-ave5

### v5.0.0
- **Created fork**
- Updated all dependencies

### v4.0.0

- **Created fork**
- Added type information https://github.com/surmon-china/vue-awesome-swiper/pull/458
- fix: change some demo's wrong tag https://github.com/surmon-china/vue-awesome-swiper/pull/446
- keep component alive during page transition https://github.com/surmon-china/vue-awesome-swiper/pull/388
- fix #286 https://github.com/surmon-china/vue-awesome-swiper/pull/377
- Fix: When destroying a component with an not initialized swiper https://github.com/surmon-china/vue-awesome-swiper/pull/341
- Update nuxt-ssr-example.vue SSR example didnt worked for me (nuxt 1.4 / eslint 3.4.0) needed to add :key for banner https://github.com/surmon-china/vue-awesome-swiper/pull/331
- Fix component ssr https://github.com/surmon-china/vue-awesome-swiper/pull/350

## CHANGELOG of vue-awesome-swiper

### v3.1.3

fixed bug with swiper inside transition. #276

### v3.1.2

update webpack config and rebuild.

### v3.1.1

fix emit event in browser

### v3.1.0

1. fix loop bug
2. [bind swiper events to vuejs events](https://github.com/surmon-china/vue-awesome-swiper/pull/238)

### v3.0.7

1. remove reloop function
2. update ssr example

### v3.0.5

1. update swiper version to v4.0.7

### v3.0.4

1. fix object assign in spa

### v3.0.3

1. fix reLoop method [#205](https://github.com/surmon-china/vue-awesome-swiper/issues/205)

### v3.0.2

1. fix ssr build bug

### v3.0.1

1. fix the es module export issue

### v3.0.0

#### use
1. add global default options
2. update the options assign logic
3. Update to [Swiper4](http://www.swiper.com.cn)

#### project
- add brower support
- add test scripts
- update babel and webpack configs
