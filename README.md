# OS
THU Junior_down OS class


# 第3次课后练习

## 第一题

在你选择的开发和运行环境下，写一个函数`print_stackframe()`，用于获取当前位置的函数调用栈信息。实现获取以下**一种或多种**信息的功能：函数入口地址、函数名、参数调用参数、返回值。

可能的环境选择：

- 操作系统环境：Linux、uCore、rCore、MacOS、Windows...
- 特权级：用户态、内核态
- 编程语言：Rust、C、...

已有参考：

- [在uCore中写一个函数print_stackframe()](https://piazza.com/class/i5j09fnsl7k5x0/post/1273)：这里有多种可以在uCore和rCore上可以工作的print_stackframe()实现；（如果无法访问piazza，尝试先访问[这个链接](https://piazza.com/demo_login?nid=i5j09fnsl7k5x0&auth=b2410d0)）（**备注**：有些信息可能比较过时，请注意甄别）
- [获取内核堆栈回溯信息的实用程序](https://github.com/os-module/tracer)：北京理工大学陈林峰同学给出比较完善的Rust语言的函数调用栈回溯工具。
