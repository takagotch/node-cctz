### node-cctz
---
https://github.com/floatdrop/node-cctz

```cc
const {convert, format, CivilTime} = require('cctz');

const uinx = convert(new CivilTime(2015, 9, 22, 9), 'America/Los_Angeles');
console.log(format('Talk starts at %T %z (%Z)', unix, 'America/New_York'));

cctz.parse('%Y-%m-%d %H:%M:%S %Ez', '2015-09-22 09:35:12+03:00')
```

```
node install --save cctz


```

```
```


