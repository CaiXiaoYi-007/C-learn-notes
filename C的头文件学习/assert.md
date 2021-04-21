# 1. assert.h
    <assert.h> 头文件中只定义了一个用于断言的宏函数，就是 assert()。
    void assert (int expression);
    传入表达式，结果为“假”，会打印失败的信息，并终止程序；结果为“真”，则程序继续执行。
    应用举例：被除数不能为 0，可以加入了assert() 来检测错误。
