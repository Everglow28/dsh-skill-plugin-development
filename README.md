# dsh-skill-plugin-development

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Platform: DeepSeek Harness](https://img.shields.io/badge/platform-DeepSeek%20Harness-1f6feb)

DeepSeek Harness 插件开发/调试/发布流程 skill —— 由 [dsh-glm-quota-dock](https://github.com/Everglow28/dsh-glm-quota-dock) v1.0.0 → v1.3.1 的完整开发过程整理,并经官方文档(`docs/user/develop/`、`docs/cordis-primer.md`)校准。

## 安装

复制到 DSH 技能目录:

```powershell
git clone https://github.com/Everglow28/dsh-skill-plugin-development.git "$env:USERPROFILE\.dsh\skills\dsh-plugin-development"
```

重启 DSH 后,会话中涉及 DSH 插件开发/调试/发布时自动可用;也可直接点名 `dsh-plugin-development`。

## 内容

- `SKILL.md` —— 工作流主干(概念、双半部结构、调试边界、发布清单、高频坑)
- `reference.md` —— 完整参考:官方术语与加载顺序、Host/Client 模板、Standard Schema 配置、link 调试、发布 checklist、已知坑(BOM、pnpm 冷静期、registry 延迟等)

## 适用范围

- Windows 桌面版 DeepSeek Harness;进程内 Host 插件 + Web client 半部的组合包形态
- 配套实战样例:[dsh-glm-quota-dock](https://github.com/Everglow28/dsh-glm-quota-dock)

## License

MIT
