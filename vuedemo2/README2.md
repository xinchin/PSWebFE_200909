## 參考

[Vue -真正的应用程序(Vuex，路由器，节点)的完整指南 | Udemy](https://www.udemy.com/course/draft/2297174/learn/lecture/14196758#notes)


---------

> vue init webpack vuedemo2

> cd vuedemo2

> npm run dev

--------
**此專案是不含「路由」**

```
λ vue init webpack vuedemo2

? Project name vuedemo2
? Project description A Vue.js project
? Author Nelson Huang <xinchin@gmail.com>
? Vue build standalone
? Install vue-router? No
? Use ESLint to lint your code? No
? Set up unit tests No
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recommended) npm
```


---------

```
nelson.huang@wan014033 /d/RD_2020/MyRepo/PSWebFE_200909 (dev/work)
λ vue init webpack vuedemo2

? Project name vuedemo2
? Project description A Vue.js project
? Author Nelson Huang <xinchin@gmail.com>
? Vue build standalone
? Install vue-router? No
? Use ESLint to lint your code? No
? Set up unit tests No
? Setup e2e tests with Nightwatch? No
? Should we run `npm install` for you after the project has been created? (recommended) npm

   vue-cli · Generated "vuedemo2".


# Installing project dependencies ...
# ========================

npm WARN deprecated extract-text-webpack-plugin@3.0.2: Deprecated. Please use https://github.com/webpack-contrib/mini-css-extract-plugin
npm WARN deprecated browserslist@2.11.3: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.
npm WARN deprecated bfj-node4@5.3.1: Switch to the `bfj` package for fixes and new features!
npm WARN deprecated core-js@2.6.11: core-js@<3 is no longer maintained and not recommended for usage due to the number of issues. Please, upgrade your dependencies to the actual version of core-js@3.
npm WARN deprecated fsevents@1.2.13: fsevents 1 will break on node v14+ and could be using insecure binaries. Upgrade to fsevents 2.
npm WARN deprecated browserslist@1.7.7: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.

> core-js@2.6.11 postinstall D:\RD_2020\MyRepo\PSWebFE_200909\vuedemo2\node_modules\core-js
> node -e "try{require('./postinstall')}catch(e){}"

Thank you for using core-js ( https://github.com/zloirock/core-js ) for polyfilling JavaScript standard library!

The project needs your help! Please consider supporting of core-js on Open Collective or Patreon:
> https://opencollective.com/core-js
> https://www.patreon.com/zloirock

Also, the author of core-js ( https://github.com/zloirock ) is looking for a good job -)


> ejs@2.7.4 postinstall D:\RD_2020\MyRepo\PSWebFE_200909\vuedemo2\node_modules\ejs
> node ./postinstall.js

Thank you for installing EJS: built with the Jake JavaScript build tool (https://jakejs.com/)


> uglifyjs-webpack-plugin@0.4.6 postinstall D:\RD_2020\MyRepo\PSWebFE_200909\vuedemo2\node_modules\webpack\node_modules\uglifyjs-webpack-plugin
> node lib/post_install.js

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@~2.1.2 (node_modules\chokidar\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@2.1.3: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules\watchpack-chokidar2\node_modules\chokidar\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN optional SKIPPING OPTIONAL DEPENDENCY: fsevents@^1.2.7 (node_modules\webpack-dev-server\node_modules\chokidar\node_modules\fsevents):
npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.13: wanted {"os":"darwin","arch":"any"} (current: {"os":"win32","arch":"x64"})
npm WARN ajv-keywords@3.5.2 requires a peer of ajv@^6.9.1 but none is installed. You must install peer dependencies yourself.

added 1266 packages from 672 contributors and audited 1273 packages in 158.124s
found 17 vulnerabilities (3 low, 8 moderate, 6 high)
  run `npm audit fix` to fix them, or `npm audit` for details




# Project initialization finished!
# ========================

To get started:

  cd vuedemo2
  npm run dev

Documentation can be found at https://vuejs-templates.github.io/webpack


nelson.huang@wan014033 /d/RD_2020/MyRepo/PSWebFE_200909 (dev/work)
λ
```

```
nelson.huang@wan014033 /d/RD_2020/MyRepo/PSWebFE_200909 (dev/work)
λ cd vuedemo2/
nelson.huang@wan014033 /d/RD_2020/MyRepo/PSWebFE_200909/vuedemo2 (dev/work)
λ npm run dev

> vuedemo2@1.0.0 dev D:\RD_2020\MyRepo\PSWebFE_200909\vuedemo2
> webpack-dev-server --inline --progress --config build/webpack.dev.conf.js

 12% building modules 22/27 modules 5 active ...o\PSWebFE_200909\vuedemo2\src\App.vue{ parser: "babylon" } is deprecated; we now treat it as { parser: "babel" }.
 95% emitting

 DONE  Compiled successfully in 7966ms                                                                                                                                                      16:53:10

 I  Your application is running here: http://localhost:8080
 ```

--------



