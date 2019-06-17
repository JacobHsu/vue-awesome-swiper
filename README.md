# vue-awesome-swiper

[vue-awesome-swiper](https://github.com/surmon-china/vue-awesome-swiper)  

` npm install vue-awesome-swiper --save`

CDN Example https://jsfiddle.net/bL983fjt/


### github vue cli 3
delete `README.md`  
`$ vue create vue-awesome-swiper`   
merge 

`$ cd vue-awesome-swiper`  
`$ yarn serve`  

package.json
```js
  "name": "v-awesome-swiper",
```
project name同名npm無法安裝　


mount with global

main.js  
```js
import Vue from 'vue'
import VueAwesomeSwiper from 'vue-awesome-swiper'

// require styles
import 'swiper/dist/css/swiper.css'

Vue.use(VueAwesomeSwiper)
```　

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn run serve
```

### Compiles and minifies for production
```
yarn run build
```

### Run your tests
```
yarn run test
```

### Lints and fixes files
```
yarn run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
