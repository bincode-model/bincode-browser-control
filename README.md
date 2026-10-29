# BinCode 多浏览器控制

![BinCode 多浏览器控制介绍](bincode-browser-control-intro-16x9.png)

macOS 多浏览器控制台，保存版本 **1.1.1**。支持 140 个独立编号环境，通过自有浏览器插件及 MCP 服务接入 AI 任务。

## 完整项目与源码

| 文件 | 内容 |
| --- | --- |
| [完整源码 ZIP](bincode-browser-control-v1.1.1-complete-source.zip) | 124 个文件，保留原目录；包括前后端、Swift 原生窗口、浏览器插件、MCP、脚本、测试及交接资料 |
| [源码 Git bundle](bincode-browser-control-source-history.bundle) | 保留已有源码提交和本次完整备份提交，可还原 Git 仓库和文件执行权限 |
| [源码逐文件清单](SOURCE_FILE_MANIFEST.json) | 文件路径、大小及 SHA-256 / Git blob 校验值 |
| [本地核验结果](BACKUP_VERIFICATION.json) | 原文件比对、程序归档核验和 140 个编号浏览器检查结果 |
| [运行文件与校验](https://github.com/bincode-model/bincode-browser-control/releases/tag/backup-v1.1.1-20261029) | 原生应用、固定版 Chromium、140 个编号程序、Node.js、Codex CLI 和运行依赖 |

源码包中的目录包括 `src/`、`public/`、`extension/`、`mac/`、`scripts/`、`tests/`、`handoff/`、`backup-metadata/` 和 `assets/`。安装迁移工具、历史验收材料、使用与开发说明均按原内容保存。

下载 Git bundle 后可在本地恢复完整源码仓库：

```sh
git clone bincode-browser-control-source-history.bundle bincode-browser-control
```

## 完整性与资料边界

本次比较现用安装目录、安装暂存、此前源码备份及原交接压缩包。原交接包共检查 59,243 个条目，93 个源码和交接文件均匹配；程序归档的 140 个编号浏览器全部保留。

所有浏览器登录档案、cookie、session、管理员及插件令牌、模型认证和当前业务记录留在本机。原始含登录资料的交接压缩包未原样上传。

历史验收资料记录 2026-10-17 当时结果。本次执行文件和归档完整性核验，没有运行店铺或业务操作。原迁移安装器依赖原交接包的数据和校验清单，复原程序文件时应在新目录初始化独立资料。

介绍图使用 Codex 内置 image_gen 生成，为产品概念介绍视觉。最终提示词与品牌素材来源保存在完整源码包 `assets/marketing/IMAGE_GENERATION.md`。第三方组件来源和许可证保存在源码包 `THIRD_PARTY_NOTICES.md` 及 `GitHub参考与版本.txt`。
