# 0、OOP-Python面向对象
-  Python的面向对象
- 面向对象编程
    - 基础
    - 公有私有
    - 继承
    - 组合、Minxi
- 魔法函数
    - 魔法函数概述
    - 构造类魔法函数
    - 运算类魔法函数
 
 # 1、面向对象(object-oriented)概述
 - OOP思想
    - 面向对象的编程的主要思想是把构成问题的各个事物分解成各个对象，建立对象的目的不是为了完成一个步骤，而是为了描述一个事物在解决问题的过程中经历的步骤和行为。
    对象作为程序的基本单位，将程序和数据封装其中，以提高程序的重用性，灵活性和可扩展性。类是创建对象的模板，一个类可以创建多个对象。对象是类的实例化。
    类是 抽象的，不占用存储空间；而对象具体的，占用存储空间。
 
 - 几个名词：
    - OO: 面向对象
    - OOA: 面向对象的分析
    - OOD: 面向对象的设计
    - OOI: 面向对象的实现
    - OOP: 面向对象的编程
    - OOA -> OOD -> OOP: 面向对象的实现过程
 - 面向对象有三大特性：封装，继承，多态。
 
- 类和对象的概念
    - 类：抽象名词，代表一个集合、共性的事物
    - 对象： 具象的事物，单个个体
    - 类和对象的关系
        - 一个是具象，代表一类事物的某一个个体
        - 一个是抽象，代表的是一大类事物
- 类中的内容，应该包含两个内容
    - 表明事物的特征，叫做属性（变量）
    - 表明事物的功能或动作，叫做成员方法（函数）

# 2、类的基本实现
- 类的命名
    - 遵守变量命名的规范
    - 大驼峰（由一个或者多个单词构成，每个单词首字母大写，单词与单词直接相连）
    - 尽量避免跟系统命名相似的命名
    
- 如何声明一个类
    - 必须用class关键字
    - 类由属性和方法构成，其他不允许出现
    - 成员属性定义可以直接使用变量赋值，如果没有值，需使用None
        - 案例：01.py
    
       
 