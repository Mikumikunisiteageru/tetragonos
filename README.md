[//]: # (tetragonos/readme.md)
[//]: # (20190114)

# tetragonos

`tetragonos` 是一个能标注汉字四角号码的 LaTeX 宏包。

## 用法

`\getTG{<string>}`：计算汉字字符串`<string>`中第一个汉字的四角号码（新版，带附笔号码）。

举个栗子，`\getTG{汉}` 与 `\getTG{汉字}` 都会展开成“汉”字的四角号码，即 `37140`。

## 范例

`tetragonos-example.tex` 中示范了 `tetragonos` 宏包与 `glossaries` 宏包的联合应用，该文件为一段古文中出现的全部植物名称建立了首字四角号码索引。事实上，字词索引是四角号码最常出现的地方了。

## 杂谈

明天下午再写
