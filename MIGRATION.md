# MIGRATION

从v2.0.0升级到v2.1.0无需迁移账户或行情配置。若自定义候选模板，请新增Positioning Risk Card字段。旧报告缺少借券/SI数据不补0，统一标UNKNOWN。


## 2026-10-02：独立仓库迁移

从 RickyyyFu/GammaLens 的 feat/equity-research-skills-v1 分支（2c2de5790f93a698b25b31660bc5c5fe1ea97dbe）完整复制 skills/us-equity-screening 到本仓库根目录。版本仍为 v2.1.0。扩充中英文 README，新增来源校验清单、测试记录及 CI。未改变研究规则、模板或运行时依赖；无需安装另一 Skill。GammaLens 未修改。
