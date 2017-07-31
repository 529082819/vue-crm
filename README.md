**demo**: [https://taylorchen709.github.io/vue-admin/](https://taylorchen709.github.io/vue-admin/)

# 说明
非常简单的一个vue2后台管理系统：

* 1、vuex状态管理
* 2、axios前后端接口交互、本地mock数据
* 3、使用element-UI前端UI框架
* 4、router单页运用
* 5、webpack构建整个项目

# To start

This is a project template for [vue-cli](https://github.com/vuejs/vue-cli)

``` bash
# install dependencies
npm install

# 开发环境 at localhost:8081
npm run dev

# build for production with minification 生产环境
npm run build

```

# Folder structure
* build - webpack config files  webpack配置
* config - webpack config files  
* dist - build   构建文件
* src -your app
    * api
    * assets
    * common
    * components - your vue components
    * mock
    * styles
    * views - your pages
    * vuex
    * App.vue
    * main.js - main file
    * routes.js
* static - static assets

# mock
开发环境支持mock数据

# vuex
开发环境支持mock数据

# Theme
可以改变默认颜色
You can change theme by 
1. Generate theme packages by [https://elementui.github.io/theme-preview/#/](https://elementui.github.io/theme-preview/#/)
2. Put theme packages in src/assets/theme/
3. Edit src/main.js 
``` bash
   import 'element-ui/lib/theme-default/index.css'
   to
   import './assets/theme/your-theme/index.css'
```
4. Edit src/styles/vars.scss

![theme-blue](https://raw.githubusercontent.com/taylorchen709/markdown-images/master/vueadmin/rec-demo.gif)
![theme-green](https://raw.githubusercontent.com/taylorchen709/markdown-images/master/vueadmin/theme-green.png)

# Browser support

Modern browsers and IE 10+.

# License
[MIT](http://opensource.org/licenses/MIT)
