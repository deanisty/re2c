# re2c

官网地址：http://re2c.org/

简介：
---------------------------------------------------------
re2c is a free and open-source lexer generator for C and C++. Its main goal is generating fast lexers: at least as fast as their reasonably optimized hand-coded counterparts. Instead of using traditional table-driven approach, re2c encodes the generated finite state automata directly in the form of conditional jumps and comparisons. The resulting programs are faster and often smaller than their table-driven analogues, and they are much easier to debug and understand. re2c applies quite a few optimizations in order to speed up and compress the generated code. Another distinctive feature is its flexible interface: instead of assuming a fixed program template, re2c lets the programmer write most of the interface code and adapt the generated lexer to any particular environment.

（从字面上理解：re2c就是regular expression to C/C++代码，将正则表达式转成C/C++代码）
re2c是一个免费开源的C/C++词法分析器的生成器。它的主要目标就是生成快速的词法分析器：至少会和特意优化过的手写的词法分析器一样快。re2c并没有使用传统的表格驱动的方法，取而代之的是直接将有限状态机编码为有条件的跳转和比较表达式的形式。产生的代码更加有效率而且通常会比表格驱动的代码体积更小，并且可以更加容易的调试和理解。re2c采取了少量的优化手段为了加速执行和压缩产生的代码。另外一个与众不同的地方就是它灵活的接口：re2c允许程序员编写大部分接口代码，它负责使生成的词法分析器适应任何特殊的环境，而并非只是提供一个固定的变成模板。

-----------------------------------------------------------

-----------------------------------------------------------
-----------------------------------------------------------
-----------------------------------------------------------
-----------------------------------------------------------
