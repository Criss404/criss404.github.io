# 我的unity学习笔记01
#### unity浮点精度问题
(1)unity的transform貌似是用float存储的，今天在设置2D人物移动时，无论是int，还是double，在unity中都会显示报错。
#### 创建初始脚本时的两个方法
(2)**start()** 方法在unity脚本中指的是游戏开始之前将调用它；**Update()** 方法在unity脚本中指的是游戏开始中每一帧将更新数据。
#### unity中public和private
(3)unity中public和private是有区别的。在设置2D人物移动时，如果定义一个变量为private，那么该变量在unity中将会无法运行，报错。只有public才能正常运行。public 变量 一经修改会保存值，相当于static 变量，在editor 模式下每次run之后变量会记住editor下设置的值,private 每次run 变量都会初始化，如果是float类型，默认初始值为0。

