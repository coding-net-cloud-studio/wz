[原文地址](https://mp.weixin.qq.com/s/yCzIiZ2f50GI5VuDW_geAg)

项目地址：https://github.com/trekhleb/learn-python

# Learn-python:一个学习和使用Python的脚本集合,从入门到精通,代码示例,速查表,最佳实践一网打尽

**原创** **小白这样学Python** [小白这样学Python](javascript:void(0);) *2024年11月12日 00:02* *湖南*

> 还在为学习Python而苦恼吗?这个项目将带你轻松入门,并逐步掌握Python的精髓!`learn-python` 不仅是一个代码示例库,更是一个交互式的学习平台,让你在实践中快速提升编程技能.

![图片](attachments/640%5B31%5D.webp)

**项目简介**

`learn-python` 是一个按主题分类的 Python 脚本集合,包含丰富的代码示例,详细的解释,不同的用例以及扩展阅读链接.它既是一个"游乐场",又是一个"速查表",助你轻松玩转 Python.

**为什么称之为"游乐场"?**

你可以修改或添加代码,实时查看运行结果,并使用断言进行测试.你还可以使用代码检查工具,确保代码符合 Python 代码风格指南.这种交互式学习方式,可以让你更深入地理解代码,并从一开始就养成良好的编码习惯.

![图片](attachments/640%5B32%5D.webp)

**为什么称之为"速查表"?**

当你需要回顾 Python 语法或标准库用法时,可以随时查阅这些代码示例.由于代码中包含了大量的断言,你可以直接看到函数/语句的预期输出,无需运行代码.

![图片](attachments/640%5B33%5D.webp)

**如何使用这个宝库?**

每个 Python 脚本都遵循以下结构:

```
"""列表  <--- 主题名称

# @see: https://www.learnpython.org/en/Lists  <-- 扩展阅读链接

这里可能会有对当前主题的更详细的解释(例如,关于列表的一般信息).
"""


deftest_list_type():
"""子主题的解释在这里.

    每个文件都包含测试函数,用于说明子主题(例如,列表类型,列表方法).
    """

# 这是一个如何构建列表的示例.  <-- 注释解释了操作
    squares =[1,4,9,16,25]

# 列表可以被索引和切片.
# 索引返回项.
assert squares[0]==1# <-- 断言在这里说明了结果.
# 切片返回一个新列表.
assert squares[-3:]==[9,16,25]  # <-- 断言在这里说明了结果.
```

通常,你可以按照以下步骤学习:

1. 1. 找到你想要学习或回顾的主题.
2. 2. 阅读每个脚本文档字符串中的注释和/或链接的文档(如上例所示).
3. 3. 查看代码示例和断言,了解用法示例和预期输出.
4. 4. 更改代码或添加新的断言,看看它们是如何工作的.
5. 5. 运行测试和代码检查,确保代码正常工作并符合规范.

**涵盖的主题**

* •  **入门** :Python 简介,语法,变量,运算符
* •  **数据类型** :数字(包括布尔值),字符串,列表,元组,集合,字典,类型转换
* •  **控制流** :if 语句,for 语句,while 语句,try 语句,break 语句,continue 语句
* •  **函数** :函数定义,变量作用域,默认参数值,关键字参数,可变参数列表,参数解包,lambda 表达式,文档字符串,函数注解,函数装饰器
* •  **类** :类定义,类对象,实例对象,方法对象,类变量和实例变量,继承,多重继承
* •  **模块** :模块导入,包
* •  **错误和异常** :异常处理,引发异常
* •  **文件** :读写文件,文件对象的方法
* •  **附加内容** :pass 语句,生成器,标准库简介(序列化,文件通配符,字符串模式匹配,数学,日期和时间,数据压缩),用户输入

**如何运行代码**

**前提条件:** 安装 Python 3,推荐使用 `venv` 创建虚拟环境.

**安装依赖项:** `pip install -r requirements.txt`

**运行测试:** `pytest` 或 `pytest ./path/to/the/test_file.py` (运行特定测试)

**代码检查:** `pylint ./src/`

**总结**

这个项目提供了一个系统学习 Python 的绝佳途径,无论你是初学者还是有一定经验的开发者,都能从中受益匪浅.赶紧来体验吧!

**项目地址:https://github.com/trekhleb/learn-python**
