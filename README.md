GebImage
========

Geb.Image 是一款为图像分析目的而构建的易用、高性能的 C# 图像库。图像、视频这样的数据占人类数据总量的绝大部分，自 2008 年转型图像和视频开发时起，我就在找寻一个开发语言，能够高效的处理图像和视频数据，同时又具有高开发速度。经过多方比对，最终选择了 C#。C# 是一个成熟的快速开发语言，而打开 unsafe 后，可以直接用指针操作内存数据，能够实现接近于 C 语言的性能。Geb.Image 是我的一个尝试。

本项目有以下特色：

- 高性能：计算密集部分使用指针开发

- 自包含：是纯的 .net 库，不包含第三方 native dll

- 自2.0起，支持.Net 2.0 标准

- 兼容 dotnet/CoreRT，方便编译为独立 exe 程序发布 
