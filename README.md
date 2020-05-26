# babel-plugin-miniapp-promise

es6 promise polyfill for wechat miniapp(promise-polyfill针对小程序兼容的plugins版本)

## Use

1、Installation

```
npm install -D babel-plugin-miniapp-promise promise-polyfill
```

2、Set babel plugin config

```
{
 "plugins": ["miniapp-promise"]
}
```

3、If you configured ``transform-runtime plugins config``, you need to disable polyfill...

```
[' transform-runtime', {'polyfill': false}]
```
