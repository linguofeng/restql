# koa-restql

## 安装

```bash
$ yarn add @linguofeng/koa-restql
```

## 使用

```js
import Koa from 'koa';
import { restql } from '@linguofeng/koa-restql';

const main = async () => {
  const app = new Koa();

  app.use(restql(
    tag: 'gql',
  ));

  app.listen(8123, () => {
    console.log('server running on 8123');
  });
};

main();

```
