# zz

zz (Chinese word for **Regex Expression** is **正则表达式**, the 'pin yin' is `zheng4 ze2 biao3 da2 shi4`, and **zz** for short).

## Hello World

```
^       ; Here is start
hello   ; Here is 'hello'
|       ; Here is `or`
world   ; Here is 'world'
$       ; Here is end
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
