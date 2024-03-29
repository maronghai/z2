# ZZ

**ZZ** (In Chinese, the term "Regex" translates to "正则", pronounced as "Zheng4 Ze2", and is ofen abbreviated as "ZZ".)  is a Regex expression tool designed to streamline the development process for Regex expression projects, offering a faster and more efficient experience. It is composed of two primary components.

1. Multi-line regex expression
2. Inline comment

## Hello World

```asm
^       ; Here is start
hello   ; Here is 'hello'
|       ; Here is `or`
world   ; Here is 'world'
$       ; Here is end
```

Result:

```asm
^hello|world$
```

## zz.zz

```asm
(?:
  (?:[ ]*)        ; spaces prefix
  (?:.*?)         ; Regex expression
  (?: {3,};.*)?   ; Commen with three or more spaces and ';' prefix
  \n              ; new line
)*
```

## Echosystem

1. [DB Create](https://github.com/maronghai/dbcreate)

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 2023-present, Ronghai Ma
