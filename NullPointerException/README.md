# NullPointerException

> 你的 Minecraft 抛出了一个异常。

将 Minecraft 简体中文文本替换为编程梗、Java 异常和开发笑话的资源包。

## 📦 简介

NullPointerException 是一个纯语言资源的 Minecraft 资源包。它不修改任何纹理、模型或声音 —— 只改文本。

每条翻译都是一次键值覆盖：`item.minecraft.golden_sword` 不再映射到 `"金剑"`，而是映射到 `"金剑(kill -9)"`。从物品名到死亡提示，从选项菜单到成就描述，所有可见的中文文本被重构为一套编程笑话。

## ✨ 特性

- **编程梗全覆盖** — 物品、方块、状态、死亡消息、成就、GUI 文本，约 6800+ 条键值
- **Java 异常风格** — 死亡不是 "你死了"，是 `⛔ 你BSOD了！`；重生是 `reboot`
- **Linux 命令调侃** — `kill -9`、`sudo`、`echo`、`grep`、`chmod` 随处可见
- **MC 原生显示** — 沿用 § 颜色代码，游戏内效果与原版一致，只是内容变了
- **轻量级** — 仅 400+ KB，纯 JSON，覆盖整个游戏

## 🚀 安装

1. **下载** 本仓库或 Release 中的 `NullPointerException.zip`
2. **放置** 到 Minecraft 资源包文件夹：
**resourcepacks**
1. **启用**：进入游戏 → 选项 → 资源包 → 选择 NullPointerException → 完成

## 🔍 语言变更示例

| 原版 | NullPointerException |
|------|---------------------|
| 金剑 | 金剑(kill -9) |
| 钻石镐 | 钻石镐 (OP镐) |
| 苹果 | 苹果 (HP restore) |
| 箭 | 箭 (Projectile ptr) |
| 骨头 | 骨头(Wild Pointer) |
| 你死了！ | ⛔ 你BSOD了！ |
| 重生 | reboot |
| 标题屏幕 | 标题屏幕(Main Menu) |
| 命令方块 | 控制台命令 (Console) |
| 循环 | while loop |
| 红石比较器 | 红石Circuit |
| 工作台 | IDE |
| 合成 | compile |
| 保护 | try-catch |
| 怪物猎人 | EntityHunter |

完整列表见 `assets/minecraft/lang/zh_cn.json`（6800+ 行）。

## 🎯 兼容性

- **游戏版本**: Minecraft Java Edition 1.21.x
- **语言文件格式**: pack_format 34（对应 1.21.x）
- **仅影响简体中文（zh_cn）客户端** — 英文或其他语言玩家不受影响
- 与任何纹理/模型资源包兼容

## 📄 许可证

GNU General Public License v3.0 — 详见 [LICENSE](./LICENSE) 和根目录 [LICENSE](../LICENSE)。

---

> Minecraft 是 Mojang Studios 的商标。本资源包与 Mojang Studios 无关。
