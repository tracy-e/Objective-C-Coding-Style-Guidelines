#开发小贴士和技巧
##初始化
###类初始化
在 initialize 类方法中,能够编写实现一些延迟执行且只被一次的代码,initialize 类方法是由运行时系统在

+ (void)initialize {


if (self == [NSFoo class]) {
