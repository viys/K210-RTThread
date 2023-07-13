# K210-RTThread

## **K210简介**:

勘智K10采用RISCV理器架构,具备视听一体,自主IP核与可编程能力强三大特点,支持机器视觉与机器听觉多模态识别,可广泛应用于智能家居,智能园区,智能耗和智能农业等场景.

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

## 开发环境搭建

- **编译器仓库地址:[kendryte-gnu-toolchain](https://github.com/kendryte/kendryte-gnu-toolchain)**
- **烧录器仓库地址:[kflash](https://github.com/kendryte/kflash.py)**
