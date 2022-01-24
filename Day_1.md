/**
 * Day 1
 * 面向对象
 * 对象：bject 具体的某个事物
 * 类：class 对具有相同或相似属性与行为特征的一类事物的描述
 */

// 类的命名：驼峰命名
public class Human {
    Spring name;
    int age;
    String sex;

    // 常用final修饰的变量 初始化之后不可以改变值
    final int iD;

    // 静态的，只属于类
    static String nationality = "China";

    // final static
    final static double weight = 65.0;

    //默认有构造方法，创建后覆盖默认构造方法，使用空参数需重载
    public Huamn(Spring n, int a, String s, int i) {
        this.name = n;
        this.age = a;
        this.sex = s;
        this.iD = i;
    }

    public Human() {

    }
}

/** 
* 代码中没有对象，对象在内存中。只有执行创建对象的代码的时候才会创建对象。
* 非运行状态：一些文件（代码 + 资源）
* 运行状态： 进程通过计算机指令调度计算机资源（CPU RAM IO）解决问题
* 写代码：预先写一套指令。
*/

/**
* Question:
* 如何创建“.md”文件
* fianl static 何时初始化，可否在构造方法里赋值？
*/

