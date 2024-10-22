# 如何解决S17错误

S17：单圈编码器错误

适用产品：xArm 系列, UF 850, Lite6

适用固件版本: V2.4.0+

适用studio版本：V2.4.0+

* [x] 如果你长时间没有使用这个机械臂（超过3个月），然后手臂报错S17，请按照下面的步骤操作清除错误
* [ ] 如果刚刚收到机械臂就报错S17，请截图错误弹窗并且联系我们

### 状态码=16

错误码：S17，关节ID：*（1~7），状态码：16

1-按下急停，然后松开

2-不要使能，进入设置-通用设置-调参工具-关节，发送 H101 D0104 V1 I\*，解锁关节\*，手动移动关节\*，轻微转动一点就可以，然后发送H101D0813V2I\*，按下急停。(这一步将会重置零点位置，所以在移动关节到初始点之前，请记住初始点位置)

3-松开急停，移动关节*到初始点位置，发送D13 I*\*，按下急停

4-松开急停，尝试再次使能机械臂


