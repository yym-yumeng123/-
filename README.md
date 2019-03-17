# 记录一些常用的npm工具包

## npm常用工具包


#### 1. nrm -- NPM registry manager
```
$ npm install -g nrm
```

```
$ nrm ls

* npm -----  https://registry.npmjs.org/
  cnpm ----  http://r.cnpmjs.org/
  taobao --  https://registry.npm.taobao.org/
  nj ------  https://registry.nodejitsu.com/
  rednpm -- http://registry.mirror.cqupt.edu.cn
  skimdb -- https://skimdb.npmjs.com/registry
```

```
$ nrm use cnpm  //switch registry to cnpm

    Registry has been set to: http://r.cnpmjs.org/
```

#### 2. http-server: a command-line http server

```
npm install http-server -g
 
Usage:
  http-server [path] [options]
```

#### 3. git-open: 打开github website

```
npm install --global git-open


$ git open
# opens https://github.com/TRACKED_REMOTE_USER/CURRENT_REPO/tree/CURRENT_BRANCH 
 
$ git open someremote
# opens https://github.com/PROVIDED_REMOTE_USER/CURRENT_REPO/tree/CURRENT_BRANCH 
 
$ git open someremote somebranch
# opens https://github.com/PROVIDED_REMOTE_USER/CURRENT_REPO/tree/PROVIDED_BRANCH 
 
$ git open --issue
# If branches use naming convention of issues/#123, 
# opens https://github.com/TRACKED_REMOTE_USER/CURRENT_REPO/issues/123 
```


## 4. Vue 常用npm包
#### 4-1. fastclick
```
// 解决移动端300ms延迟的问题
npm install fastclick

use 
import fastclick from 'fastclick';
fastclick.attach(document.body)
```

#### 4-2. better-scroll
```
better-scroll 是一款重点解决移动端（现已支持 PC 端）各种滚动场景需求的插件。

npm isntall better-scroll
```
[使用地址https://github.com/ustbhuangyi/better-scroll]()

#### 4-3 vue-lazyload
```
npm i vue-lazyload -S
```
[使用地址](https://github.com/hilongjw/vue-lazyload)
