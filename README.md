# proj311-ArceOS
# 基于飞腾派部署ArceOS操作系统实现智能小车驱动

## 项目描述

飞腾派开发板是飞腾公司针对教育行业推出的一款国产开源硬件平台，兼容 ARMv8-A 处理器架构。飞腾小车是一款利用飞腾派开发板组装的小车，它是一个计算机编程实验平台，包含电机驱动、红外传感器、超声传感器、AI加速棒、视觉摄像云台等，可以满足学生学习计算机编程、人工智能训练等课题。

ArceOS是基于组件化设计的思路，用Rust语言的丰富语言特征，设计实现不同功能的独立操作系统内核模块和操作系统框架，可形成不同特征/形态/架构的操作系统内核。

本项目需要参赛队伍将ArceOS移植到飞腾派开发板，实现UART串口通信、以太网口通信（HTTP server和HTTP client 可以上传下载文件），并且可以通过实现I2C驱动和USB驱动去驱动小车行走。

飞腾小车

![Pasted image 20240226171957](https://github.com/oscomp/proj311-ArceOS/assets/160444530/507ac2e3-1624-4c42-b563-fc07824cbdc6)


## 预期目标

1. 完成ArceOS操作系统移植到飞腾派开发板。
2. 实现UART串口通信。
3. 实现以太网口通信（HTTP server和HTTP client 可以上传下载文件）。
4. 通过实现I2C驱动PCA9685模块来驱动电机实现小车行走。
5. 通过实现USB驱动利用遥控手柄实现小车行走。

## 特征

- 熟悉操作系统/计算机组成原理等基本概念
- 熟悉Rust语言
- 熟悉驱动原理和开发
- 可支持硬件
	- 飞腾小车（基于飞腾派开发板控制）

## 已有参考资料

- [操作系统大赛飞腾赛道交流社区](https://edu.phytium.com.cn/group/10)
- [飞腾派开发板电子发烧友社区](https://bbs.elecfans.com/group_1708)
- [ArceOS源码仓库](https://github.com/rcore-os/arceos)
- [赛题资料汇总](https://edu.phytium.com.cn/group/10/thread/21579)
## 赛题分类

内核移植

## 参赛要求

- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生或研究生
- 允许学生参加大赛的多个不同题目，最终自己选择一个题目参与评奖
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求

## 难度

中等-高等

## License

- GPL-3.0
- Apache-2.0

## 所属赛道

2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 项目导师

**赛事支持导师**
- 姓名：郭丁丁
- 单位：飞腾信息技术有限公司
- email：[guodingding1657@phytium.com.cn](mailto:guodingding1657@phytium.com.cn)
**飞腾小车支持导师**
- 姓名：连宇飞
- 单位：飞腾信息技术有限公司
- email：[lianyufei@phytium.com.cn](mailto:lianyufei@phytium.com.cn)
**飞腾技术支持导师**
- 姓名：李阳
- 单位：飞腾信息技术有限公司
- email：[liyang1265@phytium.com.cn](mailto:liyang1265@phytium.com.cn)
