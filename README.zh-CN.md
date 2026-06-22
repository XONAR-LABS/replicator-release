<p align="center">
  <img src="./assets/icon.png" alt="Replicator app icon" width="112" height="112">
</p>

<h1 align="center">Replicator</h1>

<p align="center">
  <strong>硬件产品的 Codex。</strong>
</p>

<p align="center">
  把一句产品想法推进到机械结构、电气电路、PCB 和制造都能落地的真实原型。
</p>

<p align="center">
  <a href="./README.md">English</a> |
  <a href="./README.zh-CN.md">简体中文</a> |
  <a href="./README.ja.md">日本語</a>
</p>

<p align="center">
  <a href="https://github.com/XONAR-LABS/replicator-release/releases/latest">下载最新 macOS 版本</a>
</p>

> [!IMPORTANT]
> 当前公开版本面向 **macOS Apple Silicon**。
> Windows、Linux、Intel macOS 和 Universal macOS 版本暂未发布。

<br>

## Replicator 是什么？

Replicator 是面向实体产品和硬件原型的 AI 工作台。

你只需要描述想做的产品，Replicator 会帮助你把想法继续往前推进：整理产品方案、拆解实现路径、选择零件，推进机械结构、电气电路和 PCB 设计，准备制造交付文件，并给出下一步打样或制造动作。

它适合创始人、创客、硬件团队和产品团队，用来减少在设计工具、供应链平台、表格、制造平台和设备流程之间反复切换的时间。

## Replicator 可以帮你做什么

- 把一句产品想法整理成清晰的实现计划。
- 像 AI 产品工程师一样，和你一起讨论功能、约束、零件、成本和下一步。
- 在一个流程里推进机械结构、电气电路、PCB 规划和原型约束。
- 准备用于原型打样的设计、电气和制造交付文件。
- 在一个本地项目里管理生成文件、设计决策和迭代过程。
- 在支持的流程里，帮助你准备提交给嘉立创、华秋等制造平台的资料。
- 在支持的流程里，帮助你把合适的制造任务推进到拓竹等桌面制造设备。

Replicator 不只是画图工具。它解决的是从“我想做这个产品”到“我可以打样、下单或制造”的中间执行工作。

## 安装

1. 打开
   [最新版本页面](https://github.com/XONAR-LABS/replicator-release/releases/latest)。
2. 下载 `.dmg` 文件。
3. 打开磁盘映像，把 **Replicator** 拖入 **Applications**。
4. 启动 Replicator，并创建或打开一个项目文件夹。

Release 页面里可能还会有 `.zip`、`.blockmap` 和 `latest-mac.yml` 文件。大多数用户只需要安装 `.dmg`；其他文件用于应用更新和发布信息。

> [!NOTE]
> 第一次启动可能会更久，因为 Replicator 需要准备本地制造运行环境。请保持应用打开，直到初始化完成。

## 系统要求

- Apple Silicon 芯片的 Mac
- 下载、首次初始化和 AI 模型调用需要网络连接
- 根据你使用的工作流，需要配置模型服务，或连接本机 Codex 应用

为了获得更好的效果，建议使用具备强推理能力的模型。

## 隐私和本地文件

Replicator 会把项目文件保存在你选择的项目文件夹中。生成文件、产物和项目日志会保留在你的机器上，除非你主动分享或同步该文件夹。

AI 模型请求会发送给你配置的模型服务商。

## 支持

如果遇到问题，或需要发布版本相关帮助，请在
[Replicator release repository](https://github.com/XONAR-LABS/replicator-release/issues)
提交 issue，并附上应用版本、macOS 版本、你正在尝试的操作以及相关错误信息。

## 发布说明

每个 GitHub release 都包含对应版本的应用文件和发布说明。版本变化、修复内容和已知限制，请阅读你下载版本对应的 release notes。
