LCD 接线
---
> LCD 用的是 Arduino 的 `LCD Keypad`<br>
> `5v 供电`

LCD    | STM32
:----- | -----:
RW     | PB4
E      | PB3
RS     | PD3
D4     | PD4
D5     | PD5
D6     | PD6
D7     | PD7

MQ-5 可燃气体传感器
---
> `5v 供电`
> `注：传感器模拟量输出可能大于 3.3v 所以要通过适当的电阻进行分压（我用了2.2k和3.3k的色环电阻）`

MQ-5   | STM32
:----- | -----:
AO     | PA1

![](https://github.com/code-structure-train/mq_5_demo/raw/master/Doc/mq_5_1.jpg)

![](https://github.com/code-structure-train/mq_5_demo/raw/master/Doc/lcd_keypad_2.jpg)

## 欢迎扫码关注我的公众号`MultiMCU EDU`。<br>
![](https://github.com/SuWeipeng/img/raw/master/gongzonghao.jpg)<br>
### `提示：在公众号“关于我”页面可加作者微信好友。`

