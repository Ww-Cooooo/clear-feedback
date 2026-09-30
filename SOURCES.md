# 来源与改编

Clear Feedback 处理的是已有作品或方案的模糊反馈，目标是形成可以继续制作和比较的下一版。它保留自身的触发边界与修订闭环，结合以下方法作了适配，不依赖这些 Skill 才能运行。

核对日期：2026-09-30。作者为 Matt Pocock，原仓库为 [mattpocock/skills](https://github.com/mattpocock/skills)。本次固定核对提交 `d81f3a183412e71a5b1e84ca21bc1a35eea03a60`，提交日期为 2026-09-29；这标识所读版本，不证明下表各项都在当天首次发布。

| 来源 | 本 Skill 吸收的部分 |
|---|---|
| [grill-me](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/productivity/grill-me/SKILL.md) 与 [使用说明](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/docs/productivity/grill-me.md) | 主动检验隐含判断；有些体验要通过小样而非继续口头访谈来判断。 |
| [grilling](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/productivity/grilling/SKILL.md) | 从材料查事实；先解决后续问题所依赖的分歧；无依赖的少量问题可以同轮处理。 |
| [grill-with-docs](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/engineering/grill-with-docs/SKILL.md) 与 [domain-modeling](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/engineering/domain-modeling/SKILL.md) | 用具体情境澄清含混词语，核对与现有说明、实现的冲突。 |
| [prototype](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/engineering/prototype/SKILL.md) | 小样服务于一个明确待判断的问题，暂定材料不当作正式结果。 |
| [triage](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/skills/engineering/triage/SKILL.md) | 核对报告中的事实问题；续接时使用已有答案，具体说明还缺什么。 |

## 适配到反馈任务的取舍

上游访谈用于把计划各分支讨论清楚；本 Skill 只解决会改变已授权下一版的分歧，不遍历全树，也不把所有工作额外卡在最终确认上。

上游给每道题推荐答案；此处区分专业改法和用户体验：Agent 推荐自己负责的改法，不替用户推荐他们应有的感受或偏好。合并问题同样要照顾理解负担，用户要求一次一问时遵从。

上游领域建模维护术语和决策文档，分诊会操作工单；这些不进入普通反馈修订。需要续接时沿用现有任务记录，不由一次审美反馈自动生成项目治理、长期偏好或对外消息。

上游原型强调快速探索；本 Skill 保留当前任务要求的品质，尤其不能省掉正在被评价的视觉或交互，再用“临时小样”解释结果不足。说明性案例由本 Skill 编写，不是上游项目实测或用户历史原话。

## 许可与独立使用

本项目和所核对上游均为 MIT 许可，上游 [许可证](https://github.com/mattpocock/skills/blob/d81f3a183412e71a5b1e84ca21bc1a35eea03a60/LICENSE)署名为 Matt Pocock。改编部分的版权署名保留在本包 [LICENSE](LICENSE)。未把上游整套 Skill、执行流程或工具依赖复制进来；这些链接用于归属和追溯，日常使用本 Skill 不要求联网读取它们。
