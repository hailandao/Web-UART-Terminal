Web UART Terminal
A lightweight, clean, and easy-to-use web-based serial port terminal powered by Web Serial API.
网页版轻量级串口调试助手 | 基于浏览器 Web Serial API 开发

在线预览：[https://hailandao.com/tools/uart.html ](https://hailandao.com/tools/uart.html)

✨ 功能特性

✅ 纯网页运行，无需安装软件，开箱即用

✅ 中英文双语界面，一键切换

✅ 支持 文本模式 / 十六进制模式 收发数据

✅ 接收数据自动帧合并，不拆行、不乱码

✅ 日志颜色区分：发送 = 蓝色，接收 = 绿色

✅ 支持波特率、数据位、停止位、校验位配置

✅ 界面简洁清爽、响应式布局

✅ 支持清空日志、一键发送

✅ 完美适配 ESP32 / STM32 / Arduino / 51 / 单片机 调试

🖥 界面预览
<img width="879" height="670" alt="image" src="https://github.com/user-attachments/assets/d9c32e0d-30a9-4398-915b-02046b2c524c" />

🚀 使用方法
1. 打开网页
   直接用 Chrome / Edge 浏览器 打开（或双击打开）WebUartTerminal.html

2. 连接串口
   点击 连接串口
   选择你的串口设备
   配置参数（波特率 / 数据位 / 停止位 / 校验位）

3. 发送数据
   在输入框输入内容
   选择 文本模式 或 十六进制模式
   点击 发送

4. 查看日志
   Tx Text > 发送文本
   Tx Hex > 发送十六进制
   Rx Text < 接收文本
   Rx Hex < 接收十六进制

5. 清空日志
   点击右下角 清空日志 按钮

📶 支持参数

波特率：115200 / 57600 / 38400 / 19200 / 9600 / 4800

数据位：8 / 7 / 6 / 5

停止位：1 / 1.5 / 2

校验位：无校验 / 奇校验 / 偶校验


🌏 浏览器支持
仅支持支持 Web Serial API 的现代浏览器：

✅ Google Chrome

✅ Microsoft Edge

✅ Opera

👨‍💻 开发者

Developed by hailandao

博客：hailandao.com

邮箱：dm@eejaa.com

📝 开源说明

本项目为开源工具，仅供学习与开发调试使用。

⭐ 如果对你有帮助

欢迎 Star / Fork 支持开发者！
