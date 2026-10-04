# MIGRATION

## v2.2.0 → v2.2.1
本次为文档与分发包修订，研究规则和数据配置不变。下载新版 ZIP，保留完整技能文件夹；既有研究结果无需迁移。

## v2.1.0 → v2.2.0
无需迁移账户或行情配置。技术覆盖新增DMI/ADX：默认14周期，+DI/-DI判方向、ADX判强度；自定义候选卡建议加入DMI/ADX字段。历史报告若无可靠DMI数据保持UNKNOWN，不回填估算值。DMI不作为独立买卖或候选排名信号。

从v2.0.0升级到v2.1.0无需迁移账户或行情配置。若自定义候选模板，请新增Positioning Risk Card字段。旧报告缺少借券/SI数据不补0，统一标UNKNOWN。


## 2026-10-02：独立仓库迁移

从 RickyyyFu/GammaLens 的 feat/equity-research-skills-v1 分支（2c2de5790f93a698b25b31660bc5c5fe1ea97dbe）完整复制 skills/us-equity-screening 到本仓库根目录。版本仍为 v2.1.0。扩充中英文 README，新增来源校验清单、测试记录及 CI。未改变研究规则、模板或运行时依赖；无需安装另一 Skill。GammaLens 未修改。
