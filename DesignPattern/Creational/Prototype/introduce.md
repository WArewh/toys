# prototype
### 目的
用原型实例指定创建对象的种类，并且通过拷贝这些原型创建新的对象

### 适用时机
创建大量相同或者相似的对象

### 优缺点
- 简化对象的创建，同时还提高了创建的速度
- 改变数值或者改变结构就可以创建出新对象
- 每一个Prototype的子类都必须实现clone，当内部包括一个不支持拷贝或者有循环引用的对象时，实现克隆可能也会困难

### 注意事项
- prototype一般和工厂方法一起使用

# application
Java的clone方法
