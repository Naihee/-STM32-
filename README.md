# 基于stm32的麦克纳姆轮地盘

1.0 板子主要问题
（1）电路原理图设计缺陷（12V电源未接通）
（2）降压电路电感对应pcb元件选择错误
（3）STM32核心板针脚间隙过打误差大小100mil


已经修正问题：
（1）电路原理图设计缺陷（12V电源未接通）
（2）降压电路电感对应pcb元件选择错误
（3）STM32核心板针脚间隙过打误差大小100mil


2.0板子已经打样测试，现有问题
（1）电路adc检查电压引脚PA5没有接入主电源

Altium Designer 版本为2020

![image](https://user-images.githubusercontent.com/72441782/176927777-31943cf9-811e-4ad3-b7a6-59fb79f3893a.png)
![image](https://user-images.githubusercontent.com/72441782/176927823-2eda38ec-80f1-432d-b95d-2220dbd04ad0.png)
![image](https://user-images.githubusercontent.com/72441782/176927888-31378ba3-7324-436b-93e4-6619a10bd894.png)
![image](https://user-images.githubusercontent.com/72441782/176927902-4282fcbf-1554-4f05-8048-d14246f6aa0f.png)
