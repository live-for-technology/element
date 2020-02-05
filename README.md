## 怎么创建一个组件
- 组件本身
- 组件的文档

## 组件本身
在packages里添加组件的目录hello-world
packages
  -- index.js
  -- src
    -- hello-world.vue
在conponents.json中注册组件。
样式不要写在这里，样式写在单独的样式文件里目录是packages/theme-chalk-src/hello-world.scss
## 组件文档
examples/docs/zh-CN这个代表中文的，还有别的语言，在里面创建hello-world.md

然后要在examples/nav.config.json中注册文档的路由
