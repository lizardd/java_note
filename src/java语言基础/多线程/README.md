+ 1、Runnable适合于多个相同程序代码线程去处理统一资源的情况，把虚拟的cpu（线程）同程序的代码，数据有效分离，较好体现面向对象的编程的思想

+ 2、Runnable可以避免由于Java的单继承机制带来的局限。可以再继承其他类的同时，还能实现多线程的功能。

+ 3、Runnable能增加程序的健壮性。代码能够被多个线程共享

+ 4、Runnable定义的子类中没有start()方法，只有Thread类中才有