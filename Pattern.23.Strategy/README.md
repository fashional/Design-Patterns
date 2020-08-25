# 策略模式

策略模式（Strategy Pattern），一个类的行为或者其算法可以在运行时改变，属于行为模式

## 优点

1. 算法可以自由切换
2. 避免出现多重条件判断
3. 拓展性好

## 缺点

1. 策略类增多
2. 所有策略类都要对外暴露

## 注意

> 如果一个系统策略超过四个，则需要使用混合其他模式，解决类膨胀的问题