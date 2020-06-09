# WUF-C1-HCI
WUF-C1 Ultrasonic flowmeter man-machine interface.

## **目录**
  * [1主界面显示内容](#1主界面显示内容)
  * [2第二界面显示内容](#2第二界面显示内容)

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
