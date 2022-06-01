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
# alias as `dart build/build.dart.snapshot --serve`
```

生成的译文静态页面位于 [site_zh](./site_zh/) 文件夹下，原始英文静态页面位于老的 [site](./site/) 文件夹下不受影响。

### 翻译进度

| 章节序号 | 英文章节名 | 中文章节名 | 完成情况 |
| ---- | ----- | ------- | ------- |
| F. | Frontmatter | 前言 | - |
|  ┣F1. | [Dedication](https://craftinginterpreters.com/dedication.html) | [献辞](https://craftinginterpreters-zh.vercel.app/dedication.html) | ✅ |
|  ┗F2. | [Acknowledgements](https://craftinginterpreters.com/acknowledgements.html) | [致谢](https://craftinginterpreters-zh.vercel.app/acknowledgements.html) | ✅ |
| I. | [Welcome](https://craftinginterpreters.com/welcome.html) | [欢迎](https://craftinginterpreters-zh.vercel.app/welcome.html) | ✅ |
|  ┣1. | Introduction | 入门指导 | [ ] |
|  ┣2. | A Map of the Territory | 领地地图 | [ ] |
|  ┗3. | The Lox Language | Lox 语言 | [ ] |
| II. | A Tree-Walk Interpreter | 一个遍历树解释器 | [ ] |
|  ┣4. | Scanning | 扫描 | [ ] |
|  ┣5. | Representing Code | 代表性代码 | [ ] |
|  ┣6. | Parsing Expressions | 解析表达式  | [ ] |
|  ┣7. | Evaluating Expressions | 求值表达式 | [ ] |
|  ┣8. | Statements and State | 申明与状态 | [ ] |
|  ┣9. | Control Flow | 控制流程/条件语句 | [ ] |
|  ┣10. | Functions | 函数 | [ ] |
|  ┣11. | Resolving and Binding | 解析与绑定 | [ ] |
|  ┣12. | Classes | 类 | [ ] |
|  ┗13. | Inheritance | 继承 | [ ] |
|  III. | A Bytecode Virtual Machine | 一个字节码虚拟机 | [ ] |
|  ┣14. | Chunks of Bytecode | 字节码块 | [ ] |
|  ┣15. | A Virtual Machine | 虚拟机 | [ ] |
|  ┣16. | Scanning on Demand | 按需扫描 | [ ] |
|  ┣17. | Compiling Expressions | 编译表达式 | [ ] |
|  ┣18. | Types of Values | 数值类型 | [ ] |
|  ┣19. | Strings | 字符串 | [ ] |
|  ┣20. | Hash Tables | 哈希表 | [ ] |
|  ┣21. | Global Variables | 全局变量 | [ ] |
|  ┣22. | Local Variables | 局部变量 | [ ] |
|  ┣23. | Jumping Back and Forth | 来回跳跃 | [ ] |
|  ┣24. | Calls and Functions | 调用与函数 | [ ] |
|  ┣25. | Closures | 闭包 | [ ] |
|  ┣26. | Garbage Collection | 垃圾回收机制 | [ ] |
|  ┣27. | Classes and Instances | 类与实例 | [ ] |
|  ┣28. | Methods and Initializers | 方法与初始化函数 | [ ] |
|  ┣29. | Superclasses | 超类 | [ ] |
|  ┗30. | Optimization | 优化 | [ ] |
| B. | Backmatter | 后记 | [ ] |
|  ┣A1. | Appendix I | 附录 I | [ ] |
|  ┗A2. | Appendix II | 附录 II | [ ] |

### 特别感谢

- 为了节省时间，前面十几章节后面可能考虑使用 [GuoYaxiang/craftinginterpreters_zh](https://github.com/GuoYaxiang/craftinginterpreters_zh) 的译文，这里特别感谢该译者的付出。
- 由于涉及到静态页面，同时需要对 HTML 页面上某些跳转条目同步做中文翻译，呼吁大家一起参与到翻译工作中。