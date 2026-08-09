# 🌡️ IoT 温湿度仿真监测仪

> 基于 ESP32 + DHT22 + SSD1306 的在线仿真项目，**无需硬件，浏览器即可运行**。

[![Wokwi Simulation](https://img.shields.io/badge/Wokwi-Run_Simulation-blue?logo=arduino)](https://wokwi.com/projects/你的项目ID)

## ✨ 功能

- ✅ 实时温湿度采集显示
- ✅ I2C OLED 屏幕刷新
- ✅ 串口数据输出
- 🔜 WiFi 上报（计划中）
- 🔜 FreeRTOS 多任务（计划中）

## 🖥️ 在线演示

1. 点击上方 `Run Simulation` 徽章，或访问 Wokwi 项目
2. 浏览器中将出现 ESP32、传感器和 OLED 的仿真画面
3. 观察 OLED 显示温度与湿度变化

## 📂 项目结构

```
IoT-Thermo-Sim/
├── firmware/          # 固件源码 (PlatformIO)
├── simulation/        # Wokwi 仿真描述文件
├── docs/              # 截图与说明
└── README.md
```

## 🚀 如何编译（如果你有硬件）

1. 安装 PlatformIO
2. 打开 firmware/ 文件夹
3. 连接 ESP32 开发板，点击上传
4. 接线参照 simulation/diagram.json 中的定义

## 📈 深化路线图

- [x] 裸机驱动与显示
- [ ] 移植 FreeRTOS，任务间通信
- [ ] 加入 WiFi MQTT 数据上传
- [ ] 低功耗休眠唤醒
- [ ] OTA 固件更新

---

🎓 **作者**：太原理工大学 · [你的专业] · [你的姓名]

📧 联系方式：[你的邮箱]

## 📄 许可证

MIT License
