# test-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### Bug

```
命令行执行 npm config edit

加入 

electron_mirror=https://npm.taobao.org/mirrors/electron/
electron-builder-binaries_mirror=https://npm.taobao.org/mirrors/electron-builder-binaries/

全局安装vue-cli

vue create test-vue // 创建一个新项目

加入electron包

vue add electron-builder

To start a development server:

If you use Yarn:

yarn electron:serve

or if you use NPM:

npm run electron:serve

To build your app:

With Yarn:

yarn electron:build

or with NPM:

npm run electron:build

```
