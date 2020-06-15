# WUF-C1-HCI
WUF-C1 Ultrasonic flowmeter man-machine interface.

## **参考**
本文所涉及的示意图、符号等，均可以《TUF-C1型插入式超声流量计使用说明书(Version 1.04)20200615183717》作为首要参考。

## **目录**
  * [1主界面显示内容](#1主界面显示内容)
  * [2第二界面显示内容](#2第二界面显示内容)
  * [3仪表参数界面](#3仪表参数界面)

## **1主界面显示内容**
  * 1.1公司徽识
  * 1.2日期、时间
  * 1.3第一声道正向信号强度示意、反向信号强度示意、运行状态
  * 1.4第二声道正向信号强度示意、反向信号强度示意、运行状态
  * 1.5瞬时流量

      显示范围：﹣9,999,999.999 ~﹢9,999,999.999

      单位可选m3/h、m3/s、L/h、L/s
  * 1.6正累计流量

      显示范围为 [0 ~﹢100,000,000)

      单位可选 m3、L
  * 1.7负累计流量

      显示范围为 (﹣100,000,000 ~ 0]

      单位可选 m3、L
  * 1.8显示内容相对位置
  ```
  ---------------------------------------------
  |1.1    |                |1.2               |
  |-------------------------------------------|
  |       |                                   |
  |       |1.5                                |
  |1.3    |                                   |
  |       |-----------------------------------|
  |-------|                                   |
  |       |1.6                                |
  |       |-----------------------------------|
  |1.4    |                                   |
  |       |1.7                                |
  ---------------------------------------------
```
## **2第二界面显示内容**
  * 2.1公司徽识
  * 2.2日期、时间
  * 2.3第一声道正向信号强度示意、反向信号强度示意、运行状态
  * 2.4第二声道正向信号强度示意、反向信号强度示意、运行状态
  * 2.5流速

      数值精度：0.01

      单位m/s
  * 2.6液体温度

      数值精度：0.1

      单位 ℃
  * 2.7液体压力

      数值精度：0.1

      单位MPa
  * 2.8有效测量时间

      单位 小时
  * 2.9仪表运行时间

      单位 小时
  * 2.10显示内容相对位置
  ```
  ---------------------------------------------
  |2.1    |                |2.2               |
  |-------------------------------------------|
  |       |                                   |
  |       |2.5                                |
  |2.3    |                                   |
  |       |-----------------------------------|
  |-------|                |                  |
  |       |2.6             |2.7               |
  |       |-----------------------------------|
  |2.4    |                |                  |
  |       |2.8             |2.9               |
  ---------------------------------------------
```
## **3仪表参数界面**
  * 3.1管道内径

  可修改。

  设置范围：15.0mm ~ 10000.0mm
  * 3.2安装方法

  可修改。

  设置选项：Z法、V法
  * 3.3安装距离

  不可修改。

  显示精度：0.1mm
  * 3.4零流量

  不可修改。

  显示精度：0.0001m3/h
  * 3.5始动流速

  可修改。

  设置范围：0.000m/s ~ 0.100m/s

  * 3.6修正系数

  不可修改。

  显示精度：0.0001
  * 3.7计量方向

  可修改。

  设置选项：单向、双向

  * 3.8滑动平均参数

  可修改。

  设置范围：01 ~ 99

  安装距离
  调试界面
  零流量设置按钮
