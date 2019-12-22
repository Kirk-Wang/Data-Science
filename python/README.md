# Python 基础快速入门

### Pyton 能做什么？
* 网站开发
  - Django, Flask
* 科学计算，人工智能
  - Numpy, Scipy
  - TensorFlow
* 系统管理
* 网络开发
* 桌面应用开发
* 嵌入式（树莓派）
* 其它

### Pyton 有什么缺点？
* 运行有些慢（相对来说）

### 内容
* 基本的数据类型
* 列表和元组
* 字典和集合
* 条件语句和循环语句
* 函数
* 面向对象基础
* 模块和包
* 输入输出和文件
* 函数式编程
* 调试和测试

### 整数
* 定义 a = 125
* Python 可以处理 “任意” 大小的整数，包括负数。
* 支持二进制，八进制，十进制，十六进制

前缀|例子|进制
-|-|-
0b或者0B|a=0b1010|2
0o或者0O|a=0b12|8
无|a=10|10
0x或者0X|a=0xa|16

### 浮点数
* 定义
  - a = 1.2
  - b = .4
  - c = 1.2e-4
* 计算时可能会丢失精度 [15. Floating Point Arithmetic: Issues and Limitations](https://docs.python.org/3.6/tutorial/floatingpoint.html)
```sh
pyton3
>>> 1/3
0.3333333333333333
>>> a = 1
>>> type(a)
<class 'int'>
>>> a = 1.2
>>> type(a)
<class 'float'>
>>> a = .4
>>> a
0.4
>>> a = 1.2e-4
>>> a
0.00012
>>> 1/3
0.3333333333333333
>>> a = 1/3
>>> type(a)
<class 'float'>
>>> 1+3
4
>>> a = 1
>>> b = 3
>>> c = a + b
>>> c
4
>>> 2 * 4
8
>>> 2 * -4
-8
>>> 2 / 4
0.5
>>> 8 / 3
2.6666666666666665
>>> 4 / 2
2.0
>>> 2 // 4
0
>>> a = 4 / 2
>>> type(a)
<class 'float'>
>>> b = 4 // 2
>>> type(b)
<class 'int'>
>>> c = 8 // 3
>>> c
2
>>> a = 0.2/0.4
>>> a
0.5
>>> a = 0.2 // 0.4
>>> a
0.0
```

### 字符串
* 定义
  - a = 'test'
  - a = "test"
  - a = "中文"
  - a = '''在一个字符串里包含一个双引号(")和一个单引号(')'''
```sh
>>> a = "test"
>>> a[0
... ]
't'
>>> a[4]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
IndexError: string index out of range
>>> a[-4]
't'
>>> a[-1]
't'
>>> a[-2]
's'
>>> a[-3]
'e'
>>> b = 'xx'
>>> c = a + b
>>> c
'testxx'
>>> c * 3
'testxxtestxxtestxx'
```

### 字符串格式化