# pet  
# This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.         For more information, please check Tuya Developer Website.
## 一、 宠物自动喂食器
#### 系统组成
* 基座外壳、下料桶、食物盘、压力传感器、密封圈、温湿度传感器、无刷直流电机、显示控制板、警告灯、电路控制系统以及电源开关

#### 系统功能：
* 实现基于涂鸦云的宠物自动喂食器，具备定时喂食功能、投喂食物重量检测功能、数据上云功能及通过APP控制功能。
* 基于stm32开发板结合涂鸦的sdk开发，包括状态指示灯（LED灯）显示、温湿度传感器、红外传感器、OLED显示屏、WIFI串口通信模块、小电机控制等功能实现。
* 通过语音控制单元，识别不同固定语句，来控制开发板模块。
* 通过WIFI串口通信模块，实现数据与涂鸦云平台的通信，实现对喂食仓余量，温湿度等状态的上传。
* 通过涂鸦APP实现简易的宠物喂食提醒器状态监控，及喂食等控制功能。当食物桶内余量不足10%时通过app告警。
* 出仓口采用温湿度传感器模块检测粮食的环境状态，结合电机风扇对暴露在空气下的粮食进行吹干处理，预防粮食的发霉潮湿。
* 加入语音模块提升智能化,主人可通过指定的命令对小夜灯、风扇、控制粮食进出的电机的联动开关。


## 二、方案应用
#### 场景地点：
*  家中任何地方，或是宠物的小窝改造。
 
## 三、开发计划
* 3月31前完成.
* 1）3月8日前熟悉资料，申请相关账号并熟悉平台。
* 2）3月9-20日跟着视频教程学习嵌入式开发、MCUSDK移植及云开发
* 3）3月21-31日整体调试，有必要的条件下自制PCB扩展板，并提交结果。
