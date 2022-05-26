# 读我

本仓库可视为在原始仓库基础上追加中文翻译，查看原始 [英文 ENGLISH](./original_README.md) 读我，原始仓库地址为：[munificent/craftinginterpreters](https://github.com/munificent/craftinginterpreters) ，原始在线英文网站为：[craftinginterpreters.com](https://www.craftinginterpreters.com/) 。

### 翻译说明

- 为了准确性考虑，一般引用的人名、书名不做翻译（如有特殊情况，会在括号中标出，或留下译者注注解等字眼）
- 代码中注释一概不做翻译
- 一些特殊专用技术名词不做翻译
- 较难翻译或无法准确表达含义的，使用原始英文，后续通过 issue 审阅校准之后修正为中文

### 译文

中文译文位于 [book_zh](./book_zh/) 目录下 ，英文位于原始的 [book](./book/) 目录下，而不受影响。

### 静态页面

安装好 [dart](https://dart.dev/get-dart) 运行时后，可以通过执行 `make book` 命令生成静态页面，执行 `make serve` 进入开发模式。

```bash
make get
make
make book 
make serve
```

生成的译文静态页面位于 [site_zh](./site_zh/) 文件夹下，原始英文静态页面位于老的 [site](./site/) 文件夹下不受影响。

### 特别感谢

- 为了节省时间，前面十几章节后面可能考虑使用 [GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) 的译文，这里特别感谢该译者的付出。
- 由于涉及到静态页面，同时需要对 HTML 页面上某些跳转条目同步做中文翻译，呼吁大家一起参与到翻译工作中。