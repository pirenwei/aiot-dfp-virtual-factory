
# AIOT-DFP Virtual Factory Demo

## 1. 简介
虚拟工厂 Demo，用于展示 AIOT-DFP 平台能力。  
不包含真实客户或商业数据，完全开源。

## 2. 架构概览
- Simulator → Kafka → NiFi → InfluxDB → 后端 → 前端

## 3. 快速启动
1. 安装 Docker / Docker Compose  
2. 克隆仓库  
3. 执行：
   docker-compose up
4. 打开浏览器访问 http://localhost:3000

## 4. 功能
- 多工厂切换  
- 产线实时状态  
- 批次追溯  
- 告警监控  
- 数据流可视化

## 5. 贡献
请参阅 CONTRIBUTING.md

## 6. License
Apache 2.0
