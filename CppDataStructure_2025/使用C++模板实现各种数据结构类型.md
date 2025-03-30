
# 使用C++及模板技术实现各种数据结构类型
GitHub仓库地址：https://github.com/mshylf/CppDataStructure_2025

国内镜像仓库地址：https://gitcode.com/2404_89567743/CppDataStructure_2025

本项目使用visual studio 2022创建C++项目实现各种数据结构类型，为个人学习记录使用，若发现错误烦请及时指正。

## 已更新：
点击以下对应链接查看具体实现说明文档
- [顺序表](https://blog.csdn.net/2404_89567743/article/details/145797077?fromshare=blogdetail&sharetype=blogdetail&sharerId=145797077&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [单链表](https://blog.csdn.net/2404_89567743/article/details/145796670?fromshare=blogdetail&sharetype=blogdetail&sharerId=145796670&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [双链表](https://blog.csdn.net/2404_89567743/article/details/145796901?fromshare=blogdetail&sharetype=blogdetail&sharerId=145796901&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [顺序栈](https://blog.csdn.net/2404_89567743/article/details/145797210?fromshare=blogdetail&sharetype=blogdetail&sharerId=145797210&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [链栈](https://blog.csdn.net/2404_89567743/article/details/145797150?fromshare=blogdetail&sharetype=blogdetail&sharerId=145797150&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [循环队列](https://blog.csdn.net/2404_89567743/article/details/145797356?fromshare=blogdetail&sharetype=blogdetail&sharerId=145797356&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [栈括号匹配](https://blog.csdn.net/2404_89567743/article/details/145892088?fromshare=blogdetail&sharetype=blogdetail&sharerId=145892088&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)
- [表达式求值](https://blog.csdn.net/2404_89567743/article/details/146078235?fromshare=blogdetail&sharetype=blogdetail&sharerId=146078235&sharerefer=PC&sharesource=2404_89567743&sharefrom=from_link)

## 文件结构及功能描述

```plaintext
CppDataStructure_2025
├── main.cpp
├── .gitattributes
├── .gitignore
├── CppDataStructure_2025.sln
├── CppDataStructure_2025.vcxproj
├── CppDataStructure_2025.vcxproj.filters
├── src
│   ├── LinkList
│   │   ├── LinkList.hpp
│   │   └── doubleLinkList.hpp
│   ├── SqList
│   │   └── SqList.hpp
│   ├── test
│   │   ├── test.h
│   │   └── test.cpp
│   ├── stack
│   │   ├── stack.hpp
│   │   ├── LStack.hpp
│   │   ├── bracketCheck.h
│   │   ├── bracketCheck.cpp
│   │   ├── evaluateExpression.h
│   │   └── evaluateExpression.cpp
│   ├── Queue
│       └── CQueue.hpp
```

| 文件 | 功能描述 |
|:-:|:-:|
| main.cpp | 主函数 |
| .gitattributes | .gitattributes允许指定由 git 使用的文件和路径的属性 |
| .gitignore | 在git中忽略文件和文件夹 |
| CppDataStructure_2025.sln | 解决方案文件 |
| CppDataStructure_2025.vcxproj | 项目文件，记录项目相关的属性配置 |
| CppDataStructure_2025.vcxproj.filters | 项目文件过滤器 |
|src|代码实现文件夹|

|src文件子目录|文件名|功能描述|
|:-:|:-:|:-:|
|LinkList|LinkList.hpp|单链表实现|
||doubleLinkList.hpp|双链表实现|
|SqList|SqList.hpp|顺序表实现|
|test|test.h|测试文件头文件|
||test.cpp|测试文件实现代码|
|stack|stack.hpp|顺序栈实现|
||LStack.hpp|链栈实现|
||bracketCheck.h|括号匹配头文件|
||bracketCheck.cpp|括号匹配实现|
||evaluateExpression.h|表达式求值头文件|
||evaluateExpression.cpp|表达式求值实现|
|Queue|CQueue.hpp|循环队列实现|
