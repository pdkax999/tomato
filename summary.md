***

1. `qos-1`ts导入类型模块，始终没有导入过来，s导入模块总是**报错**
2. `qos-3`如果有未定义的模块，如何定义类型
3. `qos-5` 关于从外部模块**导入类型**，然后在prop上使用为啥没有生效(昨天做了点操作生效了),将模板放在了前面
4. `qos-4`ts未定义模块总是报错，结果吧`script ts`放在顶部就没有这个问题!,`ts`如何在项目中使用
5. `qos-2`watch检测`props`始终没有生效的问题!（使用这个成功**执行**）
6. `qos-6` ts如何在Vue3中如何使用，

![image-20240901124528391](C:\Users\Promise\AppData\Roaming\Typora\typora-user-images\image-20240901124528391.png)

1. `kle-1``$attr`vue3中的`$attr`居然和`$listener`合并在一起了。 **有意思**
2. `kle-2`直接通过`{}`去解耦包裹
3. `kle-3`ref给reactive使用相互影响，不方便管理数据流
4. `rth-s-1`分布安排好任务，不然时间失控花费的。按步骤执行



### 新版的优点

1. 数据相较前一个版本好管理一些，数据始终保存在父组件，不存在说要把子组件的数据映射到父组件
2. 需求重新梳理下，大于截止时间直接使用**截止时间**(方便)  不用做乱七八糟的判断了哈哈
3. v-model语法糖替代自定义事件组合。

   

### 执行任务

为什么花费这么久

![image-20240901130017547](C:\Users\Promise\AppData\Roaming\Typora\typora-user-images\image-20240901130017547.png)

> 遇到的问题做一个知识分类，处理下
>
> 1. 遇到问题耽搁了(有时候可以先记录暂时不处理)，
> 2. 前面两个番茄熟悉了一下业务功能(不过感觉不`全面`)，看了一下头部编写的源码(没有那种分步执行的感觉，就想代码没有模块化一样，一团**散沙**), 没有抓住核心抓住核心之后很**简单**
> 3. `rth-s-1`别人当时怎么去写的，就怎么去读代码，不要没有条理读代码，注意下自己编写的hooks, 
> 4. 分布安排好任务，不然时间失控花费的。按步骤执行