# singleton
### 目的
保证一个类仅有一个实例，并提供一个访问它的全局访问点，该实例被所有程序模块共享

### 适用时机
一个类只需要一个实例

### 注意事项
注意线程安全

### 优缺点
- 提供了对唯一实例的受控访问，确保所有的对象都访问同一个实例
- 减少系统的性能开销
- 单例模式没有抽象层，所以扩展困难

# application
- 文件系统
- 配置文件对象