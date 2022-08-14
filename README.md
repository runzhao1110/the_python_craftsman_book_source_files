# 《Python 工匠》源码合集

此处收录了《Python 工匠：案例、技巧与工程实践》一书中的所有 Python 源代码文件（不含部分过短的代码片段）。

> 更多信息请前往图书主页（图灵社区）：https://www.ituring.com.cn/book/3007

## 说明

每个子目录对应书中的一章，里面放着与本章内容相关的源码文件和数据文件（部分程序比如“日志分析脚本”需要）。目录名的前两位数字代表章数，比如 `07_function` 对应“第七章：函数”。

如何执行源码：

- 安装 Python 3.8 版本（更高的版本也行，但部分行为可能有差异）
- 执行源码文件：`python 01_variables/bubble_sort.py`
- 查看执行结果

### 小技巧：使用 -i 选项来执行程序

分享一个方便调试的小技巧。执行源码时，你可以使用 `python -i {FILE_NAME}` 选项进入交互模式。比如，执行以下命令：

```python
$ python -i 01_variables/bubble_sort.py
[1, 3, 19, 23, 2, 4, 4, 20, 32]
[1, 3, 19, 23, 2, 4, 4, 20, 32]

# 程序不会马上退出，而是会进入交互模式 
# 你可以调用源码中的函数或类，做些实验
>>> magic_bubble_sort([74, 28, 113, 3, 13])    
[3, 13, 113, 28, 74]
```

## 常见问题

### 为什么有的文件无法正常运行？

部分源码文件（比如 `01_variables/complex_variable.py`）在执行时，可能会抛出 `SyntaxError: 'return' outside function` 之类的异常。这是正常的，因为这些代码本身只是些零碎的小片段，仅用来描述某个概念或知识点，并非完整程序。

## 作者信息

作者：piglei \<piglei2007@gmail.com\>
主页：https://www.zlovezl.cn/
