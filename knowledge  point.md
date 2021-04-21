# 1. _attribute_机制
    以设置函数属性（Function Attribute）、变量属性（Variable Attribute）和类型属性（Type Attribute）
    attribute 语法格式为: attribute ((attribute-list))
    当__attribute__ 用于修饰对象时，它就如同C 语言语法体系结构的类型限定符，跟const , volatile , restrict 等属一类。
    当__attribute__ 用于修饰函数时，它就相当于一个函数说明符，跟inline，Noreturn 属同一类。
    当__attribute_ 用于修饰一个结构体，联合体或者枚举类型，该限定符只能放在类型标识符之前。
    示例：extern void exit(int)   __attribute__((noreturn));
# 2. 编写makefile文件中临时将tab不转换为空格
    先按CTRL+V组合键，然后再按tab键
# 3. C语言中的NULL是怎么定义的
    其宏定义为#define NULL ((void*)0)
# 4. vim中的代码补全功能
    在插入模式下按组合键ctrl-p和组合键ctrl-n.
# 5. 函数指针和指针函数的区别
    函数指针指向函数；
        函数指针和它指向函数的参数个数和类型应该是一致的，指针类型和函数的返回类型一致；
        原型为：type(*函数名)(形参列表); 
        调用形式为 (*函数名)(函数参数);
    指针函数是指函数的返回类型是指针类型;
        原型为：type *函数名(形参列表);

