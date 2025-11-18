
# MyVerdent

MyVerdent 是一款基于 **Tauri + SvelteKit + Rust** 的 Windows 桌面工具，用于管理多个 Verdent 账号，支持额度查询、一键切换账号等功能。

> ⚠ **重要提醒**：切换账号功能会修改 Windows 机器码，以让 Verdent 识别为 新设备。详细风险说明请参考应用内的重要提示。

## 功能概览

- 账户管理：导入 / 添加 / 编辑 / 删除多个 Verdent 账户
- 额度查询：单账号查询、批量查询额度，支持进度展示
- 一键切换：自动备份当前机器码、重置机器码并应用到 Verdent
- 历史记录：记录每次切换历史，方便回溯
- Verdent 状态检测：检测 Verdent 是否运行
- 管理员状态检测：提示当前是否以管理员模式运行
## 展示
<img width="1252" height="914" alt="QQ_1763445392396" src="https://github.com/user-attachments/assets/cb22ba7b-4577-4151-9b48-ac1b6a2901e9" />


## 使用注意

- **务必理解风险**：切换账号会修改机器码，可能触发 Verdent 的风控机制。
- 使用前建议阅读应用内的重要提示（启动时弹窗或顶部注意按钮）。
- 建议始终以管理员模式启动 MyVerdent（否则部分功能会失败）。

## 推荐开发环境

- VS Code
  - Svelte 扩展
  - Tauri 扩展
  - rust-analyzer 扩展
