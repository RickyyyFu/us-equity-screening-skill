# CHANGELOG

## 2.1.0 · 2026-10-02
- 新增Short squeeze与Long unwind/多杀多分析。
- 新增Short Interest/Short Volume强制区分、13F/GEX限制、Fuel→Trigger→Feedback阶段。
- 候选卡加入crowding状态、借券、float、期权放大、供给事件、触发/失效和数据日期。
- 拥挤度不得单独决定排名。


## 2026-10-02：独立仓库迁移

从 RickyyyFu/GammaLens 的 feat/equity-research-skills-v1 分支（2c2de5790f93a698b25b31660bc5c5fe1ea97dbe）完整复制 skills/us-equity-screening 到本仓库根目录。版本仍为 v2.1.0。扩充中英文 README，新增来源校验清单、测试记录及 CI。未改变研究规则、模板或运行时依赖；无需安装另一 Skill。GammaLens 未修改。
