# WUF-C1-HCI
WUF-C1 Ultrasonic flowmeter man-machine interface.

## **参考**
本文所涉及的示意图、符号等，均可以《TUF-C1型插入式超声流量计使用说明书(Version 1.04)20200615183717》作为首要参考。

另附Andy-3 Ultrasonic Flow Analysis System软件，作为功能参考。

## **目录**
  * [1主界面](#1主界面显示内容)
  * [2第二界面](#2第二界面显示内容)
  * [3仪表参数界面](#3仪表参数界面)
  * [4加密设置界面](#4加密设置界面)
  * [5仪表调试界面](#5仪表调试界面显示内容)
  * [6历史数据界面](#6历史数据界面显示内容)

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

      数值精度：0.01

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
  * 3.9瞬时流量单位

      可修改。

      设置选项：m3/h、m3/s、L/h、L/s
  * 3.10累计流量单位

      可修改。

      设置选项：m3、L
  * 3.11流速单位

      可修改。

      设置选项：m/s、mm/s
  * 3.12波特率

      可修改。

      设置选项：1200bps、2400bps、4800bps、9600bps
  * 3.13校验位

      可修改。

      设置选项：None、Odd、Even
  * 3.14地址

      可修改。

      设置范围：001 ~ 247
  * 3.15量程下限

      可修改。

      设置范围：﹣9,999,999.999~﹢9,999,999.999m3/h
  * 3.16量程上限

      可修改。

      设置范围：﹣9,999,999.999~﹢9,999,999.999m3/h
  * 3.17功能选择

      可修改。

      设置选项：关闭、累计脉冲、报警开关、频率输出
  * 3.18脉冲宽度

      可修改。

      设置范围：5 ~ 200ms
  * 3.19脉冲当量

      可修改。

      设置范围：0.000001 ~ 10.000000 m3
  * 3.20报警上限

      可修改。

      设置范围：﹣9,999,999.999~﹢9,999,999.999m3/h
  * 3.21报警下限

      可修改。

      设置范围：﹣9,999,999.999~﹢9,999,999.999m3/h
  * 3.22用户密码开关

      可修改。

      设置选项：关、开
  * 3.23修改用户密码

      可修改。

      设置范围：0000 ~ 9999
  * 3.24用户密码使用规则

      当用户密码开关设为“开”时，进入仪表参数界面需输入正确的用户密码。

      默认密码为0000。

      如果连续 3 次密码输入错误，仪表参数界面将被锁定 48 小时。
## **4加密设置界面**
  * 4.1实时时钟校准

      既要校准屏幕显示的实时时钟，也要校准主板上运行的实时时钟。
  * 4.2模拟量4mA输出校准

      要通过上下按钮调整数值，步进量为1。

      设置范围：365 ~ 999
  * 4.3模拟量20mA输出校准

      要通过上下按钮调整数值，步进量为1。

      设置范围：2731 ~ 4095
  * 4.4数据更正

      用于修改累计流量数值。

      设置范围： ﹣99,999,999.99~﹢99,999,999.99 m3
  * 4.5修正系数

      设置范围：0.8 ~ 1.3
  * 4.6正向分段修正

    4.6.1标定点数量

      设置范围：1 ~ 9

    4.6.2标定点流速（9组）

      设置范围：0.000 ~ 20.000

    4.6.3分段修正系数（9组）

      设置范围：0.0001 ~ 3.0000
  * 4.7反向分段修正

    4.7.1标定点数量

      设置范围：1 ~ 9

    4.7.2标定点流速（9组）

      设置范围：0.000 ~ 20.000

    4.7.3分段修正系数（9组）

      设置范围：0.0001 ~ 3.0000
  * 4.8零流量设置

      零流量设置可通过“手动输入”和“自动设置”两种方式进行。

      手动输入范围：-500 ~ 500 m3/h

      自动设置方法：参见通信协议和主板接口操作流程。
  * 4.9加密规则

      加密设置界面中各项，均使用动态密码验证用户操作权限。

      动态密码的交互过程，参见通信协议和主板接口操作流程。
## **5仪表调试界面显示内容**
  * 5.1公司徽识
  * 5.2日期、时间
  * 5.3第一声道正向信号强度

      数值精度：0.01

      单位：%
  * 5.4第一声道反向信号强度

      数值精度：0.01

      单位：%
  * 5.5第一声道信号质量

      数值精度：1

      单位：%
  * 5.6第一声道运行状态
  * 5.7第一声道传播时间

      数值精度：0.01

      单位：us
  * 5.8第一声道传播时差

      数值精度：0.001

      单位：ns
  * 5.9第二声道正向信号强度

      数值精度：0.01

      单位：%
  * 5.10第二声道反向信号强度

      数值精度：0.01

      单位：%
  * 5.11第二声道信号质量

      数值精度：1

      单位：%
  * 5.12第二声道运行状态
  * 5.13第二声道传播时间

      数值精度：0.01

      单位：us
  * 5.14第二声道传播时差

      数值精度：0.001

      单位：ns
  * 5.15软件版本
  * 5.16核心版本
  * 5.17显示内容相对位置
```
---------------------------------------------
|5.1    |                |5.2               |
|-------------------------------------------|
|5.3            |5.5          |5.7          |
|5.4            |5.6          |5.8          |
|-------------------------------------------|
|5.9            |5.11         |5.13         |
|5.10           |5.12         |5.14         |
|-------------------------------------------|
|5.16                |5.17                  |
---------------------------------------------
```
## **6历史数据界面显示内容**
