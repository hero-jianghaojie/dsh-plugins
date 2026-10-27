# DSH 插件与技能索引

DeepSeek Harness（DSH）生态里我维护的插件与技能，集中在这里做导航。
**本仓库只做索引，代码与版本仍留在各自仓库**——合并会破坏 `github:user/repo` 安装串和包身份。

| 仓库 | 类型 | 作用 | 关键词 |
|---|---|---|---|
| [dsh-lively](https://github.com/hero-jianghaojie/dsh-lively) | 插件 | 给 DSH Web GUI 加动态壁纸层：程序化预设、图片、GIF、视频，半透明壳后播放 | wallpaper / UI |
| [deepseek-harness-launcher](https://github.com/hero-jianghaojie/deepseek-harness-launcher) | 桌面启动器 + 插件 | 轻量启动 DSH 桌面端，附 API 余额查看 | launcher / 桌面端 |
| [research-paper-style](https://github.com/hero-jianghaojie/research-paper-style) | 技能 | 科研论文式作答：摘要（1–3 句结论）→ 详细介绍 → 参考文献，[n] 引用可点击溯源 | 写作 / 引用 |
| [folder-index](https://github.com/hero-jianghaojie/folder-index) | 技能 | 文件夹分类整理 + 可重建索引（_INDEX.md/_index.json/_index.tsv），移动前有引用闸门 | 文件组织 / 索引 |

## 怎么用

- **插件**：DSH 桌面版「设置 → 插件 → 添加插件」，填 `github:hero-jianghaojie/<repo>`；装完完全退出 DSH 再打开。
- **技能**：把仓库里的 skill 目录放进 `~/.dsh/skills/`（或按各仓 README 的插件方式安装），重启后生效。
- 各仓 README 里有更细的依赖、配置与已知限制，以仓库为准。

## 相关

- ADS 自动化工具合集（Python / MATLAB / EM 版图优化）：[ADS-API-Python](https://github.com/hero-jianghaojie/ADS-API-Python)
- 仓库维护约定：索引仓只改本 README；插件/技能本身在各自仓库迭代，发版时回来更新链接即可。
