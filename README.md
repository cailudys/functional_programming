# 函数式编程是什么？

函数式编程，是一种编程范式。也就是思维模式 加上它的实现方法。 （我们另一种常见的编程范式：是面向对象编程）

函数是编程的实现方法：就是用一个函数来映射 事物之间的联系。（我们我们只关注入参 和返回值 ，中间的过程都抽象到函数中了。）

# 函数是一等公民，指什么意思？

> 很多时候，简单的东西，用复杂的，难以理解的词汇讲出来，就让人搞不明白甚至产生误解。

函数是一等公民，就是这样的一种描述。其实其实质只是想联系现实形象的表达，函数的权限高，限制小。可以去到任何的地方。在JavaScript中表现为可以 作为普通对象，还可以作为函数的参数和返回值。

# 高阶函数是什么？

高阶函数是指，是指`可以函数当成参数传递给函数`或者`函数的返回值也是一个函数` 的函数。

###### 使用高阶函数的意义：

1. 可以帮助我们屏蔽细节，只需要关注我们的目标
2. 用来抽象出通用的逻辑。
