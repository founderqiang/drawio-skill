# drawio-skill — From Text to Professional Diagrams

[English](README.md) | [Online Docs](https://agents365-ai.github.io/drawio-skill/)

<p align="center">
  <img src="assets/workflow-cn.png" width="420" alt="工作流程">
</p>

## 功能说明

| 能力 | 说明 |
|---|---|
| `.drawio` XML 生成 | 根据自然语言描述生成 |
| 多格式导出 | PNG / SVG / PDF / JPG，使用 draw.io 桌面版原生 CLI |
| 6 种图表类型预设 | ERD、UML 类图、序列图、架构图、ML/深度学习、流程图 |
| 迭代审查 | 自检 + 自动修复(最多 2 轮),再走 5 轮反馈循环直到你满意 |
| 样式预设 | 用 `.drawio` 文件或图片"教会"Skill 你的风格,命名保存后随时复用 |
| 自动触发 | 图表有助于解释复杂系统时自动调用 |

## 对比

参见 [COMPARISON_CN.md](COMPARISON_CN.md) —— 与原生智能体、其他 draw.io skills/工具（jgraph/drawio-mcp、bahayonghang/drawio-skills、GBSOSS/ai-drawio）的对照表，以及核心优势小结。

## 支持的图表类型

| 类别 | 示例 | 特色 |
|---|---|---|
| 架构图 | 微服务、云（AWS/GCP/Azure）、网络拓扑、部署 | 分层泳道、hub 居中策略 |
| ML / 深度学习 | Transformer、CNN、LSTM、GRU | 张量形状标注、层类型配色 |
| 流程图 | 业务流程、工作流、决策树、状态机 | 语义形状（平行四边形 I/O、菱形判断） |
| UML | 类图、序列图 | 继承 / 组合 / 聚合箭头；生命线 + 激活框 |
| 数据图 | ER 图、数据流图(DFD) | 表容器、PK/FK 标记 |
| 其他 | 组织架构图、思维导图、线框图 | — |

## 安装

两步 —— 先装 draw.io CLI,再把技能加载到 host:

1. **[安装 draw.io 桌面版](INSTALL_CLI_CN.md)** —— macOS / Windows / Linux 各平台配方。
2. **[安装技能](INSTALL_SKILL_CN.md)** —— 插件市场(推荐)、手动克隆、以及更新命令。

## 使用方式

参见 [USAGE_CN.md](USAGE_CN.md) —— 包含自然语言提示词、微服务示例,以及多种拓扑演示(星形 / 分层 / 环形)。

## 样式预设

参见 [STYLE_PRESETS_CN.md](STYLE_PRESETS_CN.md) —— 包含内置预设(`default` / `corporate` / `handdrawn`)、"从文件学习样式"流程,以及完整的预设管理命令。

## 支持作者

如果这个 skill 对你有帮助，欢迎支持作者：

<table>
  <tr>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Agents365-ai/images_payment/main/qrcode/wechat-pay.png" width="180" alt="微信支付">
      <br>
      <b>微信支付</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Agents365-ai/images_payment/main/qrcode/alipay.png" width="180" alt="支付宝">
      <br>
      <b>支付宝</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Agents365-ai/images_payment/main/qrcode/buymeacoffee.png" width="180" alt="Buy Me a Coffee">
      <br>
      <b>Buy Me a Coffee</b>
    </td>
    <td align="center">
      <img src="https://raw.githubusercontent.com/Agents365-ai/images_payment/main/awarding/award.gif" width="180" alt="打赏">
      <br>
      <b>打赏</b>
    </td>
  </tr>
</table>

## 作者

**Agents365-ai**

- Bilibili: https://space.bilibili.com/441831884
- GitHub: https://github.com/Agents365-ai

## 开源协议

MIT
