# graceful-weui-wxss

## develop

```
$ git clone https://github.com/very-k/graceful-weui.git
```

* Install wepy

```
$ npm install wepy-cli -g
```

* Install dependencies

```
$ npm install
```

Using Yarn:

```
$ yarn
```

* Start dev Server

```
$ npm run dev
```

Using Yarn:

```
$ yarn dev
```

* 开发者工具使用

  1. 使用微信开发者工具新建项目，本地开发选择dist目录。
  2. 微信开发者工具-->项目-->关闭ES6转ES5。重要：漏掉此项会运行报错。
  3. 微信开发者工具-->项目-->关闭上传代码时样式自动补全 重要：某些情况下漏掉此项会也会运行报错。
  4. 微信开发者工具-->项目-->关闭代码压缩上传 重要：开启后，会导致真机computed, props.sync 等等属性失效。
  5. 项目根目录运行wepy build --watch，开启实时编译。

## Links

* [Documentation](https://tencent.github.io/wepy/)
