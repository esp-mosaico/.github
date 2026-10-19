<div align="center">

# ESP-Mosaico

### 从一句灵感，到手中的真实作品。

为 Coding Agent 打造的模块化开发板，让 AI 创作走进物理世界。

<a href="https://mosaico.espressif.com/zh/">
  <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/mosaico-coreboard.webp" alt="ESP-Mosaico 核心板：透明机身中的 ESP32-S31 与板载硬件" width="960">
</a>

**对话创造 · 模块扩展 · 多机拼接 · 真机迭代**

[探索官网](https://mosaico.espressif.com/zh/) · [开始使用](https://mosaico.espressif.com/zh/guide/) · [发现创意应用](https://mosaico-ideas.espressif.com/) · [固件更新](https://mosaico.espressif.com/zh/firmware-update/)

</div>

---

## 👋 欢迎来到 ESP-Mosaico

一个能听你说话的桌面伙伴，一台自己编程的相机，一场跨越两块屏幕的游戏——你的下一个作品，可以从这里开始。

**ESP-Mosaico 是乐鑫面向 AI 硬件创作的模块化开发平台。** 这个组织汇集设备固件、Agent 开发工作区、板级驱动与工具链，让创作者能够描述想法、组合硬件、构建应用，并在真实设备上不断改进。

Mosaico 意为“镶嵌画”。在这里，一块模块、一台设备、一段代码，都可以成为作品中的一块拼图。

## ✨ 看看灵感如何发生

<!-- Absolute asset URLs also work on the organization Overview page. -->
<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://mosaico.espressif.com/zh/guide/chat-coding/">
        <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/chatcoding.gif" alt="官方 ChatCoding 动图：通过手机与 ESP-Mosaico 对话" width="480">
      </a>
      <h3>💬 说出来，让设备做出来</h3>
      <p>通过文字或语音描述需求，让 ESP-Claw 编写并运行代码，再用下一轮对话调整效果。第一次硬件创作，从一句话开始。</p>
      <p><a href="https://mosaico.espressif.com/zh/guide/chat-coding/"><strong>体验 ChatCoding →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://mosaico.espressif.com/zh/guide/vibe-coding/">
        <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/vibecoding.gif" alt="官方 VibeCoding 动图：ESP-Mosaico 与机器人原型联动" width="480">
      </a>
      <h3>🛠️ 给 Agent 一张硬件工作台</h3>
      <p>在电脑上与 AI 编程 Agent 协作，连接模拟器、构建工具和真实设备。从界面到外设，让每次迭代都有可观察的结果。</p>
      <p><a href="https://github.com/esp-mosaico/esp-mosaico-vibe"><strong>开始 VibeCoding →</strong></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/esp-mosaico/esp-mosaico-bsp#expansion-modules">
        <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/modules.gif" alt="官方模块扩展动图：向 ESP-Mosaico 接入不同功能模块" width="480">
      </a>
      <h3>🧩 换一块模块，多一种可能</h3>
      <p>摄像头、摇杆、交互板、测距、热成像、灯阵……借助扩展插槽与模块驱动，把感知、输入和反馈拼成自己的应用。</p>
      <p><a href="https://github.com/esp-mosaico/esp-mosaico-bsp#expansion-modules"><strong>探索扩展模块 →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/esp-mosaico/esp-mosaico-bsp#multi-device-interaction">
        <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/multi-device.gif" alt="官方多机演示动图：多台 ESP-Mosaico 组成多屏画面" width="480">
      </a>
      <h3>🔗 把屏幕拼起来，把玩法展开</h3>
      <p>通过磁吸交互、相邻关系识别与 ESP-NOW 通信，探索多屏画面、跨屏游戏和协同交互。设备怎么摆，也能成为玩法。</p>
      <p><a href="https://github.com/esp-mosaico/esp-mosaico-bsp#multi-device-interaction"><strong>探索多机示例 →</strong></a></p>
    </td>
  </tr>
</table>

<sub>以上为乐鑫官方演示。机器人、扩展模块和多机体验需要相应外设或额外设备；具体支持范围见各项目文档。</sub>

## 🚀 选择你的第一步

| 你想做什么 | 从这里开始 |
| --- | --- |
| **先让设备动起来** | 跟随[上手指南](https://mosaico.espressif.com/zh/guide/)完成设备设置，通过 [ChatCoding](https://mosaico.espressif.com/zh/guide/chat-coding/)尝试对话、界面与技能创作。 |
| **和 Agent 一起开发应用** | 打开 [ESP-Mosaico Vibe](https://github.com/esp-mosaico/esp-mosaico-vibe)，创建工程，在模拟器中验证，再部署到设备。 |
| **直接体验别人的创意** | 前往[点子中心](https://mosaico-ideas.espressif.com/)，发现适合设备与模块的应用。 |
| **从驱动和硬件开始** | 查看 [BSP 示例](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples)，探索显示、音频、传感器、扩展模块与多机交互。 |

给你的编程 Agent 一个起点：

> 基于 https://github.com/esp-mosaico/esp-mosaico-vibe ，帮我做一个 ESP-Mosaico 番茄钟：圆形倒计时、触摸暂停、结束时振动提醒。先确认硬件与开发环境，在模拟器中验证界面和交互，再部署到设备。

<details>
<summary><strong>⌨️ 想自己动手？先创建一个应用工程</strong></summary>

准备 Python 3.10 或更新版本，在终端运行：

```bash
git clone https://github.com/esp-mosaico/esp-mosaico-vibe.git
cd esp-mosaico-vibe
git submodule update --init submodule/esp-mosaico-utils
python mosaico.py project init my_app
```

这一步生成 `projects/my_app`，无需连接开发板或安装 ESP-IDF。没有 `python` 命令时可使用 `python3`。

继续构建、预览和安装前，请按 [Vibe 中文说明](https://github.com/esp-mosaico/esp-mosaico-vibe/blob/main/README_CN.md)准备固定版本的 ESP-IDF 与相应依赖；安装与维护方式见[设备模式指南](https://github.com/esp-mosaico/esp-mosaico-vibe/blob/main/docs/device-modes_CN.md)。

</details>

## 🌐 一起工作的开源项目

从设备上的 Agent，到电脑上的创作工作区，再到板级驱动与维护工具，各个项目共同支撑 ESP-Mosaico 的开发体验。

| 项目 | 从这里做什么 |
| --- | --- |
| [**ESP-Mosaico Vibe**](https://github.com/esp-mosaico/esp-mosaico-vibe) | **和 Agent 一起做应用。** 提供工作区、工程创建入口、Agent 指引，以及预览、构建和设备操作流程。 |
| [**ESP-Mosaico Claw**](https://github.com/esp-mosaico/esp-mosaico-claw) | **定制设备 Agent 与出厂固件。** 基于 ESP-Claw，集成对话、记忆、技能、Lua 扩展、MCP 与触屏应用。 |
| [**ESP-Mosaico BSP**](https://github.com/esp-mosaico/esp-mosaico-bsp) | **接入硬件，从示例构建作品。** 提供板级接口、模块管理、外设驱动和多机通信组件。 |
| [**ESP-Mosaico Utils**](https://github.com/esp-mosaico/esp-mosaico-utils) | **完善开发、调试与维护体验。** 提供 ESP-Iris、CLI、Web 工作台、Vibe Mode 固件及共享应用资源。 |

<sub>[esp-mosaico-matter](https://github.com/esp-mosaico/esp-mosaico-matter) 仓库已创建，目前尚无公开代码；后续能力以仓库实际发布内容为准。</sub>

## 🎮 下一个作品，做点什么？

这些方向已经有示例可以参考。挑一个起点，加入你的玩法。

| 灵感 | 可以继续创作的方向 |
| --- | --- |
| 📸 **一台自己的相机** | 触屏取景、拍照、相册，再设计自己的拍摄界面。[打开相机示例 →](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples/camera_photo_app) |
| 🗣️ **一个会回应的装置** | 唤醒词、中文语音指令与语音反馈。[打开语音示例 →](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples/voice_wake_cmd) |
| 🌡️ **把温度变成画面** | 接入热成像模块，观察和显示温度分布。[打开热成像示例 →](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples/thermal_camera) |
| 🕹️ **一场跨屏对战** | 用两台设备和两个摇杆模块体验双屏 Pong。[打开双屏游戏 →](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples/dual_screen_pong) |
| ✨ **一块会表达的灯阵** | 让 8 × 8 RGB 灯阵播放动画，在屏幕上同步预览。[打开灯阵示例 →](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples/matrix_rgb_led) |

<details>
<summary><strong>🔍 展开看看这块开发板</strong></summary>

<p align="center">
  <a href="https://mosaico.espressif.com/zh/guide/">
    <img src="https://raw.githubusercontent.com/esp-mosaico/.github/main/profile/assets/device-overview-zh.png" alt="ESP-Mosaico 官方硬件视图，标注按键、接口与扩展位置" width="880">
  </a>
</p>

| 能力 | 硬件基础 |
| --- | --- |
| 运算与显示 | ESP32-S31、480 × 480 触摸屏 |
| 声音与反馈 | ES8311 音频编解码器、板载麦克风、扬声器功放、振动马达 |
| 动作与磁感知 | BMI270 六轴 IMU、双 BMM150 磁力计 |
| 存储与电源管理 | SPI NAND、BQ27220 电量计 |
| 连接与扩展 | USB OTG、左右两个可热插拔扩展槽 |

摄像头通过**左侧扩展槽**接入；模块、总线资源及板卡版本的限制请查阅 [BSP 文档](https://github.com/esp-mosaico/esp-mosaico-bsp)。

</details>

## 🤝 把你的那块拼图带进来

欢迎从一个作品、一个问题或一次改进开始参与：

- **做出新作品**：从 [Vibe 工作区](https://github.com/esp-mosaico/esp-mosaico-vibe)或 [BSP 示例](https://github.com/esp-mosaico/esp-mosaico-bsp/tree/master/examples)开始，把自己的想法做成可运行的应用。
- **让下一位开发者少走弯路**：补充文档、复现步骤和模块使用经验，或向对应仓库提交 Issue / Pull Request。
- **一起完善基础能力**：改进 [Claw 的设备体验](https://github.com/esp-mosaico/esp-mosaico-claw)、[BSP 的硬件支持](https://github.com/esp-mosaico/esp-mosaico-bsp)和 [Utils 的开发工具](https://github.com/esp-mosaico/esp-mosaico-utils)。

---

<div align="center">

### 下一块拼图，由你创造。

[**开始你的第一个作品 →**](https://mosaico.espressif.com/zh/guide/)

<sub>产品图片与演示动图来自 <a href="https://mosaico.espressif.com/zh/">ESP-Mosaico 官网</a>及<a href="https://www.espressif.com/zh-hans/news/ESP_Mosaico_Release">乐鑫官方发布介绍</a>，版权归原权利人所有。各项目的许可条款请查看对应仓库。</sub>

</div>
