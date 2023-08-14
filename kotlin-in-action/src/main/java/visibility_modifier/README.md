
#### Kotlin和Java protected class 的区别

Java只能在同包名下可以继承 protected class
Java可以访问同包名下的 protected class

Kotlin就算同包名下也不能访问 protected class
Kotlin就算同包名下也不能继承 protected class

既然Kotlin不能访问和继承同包名下的 protected class，那么 protected class 不就和 private class 一样了吗？
在Kotlin中要是使用 protected class ，需要继承 protected class的外部类，然后我们就可以使用 它里面的 protected class了
如果外部类不能被继承，那里面的 protected class 和 private class 没有区别，在这种情况下，编译器也建议我们把 protected 改成 private





