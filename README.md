TypeScript Module "esnext" Demo
===========================

当`tsconfig.json`中`module`设为`esnext`的时候，`moduleResolution`也必须设置为`node/classic`，
typescript才能正确找到module，否则使用的第三方module都会提示"module not found"

同时，如果是运行于node，那么还需要配合webpack等，才能正确生成最终的bundle文件。

```
npm install
npm run demo
```
