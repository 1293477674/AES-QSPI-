# AES-QSPI-
2020年新工科联盟-Xilinx暑期学校（Summer School）项目

项目名称：
=============================
AES加解密与QSPI通信

项目概要：
============
本项目利用FPGA的ADC串口输入待加密的外部信号，通过拨码开关的变更来调整加密密钥，利用FPGA对明文进行加密操作，得到密文。然后将加密后的数据通过QSPI通信协议发送到ESP32，最后将加密后的数据传输到AWS云端实现外部信号的加密可视化。   
 
已实现功能
==============
通过FPGA对输入的明文（密文）进行加密（解密）

未实现功能
===========
连接esp32与aws云端

使用工具版本：
=========    
Vivado2018.3；<br>
uPyCraft_V1.0;<br>
Arduino IDE;<br>    
    
板卡型号与外设列表：
========
板卡型号:Spartan Edge Accelerator Board(SEA)<br>
芯片型号:XC7S15ftgb196-1

仓库目录介绍：
============
README.md-----仓库介绍；<br>
images--------项目图片；<br>
Sourcecode----项目源代码；<br>
Executable----可执行文件；<br>
