###对象转类：
object.constructor

###原型对象转类：
prototype.constructor

###类转对象：
new Object()

###类转原型对象
Objct.prototype

###对象转原型对象
object.__proto__

###原型对象转指向的原型对象
prototype.__proto__（如果没有继承，则默认继承自Object原型对象）

###内部获得类：
arguments.callee

###内部获得对象：
this

###内部获得参数：
arguments

###内部获得调用类：
arguments.callee.caller