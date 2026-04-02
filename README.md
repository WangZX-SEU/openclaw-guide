# 🤖 OpenClaw 虚拟机隔离安装指南

[![GitHub Pages](https://img.shields.io/badge/GitHub-Pages-brightgreen)](https://wangzx-seu.github.io/openclaw-guide/)
[![Ubuntu](https://img.shields.io/badge/Ubuntu-24.04%20LTS-orange)](https://ubuntu.com/)
[![VirtualBox](https://img.shields.io/badge/VirtualBox-7.0-blue)](https://www.virtualbox.org/)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-Latest-purple)](https://openclaw.ai/)

## 📖 简介

这是一份详尽的 OpenClaw 虚拟机隔离安装指南，专为在 **Ubuntu 24.04 主机** 上通过 **VirtualBox 虚拟机** 隔离运行 OpenClaw 而设计。

## ✨ 特点

- 🔒 **完全隔离** - OpenClaw 运行在独立虚拟机中，不影响主机系统
- 📸 **快照保护** - 可随时创建快照，出问题可快速恢复
- 🌐 **网络隔离** - NAT 模式确保虚拟机与主机网络隔离
- 📋 **详细步骤** - 每一步都有清晰的说明和可复制的命令
- ⚠️ **注意事项** - 标注了所有需要注意的坑点

## 📚 内容目录

1. **准备工作与系统要求** - 检查硬件配置，下载所需文件
2. **安装 VirtualBox 虚拟机软件** - 在 Ubuntu 24.04 上安装 VirtualBox
3. **创建虚拟机并安装 Ubuntu** - 创建虚拟机，安装系统
4. **虚拟机系统基础配置** - 换源、安装 Node.js
5. **安装 OpenClaw** - 安装并配置 OpenClaw
6. **虚拟机隔离与安全设置** - 网络隔离、防火墙、快照
7. **常见问题与故障排除** - 解决安装过程中的问题
8. **参考资源** - 官方文档和社区教程链接

## 🚀 快速开始

直接访问在线文档：**[https://wangzx-seu.github.io/openclaw-guide/](https://wangzx-seu.github.io/openclaw-guide/)**

或者克隆本仓库在本地查看：

```bash
git clone https://github.com/WangZX-SEU/openclaw-guide.git
cd openclaw-guide
# 用浏览器打开 index.html
```

## 🔧 系统要求

| 项目 | 最低要求 | 推荐配置 |
|------|---------|---------|
| 主机内存 | 8 GB | 16 GB |
| 可用磁盘 | 30 GB | 60 GB |
| CPU 核心 | 4 核 | 6 核 |

## 📦 下载资源

- [Ubuntu 24.04 LTS](https://ubuntu.com/download/desktop) - 系统镜像
- [VirtualBox](https://www.virtualbox.org/wiki/Downloads) - 虚拟机软件
- [OpenClaw 官方文档](https://docs.openclaw.ai/install) - 安装指南

## 📄 许可证

本指南采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 许可证。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这份指南！

---

📅 最后更新：2026年4月2日
