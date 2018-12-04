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
