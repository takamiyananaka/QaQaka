<div align="center">

# 🌸 QaQaka

**专为 Android 移动端现代 QQ 架构打造的轻量级体验增强与交互辅助工具**

[![Release](https://img.shields.io/github/v/release/takamiyananaka/QQEmojiReactor?color=blue&logo=github)](https://github.com/takamiyananaka/QQEmojiReactor/releases)
[![License: GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-blue.svg)](LICENSE)
[![Framework](https://img.shields.io/badge/Framework-LSPosed%20%7C%20Xposed-orange)](https://github.com/LSPosed/LSPosed)
[![Target](https://img.shields.io/badge/Target-QQ%20NT%209.2.80%2B-green)](https://im.qq.com)
[![Platform](https://img.shields.io/badge/Platform-Android%208.0+-brightgreen)](https://android.com)

</div>

---

## 📖 项目愿景与设计哲学 (Overview)

**QaQaka**（原名：菜々華）是一个旨在探索 Android 平台现代化无障碍交互管线与 UI 自适应渲染的开源技术范例项目。

项目始终恪守以下工程原则：
- 🔒 **纯本地离线运行 (Local-Only)**：无任何独立远程服务器，零网络外部数据传输，不收集、不存储、不上报任何用户的聊天记录、好友关系或个人隐私。
- ⚡ **原生级 120Hz 丝滑体验**：纯数据流驱动与纯 GPU 视图绘制，杜绝主线程额外度量与重排风暴，保障极速流畅。
- 🎨 **单向客户端视觉辅助**：所有视觉定制仅在当前设备本地视图层生效，不向服务端发送任何非法请求，保障客户端纯净与稳定。

---

## ✨ 核心优化领域 (Functional Areas)

本项目提供克制、实用的客户端体验优化与辅助能力：

- 🎭 **交互辅助**：群聊表情快速互动辅助与状态管理；
- 📝 **消息增强**：客户端消息状态提示与本地视图保护；
- 🖼️ **多媒体优化**：客户端本地图片与媒体资源查看体验增强；
- 🎨 **外观装扮**：本地单向头像个性化渲染与专属沉浸式裁剪。

> *注：具体设置项与交互细节已完整内置于模块设置面板中，安装启用后即可直观配置。*

---

## 📱 运行环境要求 (Compatibility)

- **操作系统**：Android 8.0 及以上版本（深度兼容各类主流定制系统）
- **框架支持**：支持并兼容现代主流 Xposed / LSPosed 框架
- **宿主版本**：官方正版手机 QQ（适配 QQ NT 9.2.80 及以上版本）

---

## 🚀 快速使用说明 (Quick Start)

1. 从本仓库 [Releases 页面](https://github.com/takamiyananaka/QQEmojiReactor/releases) 获取最新发行版安装包；
2. 在 LSPosed 管理器中启用 **QaQaka**，并在推荐作用域中勾选 **手机 QQ (`com.tencent.mobileqq`)**；
3. 强制停止手机 QQ 并重新启动即可生效；
4. 进入 QaQaka 主程序界面可按需进行个性化设置。

---

## 💬 交流与反馈 (Feedback & Suggestions)

非常欢迎大家体验和使用 **QaQaka**！

- **问题反馈**：如在使用过程中遇到任何异常或偶发故障，欢迎提交 [GitHub Issues](https://github.com/takamiyananaka/QQEmojiReactor/issues) 并附上机型、系统版本与复现步骤；
- **需求与建议**：如果你有新的想法、功能需求或交互优化建议，十分欢迎在 Issues 中交流探讨；
- **开发与迭代**：由于本项目属于个人业余维护，作者会在空闲时间认真阅览大家的每一条反馈，并根据技术可行性与通用价值，酌情参考排期并持续迭代。

感谢大家的理解、包容与支持！🌟

---

## ⚖️ 免责声明 (Disclaimer)

**在下载、阅读、编译或使用本项目前，请务必仔细阅读并充分理解本声明。任何使用、修改或分发本项目的行为，均视为您已完全知晓并无条件接受以下全部条款：**

1. **学术研究性质**：本项目仅作为个人针对 Android 运行机制、UI 渲染管线及无障碍交互技术的学习、研究与逆向工程学术探讨用途，属于非商业性质的开源研究项目。
2. **知识产权声明**：“QQ”及相关图形、文字、标识等知识产权均归属于深圳市腾讯计算机系统有限公司（以下简称“腾讯公司”）所有。本项目与腾讯公司不存在任何隶属、合作、关联或官方授权关系。
3. **禁止恶意用途**：本项目严禁用于任何商业营利、批量骚扰、侵犯他人合法权益或任何违反法律法规、公序良俗的行为。任何第三方因违反本约定产生的争议或法律后果均由行为人独立承担。
4. **风险自行承担**：本项目按“现状”（AS-IS）提供，作者及贡献者不对软件的可用性、稳定性作任何明示或暗示的保证。因使用本项目引发的设备异常、数据丢失或账号争议，作者及贡献者均不承担连带责任。
5. **权利人保护**：若腾讯公司或相关权利人认为本项目内容涉嫌侵犯其合法权益，请通过 GitHub Issue 发送权属声明，维护者核实后将积极配合进行下架或清理处理。

---

## 📄 开源许可证 (License)

本项目遵循 [GNU General Public License v3.0 (GPL-3.0)](LICENSE) 开源协议。
