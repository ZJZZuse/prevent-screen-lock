# prevent-screen-lock(阻止锁屏小程序)

## background
域策略的电脑有时候会写死锁屏时间，而锁屏时间往往很短。有时候一不注意就锁屏了，需要*频繁解锁*。

而频繁解锁操作比较麻烦，也容易暴露密码。

## 原理
就是隔一段时间模拟按键操作，目前是模拟pause按键，每3分钟一次。

## usage

命令行打开jar包即可。

`java -jar ./prevent-screen-lock-1.0-SNAPSHOT-jar-with-dependencies.jar`

自己也可以根据实际需求修改。

## download
[release](https://gitee.com/zeeus/prevent-screen-lock/releases)
