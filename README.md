# The C Programming Language Statements In Detail
再谈C语言中的语句

<br />

在《C语言编程魔法书》中的14章第6节已经详细讨论了C语言的六种语句：标签语句（label statement）、复合语句（compound statement）、表达式语句（expression statement）、选择语句（selection statement）、迭代语句（iteration statement）以及跳转语句（jump statement）。这里，我将对其中的表达式语句中的一种特殊形式的语句再做讨论——即**空语句**（**null statement**）。空语句在《C语言编程魔法书》中没怎么提到，这里正好做个补充。

空语句属于一种特殊的表达式语句，其表达式完全为空，即就一个分号（ **;** ）所构成的一条表达式语句。这里我们需要注意，别把void表达式语句、空语句、空复合语句搞混了，以下先展示这三种不同的语句概念：

```c
(void)0;    // 这是一条void表达式语句

;           // 这是一条空语句

{ }         // 这是一条空的复合语句
```

