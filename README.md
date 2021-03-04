# java-interview

面试题整理

## 基础篇

### 1. Java基础知识

#### 1.1 谈谈对面向对象的理解
> 面向对象注重的是对象的概念，强调的是一种”万物皆对象的“编程思想。
> 当解决一个问题的时候，面向对象会把事物抽象成对象的概念，
> 就是说这个问题里面有哪些对象，然后给对象赋一些属性和方法，
> 然后让对象与对象之间相互协调，调用方法，解决问题。

#### 1.2 面向对象和面向过程的区别
> 面向过程：强调的是过程，是分析问题解决得步骤，然后通过实现方法，通过一系列得调用，最终解决问题。
> 性能较高，所以一些单片机、嵌入式的开发等一般采用面向过程开发。
> 面向对象：强调的是对象，会将构成问题的事物分解成各个对象，各司其职，协同调用解决问题。
> 面向对象具有封装、继承、多态的特性，所以易维护，易复用、易扩展。可以设计出低耦合的系统。
> 性能比面向过程低。

#### 1.3 普通类和抽象类的区别
> - 普通类可以实例化调用；抽象类不可以被直接实例化（通过子类继承实例化，父类引用指向子类对象）
> - 普通类不能有抽象方法

#### 1.4 接口和抽象类的区别
> - 实现: 类 extend ，接口 implement
> - 构造函数: 类可以有多个，接口 不可以有
> - 实现数量: 类单继承，接口多实现
> - 访问修饰符: 抽象类中都可以，接口中默认使用public


