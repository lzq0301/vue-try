# vue-try

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## vue try
This project build step
```
mkdir vue-try
cnpm install --global vue-cli
vue init webpack vue-try
cd vue-try
cnpm install
cnpm run dev
git init
git remote add origin https://github.com/lzq0301/vue-try.git
git add .
git push -u origin master
```

### try some
1. 新建链接页面
    * router/==index.js== 里添加可访问得链接地址
    * components中添加自己的==MyHelloWorld.vue==页面

