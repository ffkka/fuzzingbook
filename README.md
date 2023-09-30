# fuzzingbook
[The Fuzzing Book](https://www.fuzzingbook.org/):一本用代码写出来的Fuzzing书籍
- 以Python代码为例，从易到难，整个学习过程循序渐进，讲解Fuzzing技术的方方面面，将理论融合在实际的操作中，学起来更有趣味性；
- 对于理解各种概念、技术原理比较有帮助，包括覆盖引导、变异策略、种子调度算法、语法Fuzzing、语义Fuzzing，符号Fuzzing等等；

>强烈想学习`fuzz`的同学深入学习这本书来进行入门，而不是一上来就是去分析`AFL`等比难的东西。    
>算是`翻译`加`笔记`的结合，希望可以帮到大家。

# 组织结构
原书分为6大部分：
1. [Whetting  Your Appetite](https://www.fuzzingbook.org/html/01_Intro.html)
2. [Lexical Fuzzing](https://www.fuzzingbook.org/html/02_Lexical_Fuzzing.html)
3. [Syntactical Fuzzing](https://www.fuzzingbook.org/html/03_Syntactical_Fuzzing.html)
4. [Semantical_Fuzzing](https://www.fuzzingbook.org/html/04_Semantical_Fuzzing.html)
5. [Domain Specific Fuzzing](https://www.fuzzingbook.org/html/05_Domain-Specific_Fuzzing.html)
6. [Managing Fuzzing](https://www.fuzzingbook.org/html/06_Managing_Fuzzing.html)

按照每一部分每一节的顺序存放笔记文件
- markdown文件加下存放md文件
- 还将md文件转换为pdf存放在pdf目录下


# 学习建议
1. 第1部分是对软件测试的一些介绍，没有任何难度。
2. 第2年部分则讲解了一些fuzzing中的常见技术，覆盖率引导，变异策略等等,难度也不是很大
3. 第3部分和第4部分则是语法语义fuzzing,这部分是最难的，涉及到编译原理领域的知识。需要先学习一波编译原理，推荐资料《编译原理》
4. 第5部分则是对特定领域的fuzzing进行介绍，如Api ，Gui等等
5. 最后则是对如果管理大型fuzzing进行介绍。
>最难的则是第3部分和第4部分。
