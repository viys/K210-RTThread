# K210-RTThread

## **K210**:

**芯片简介**![screenshot_image.png](https://oss-club.rt-thread.org/uploads/20230712/e829296c294981791c97ec098a05865e.png.webp)

**参数说明**

![screenshot_image.png](https://oss-club.rt-thread.org/uploads/20230712/9a835697c0bcdf4f98525933f6c6cfdb.png.webp)

# Sipeed M1n:

## 一、[M1n](https://wiki.sipeed.com/hardware/zh/maix/M1n.html#M1n)

SiPEEDM1n是基于基于嘉楠堪智科技的边缘智能计算芯片K210(RISC-v架构64位双核)设计的一款AIOT开发板。板载DVP双摄像头接口、Flash、并把大部分IO通过金手指方式引出，模块设计小巧精致、布局走线合理规范，用户可直接应用于商用产品，也可以通过转接板对此模块进行开发。
![M1n](https://wiki.sipeed.com/hardware/zh/maix/assets/m1n/M1n_1.png)

## 二、[应用](https://wiki.sipeed.com/hardware/zh/maix/M1n.html#应用)

智能家居，机器人清洁器，智能扬声器，电子门锁，家庭监控等;
医学行业应用，如辅助诊断，医学图像识别;
智能工业应用，如工业机械，智能分拣，电气设备监控等;
教育机器人，智能互动平台，教育效率检查等教育应用;
农业应用，如农业监测，病虫害监测，自动控制等

## 三、[M1n 参数](https://wiki.sipeed.com/hardware/zh/maix/M1n.html#M1n-参数)

M1n模块以K210作为核心单元，功能非常很强大，芯片内置64位双核处理器，拥有8M的片上SRAM，在Al机器视觉、听觉性能方便表现突出，内置多种硬件加速单元(KPU、FPU，FFT等)，总算力最高可达1TOPs ,可以方便地实现各类应用场景的机器视觉/听觉算法,也可以进行语音方向扫描和语音数据输出的前置处理工作。

![img](https://wiki.sipeed.com/hardware/zh/maix/assets/m1n/M1n.png)

| K210 芯片基本参数 |                                                              |
| ----------------- | ------------------------------------------------------------ |
| 内核              | RISC-V Dual Core 64bit, with FPU                             |
| 主频              | 400MHz （可超频至600MHz）                                    |
| SRAM              | 内置8M Byte                                                  |
| 图像识别          | QVGA@60fps/VGA@30fps                                         |
| 语音识别          | 麦克风阵列(8mics)                                            |
| 网络模型          | 支持YOLOv3Mobilenetv2TinyYOLOv2人脸识别等                    |
| 深度学习框架      | 支持TensorFlow \ Keras \ Darknet \ Caffe 等主流框架          |
| 外设              | FPIOA、 UART、 GPIO、 SPI、 I2C、I2S、 TIMER                 |
| 视频处理          | 神经网络处理器(KPU)FPU满足IEEE754-2008标准音频处理器(APU)快速傅里叶变换加速器(FFT) |

| 模块软件 |                                      |
| -------- | ------------------------------------ |
| 操作系统 | FreeRtos and Standrad development ki |
| 编程语言 | MicroPython                          |
| 机器视觉 | 支持卷积神经网络                     |
| 机器听觉 | 高性能音频处理器(APU)                |
| 开发环境 | 串口终端、MaixPy IDE                 |

| 模块硬件 |                                    |
| -------- | ---------------------------------- |
| 尺寸     | 22.0*25.0mm                        |
| 引脚     | 部分引脚金手指引出                 |
| 供电电压 | 5.0V @ 300mA（供电电流需大于300mA) |
| 工作温度 | -30°C ~85°C                        |

## 四、[资料下载](https://wiki.sipeed.com/hardware/zh/maix/M1n.html#资料下载)

- 芯片 K210 Datasheet: [Kendryte 官网](https://canaan-creative.com/)

- M1n 资料下载: [Click me](https://dl.sipeed.com/shareURL/MAIX/HDK/Sipeed-M1n)
- M1n 原理图下载：[Sipeed M1n Datasheet V1.0.pdf](https://dl.sipeed.com/fileList/MAIX/HDK/Sipeed-M1n/Sipeed%20M1n%20Datasheet%20V1.0.pdf)

## 仓库说明:

**K210深度学习配合RT-Thread操作系统**

