# zz

zz (Chinese word for **Regex Expression** is **正则表达式**, the 'pin yin' is `zheng4 ze2 biao3 da2 shi4`, and **zz** for short).

## Hello World

```
^
hello
|
world
$
```

Result:

```
^hello|world$
```

## Pro

```
(
(?:\r?\n|^)
#\s+
\.*?
(?=r\?\n)
)*

(
(?:\r?\n|^)
.*
)*


```

Result:

```
```

## src / js

```js
const fs = require('fs')

const zz = fs.readFileSync('test.txt', { encoding: 'utf8' })
const zzz = zz.replaceAll(/\r?\n/g, '')
const r = new RegExp(zzz, 'g')
```
