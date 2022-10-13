# 前端面试总结

js html css
# js

## 面向对象
对象的定义: 无序属性的集合，其属性可以包含基本值，对象或者函数

代码示例：
var person={
    name:"test",
    getName:function(){

    },
    son:{},
    parent:{}
}
创建对象 var obj=new Object() 
对象字面量的形式  var obj={}

var person={
    name:"test",
    age:"12"
    getName:function(){
        return this.name
    },
    getAge:function(){
        return this.age
    }
}
访问对象属性和方法
person.name
person['name']

## 构造函数
关于构造函数，理解new具体发生了什么
new构造函数与普通函数的不同，new的过程
1:声明一个中间对象
2:将该中间对象的原型指向构造函数的原型
3：将构造函数的this，指向该中间对象
4:返回该中间对象，即返回实例对象
## 原型
我们创建的每个函数，都有个prototype属性，该属性指向一个对象。这个对象就是我们这里说的原型。

## 原型链 继承
构造函数继承
原型继承

## this
指向，是在函数被调用的时候确定的，也就是执行上下文被创建时确定的。
1.全局对象中的this
2.函数中的this
3.使用call，apply显示制定this

## 事件循环(event loop)

## 执行上下文

## 浏览器原理
浏览器是多进程架构
1：主进程 2：渲染进程(内核) 3：插件进程 4:GPU进程 5:网络进程

## http

## 缓存

## 跨域

## 输入url显示页面过程
1.
2.


# 框架(vue react)


# 数据结构和算法

## 栈：只能操作一端
## 队列：可以操作两端

# 设计模式：
1.工厂模式:解决创建对象有重复的属性和方法
直接上代码
var createPerson=function(name,age){
    var obj=new Object()

    obj.name=name
    obj.age=age
    obj.getName=function(){
        return this.name
    }
    return obj
}
 创建实例
 var jc=createPerson('js',10)



# 工程化

# git  

# 工程化 技术难点 团队协作


