封装 回顾总结 + 笔记  
内容：
什么是封装？ encapsulation 把抽象出来的数据和对数据的操作抽象出来，数据被绑定在一起
电视机的按钮 开机，音量等等 只对用户暴露接口  
1. 隐藏实现的细节
2. 可以对数据进行验证，保证安全和合理性  

封装实现的步骤:
1. 属性进行私有化 构造方法，变量private
2. 提供一个setter和getter方法，修饰符为公共的  

快速入门：
Encapsulation.Java

课堂练习：
com.hspedu.encap:AccountTest.java 和 Account.java  
创建程序，在其中定义两个类,体会Java的封装性。 
1. Account 类要求具有属性：姓名（长度为2位3位或者4位），余额（必须>20），密码（必须是六位），如果不满足，则给出提示信息，并且给默认值
2. 通过setXxx的方法给Account的属性赋值。
3. 在AccountTest中测试  

###继承
为什么需要继承？ Java面向对象-组合与继承  
do not repeat yourself  事不过三，三则重构  
单根继承 隐式的继承了Object 保证这个对象中的所有继承的对象都有同一种行为 一个类只能继承一个类 对比多根继承 
equals 和 == 的区别  
子类和父类在内存中
