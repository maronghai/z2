# ZZ

**ZZ** (Chinese word for **Regex** is **正则**, the 'Pin Yin' is `Zheng4 Ze2`, **ZZ** for short).

## Features

1. Multi-line regex expression
2. Inline comment

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

```javascript
/(?: {3,};.*?)?\n/g
```
