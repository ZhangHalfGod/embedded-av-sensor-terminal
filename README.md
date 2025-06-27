# Embedded AV Sensor Terminal

这是一个基于 GD32F303RE 的嵌入式多传感器 + 显示 + 推流系统项目，集成了温湿度/pH 采集、按钮输入、LCD 显示、音视频采集与 FFmpeg 推流等模块，适用于边缘端实时感知和远程传输场景。

## 🎯 项目目标

- 实时采集环境参数（温湿度、pH 等）
- 支持本地 LCD 显示传感器数据
- MCU → Linux 主控：通过 UART 传送传感器数据
- 主控端视频采集 → 编码 → RTMP 推流
- 可拓展 WebRTC 或 AI 图像前处理

## 🧱 项目结构

参见 [`目录结构说明`](./docs/structure.md)

## 🚀 快速开始

### 编译

```bash
make           # 或 cmake + make
