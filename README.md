# BME280

makecode BME280 环境温湿度、气压传感器 micro:bit 软件包  

Author: shaoziyang  
Date:   2018.Mar  

![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/icon.png)  
  
![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/bme280.jpg)

## 使用方法

打开 makecode 编辑器，在项目中选择添加软件包，然后在地址栏输入下面网址  

https://github.com/microbit-makecode-packages/BME280_cn  

搜索后就可以添加并使用本软件包了。

## I2C 地址  

- 0x76/0x77  

## API

- function pressure()  
获取气压(hpa)  

- function temperature()  
获取温度(℃)

- function humidity()
获取湿度(%)

- function PowerOn()
运行模式.

- function PowerOff()  
进入低功耗模式  

- function Address(addr: BME280_I2C_ADDRESS)  
设置 BME280 I2C 地址，地址可以是如下参数:  
  - BME280_I2C_ADDRESS.ADDR_0x76
  - BME280_I2C_ADDRESS.ADDR_0x77

## 演示

![](https://raw.githubusercontent.com/microbit-makecode-packages/BME280_cn/master/demo.jpg)

## 授权方式

MIT

microbit/micropython 中文社区版权所有 (c) 2018  

## 支持硬件

* for PXT/microbit


[来自 microbit/micropython 中文社区](http://www.micropython.org.cn) 
