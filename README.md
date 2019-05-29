# BME280

makecode BME280 環境溫濕度、氣壓感測器 micro:bit 套裝軟體  

Author: shaoziyang  
Date:   2018.Mar  
  
![](https://github.com/mymell2003/BME280_TW/blob/master/bme280.jpg)

## 使用方法

打開 makecode 編輯器，在項目中選擇添加套裝軟體，然後在位址欄輸入下面網址  

https://github.com/mymell2003/BME280_TW

搜索後就可以添加並使用本套裝軟體了。

## I2C 地址  

- 0x76/0x77  

## API

- function pressure()  
獲取氣壓(pa)  

- function temperature()  
獲取溫度(℃)

- function humidity()
獲取濕度(%)

- function PowerOn()
運行模式.

- function PowerOff()  
進入低功耗模式  

- function Address(addr: BME280_I2C_ADDRESS)  
設置 BME280 I2C 位址，位址可以是如下參數:  
  - BME280_I2C_ADDRESS.ADDR_0x76
  - BME280_I2C_ADDRESS.ADDR_0x77


## 授權方式

MIT

microbit/micropython 中文社區版權所有 (c) 2018  

## 支援硬體

* for PXT/microbit

