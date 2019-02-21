### ava
---
https://github.com/avajs/ava

```
npm init ava
yarn add ava --dev
npm install --save-dev ava
npm test
npm ava
npm ava --watch
```

```json
{
  "name": "awesome-package",
  "scripts": {
    "test": "ava"
  },
  "devDependencies": {
    "ava": "^1.0.0"
  }
}
```

```js
import test from 'ava';

test('foo', t => {
  t.pass();
});

test('var', async t => {
  const bar = Promise.resolve('bar');
  t.is(await bar, 'bar');
});


```


