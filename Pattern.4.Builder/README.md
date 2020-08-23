# 建造者模式

建造者模式（Builder Pattern）将复杂对象的创建过程，改为简单对象的多个步骤来实现。如Java中的StringBuilder。Builder是一步步最终构造目标对象，独立于其他对象。

## 优点

1. 独立的建造者，容易拓展
2. 细节把控

## 缺点

1. 需要目标类具有共性
2. 需要生成的对象内部本身相互依赖

## 注意事项

> 与工厂模式最大的区别在于，建造者模式关注的创建对象，属性之间有关联的顺序