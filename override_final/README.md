#说明
跟java中这两个关键字的意思是一样的，一个用来表示覆盖基类中的同名虚函数，另一个表示这个函数不能被子类覆盖。

显示覆盖的好处是防止在子类中因为函数参数声明与基类中不匹配，导致不是覆盖，而是定义了一个新的函数，这样就失去了虚函数本来的作用。

而final则是定义防止在派生类中重新定义同样的函数。

在派生类中，只有可以正确的覆盖掉基类中的虚数时，override才可以通过编译。
在基类中，只有虚函数才可以声明为final。


可以把某个类声明为final来阻止继承。

