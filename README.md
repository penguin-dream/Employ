# Employ

1.依赖（Dependency）关系
       依赖关系是一种使用关系，它是对象之间耦合度最弱的一种关联方式。
       在代码中，某个类的方法通过局部变量、方法的参数或者对静态方法的调用来访问另一个类（被依赖类）中的某些方法来完成一些职责。


       
![image](https://github.com/penguin-dream/Employ/assets/97454173/f7701fb8-cdd0-46af-91c2-2c67ce7dba4a)




2.关联（Association）关系
       关联关系是对象之间的一种引用关系，用于表示一类对象与另一类对象之间的联系，如老师和学生、师傅和徒弟、丈夫和妻子等。关联关系分为一般关联关系、聚合关系和组合关系，我们先介绍一般关联。
       关联可以是双向的，也可以是单向的。

       
![image](https://github.com/penguin-dream/Employ/assets/97454173/8b398ed6-b582-4355-9799-fee4f56d2cfc)


3.聚合（Aggregation）关系
      聚合关系是强关联关系，是整体和部分之间的关系，是has-a的关系。聚合关系也是通过成员对象来实现的，其中成员对象是整体对象的一部分，但是成员对象可以脱离整体对象而独立存在。
      例如，学校与老师的关系，学校包含老师，但如果学校停办了，老师依然存在。

      
![image](https://github.com/penguin-dream/Employ/assets/97454173/f03316d5-ab88-4de2-be3f-2a54e9354638)



4.组合（Composition）关系
       组合关系也表示类之间的整体与部分的关系，但它是一种更强烈的聚合关系，是contains-a关系。
       整体对象可以控制部分对象的生命周期，一旦整体对象不存在，部分对象也将不存在，部分对象不能脱离整体对象而存在。
       例如，头和嘴的关系，没有了头，嘴也就不存在了。

       
![image](https://github.com/penguin-dream/Employ/assets/97454173/6f547a0c-464c-4dfb-beb9-eab76bbd6993)


5.泛化（Generalization）关系
       泛化关系是对象之间耦合度最大的一种关系，表示一般与特殊的关系,是父类与子类之间的关系，是一种继承关系, 是is-a的关系。

       
![image](https://github.com/penguin-dream/Employ/assets/97454173/54637a97-f010-47c1-af22-575b72948bf1)


6.实现（Realization）关系
       实现关系是接口与实现类之间的关系。
       在UML类图中，实现关系使用带空心三角箭头的虚线来表示，箭头从实现类指向接口。例如，汽车和船实现了交通工具，其类图如下：

       
![image](https://github.com/penguin-dream/Employ/assets/97454173/d9ac36b7-4eae-4d27-9e62-d5948e1049d5)



