# vue-awesome-swiper

[vue-awesome-swiper](https://github.com/surmon-china/vue-awesome-swiper)  

` npm install vue-awesome-swiper --save`

CDN Example https://jsfiddle.net/bL983fjt/

 
### Doc 

[Swiper Parameters](https://idangero.us/swiper/api/)  

Swiper3  

[slidesPerView](https://3.swiper.com.cn/api/Slides_grid/2014/1215/24.html): 'auto'  
[centeredSlides](https://3.swiper.com.cn/api/Slides_grid/2014/1217/50.html): true
[spaceBetween](https://3.swiper.com.cn/api/Slides_grid/2015/0308/198.html):20


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
