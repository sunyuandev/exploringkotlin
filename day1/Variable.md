# Variable 变量
```
All programs need to be able to store data,and variables help you to do just that.
In Kotlin, you can declare:

所有的程序都需要存储数据，变量可以帮你做到这一点。在 Kotlin 中，你可以声明：
```
- Read-only variables with val
- 用 val 声明只读变量，也就是常量
- Mutable variables with var
- 用 var 声明可变变量
```
You can't change a read-only variable once you have given it a value.

一旦给常量赋值后，就不能再改变它。
```
To assign a value,use the assignment operator =.
使用赋值运算符 = 给变量赋值。
```kotlin
fun main() {
    val popcorn=5 //There are 5 boxes of popcorn
    val hotDog=7 // There are 7 hotDogs
    var customer =10 //There are 10 customers
    
    //some customer leave the queue
    customer =8
    println(customer)
    //8
}
```
```
Variables can be declared outside the main() function at the beginning of your program. 
Variables declared in this way are said to be declared at top level.

变量可以在 main() 函数外部声明，在程序开始处。声明这些变量的变量被称为顶级变量。

As customer is a mutable variable,its value can be reassigned after declaration.

customer 是可变的变量，它的值可以在声明后重新赋值。

We recommend that you declare all variables as read-only variables with val by default.
Declare mutable variables with var only if necessary.

我们建议默认声明所有变量为只读变量 val。如果需要可变变量，请使用 var。
```