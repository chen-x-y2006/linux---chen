# linux---chen  yuc79122@gmail.com
# Simple Server Monitor

🎯 **一个用 Bash 编写的轻量级 Linux 服务器监控工具**

本项目用于监控服务器资源使用情况（CPU、内存、磁盘）及服务状态，并在资源超限时记录报警信息。适用于 Linux 运维初学者或轻量化监控需求场景。

---

## ✨ 功能特点

- ✅ 支持 CPU、内存、磁盘 使用率监控
- ✅ 支持多个服务运行状态检测（如 Nginx、MySQL、SSHD）
- ✅ 自定义报警阈值配置
- ✅ 支持命令行参数执行
- ✅ 日志记录+独立报警日志文件
- ✅ 支持 crontab 后台运行

---

## 📁 文件结构

```bash
simple-server-monitor/
├── monitor.sh        # 主监控脚本
├── config.cfg        # 配置文件（可修改报警阈值和服务列表）
├── alert.log         # 报警日志文件
└── sysmonitor.log    # 常规运行日志
