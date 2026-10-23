# 参考资料与归纳边界

本技能以两本设计书中的通用原则为基础，结合公开 UI 实践与交互设计案例，将其转化为网页、应用和信息排版任务中的执行方法。这里列出可核对的公开材料，**不宣称复现或替代全书，也不完整转录他人的提示词**。

## 书籍

1. Steve Krug, *Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability*, 3rd edition, New Riders, 2014.
2. Robin Williams, *The Non-Designer's Design Book*, 4th edition, Peachpit Press, 2014（中译常称《写给大家看的设计书》）。

## 公开参考

### Steve Krug

- [Don't Make Me Think, Revisited — 官方公开样章 (PDF)](https://www.peachpit.com/content/images/9780321965516/samplepages/0321965515.pdf)：用户面对界面的疑问、选择成本和点击的代价。
- [Peachpit 作者文章：Don't Make Me Think](https://www.peachpit.com/articles/article.aspx?p=2209309)：清晰命名和减少无谓猜测。
- [Peachpit 作者文章：Visual Hierarchy](https://www.peachpit.com/articles/article.aspx?p=2209310)：用视觉呈现重要性、相似性和包含关系。
- [Peachpit 作者文章：Usability Testing](https://www.peachpit.com/articles/article.aspx?p=2209313)：通过观察实际任务而非猜测来检验理解。

### Robin Williams

- [The Non-Designer's Design Book — 第四版公开预览 (PDF)](https://api.pageplace.de/preview/DT0400.9780133966336_A23586692/preview-9780133966336_A23586692.pdf)：亲密性、对齐、重复、对比原则。
- [Peachpit 作者文章：Repetition](https://www.peachpit.com/articles/article.aspx?p=2268752)：一致的设计语言与有意义的变化。
- [O'Reilly 第四版目录／排版章节](https://www.oreilly.com/library/view/the-non-designers-design/9780133966350/ch12.html)：字体的对比、沟通和组织作用。

上述链接指向出版方、作者文章或正式预览；访问权限与可见章节可能随时间变化。

### ZaynHao 的 UI 实践

| 原始材料 | 本技能参考的方向 |
| --- | --- |
| [十条 UI 优化提示词](https://x.com/ZaynHao/status/2113456751915982917) | 文案、色彩、光学对齐、边框、字号与动效打磨 |
| [对调整效果的后续说明](https://x.com/ZaynHao/status/2113482619480690729) | 修改后仍需检查实际结果 |
| [Radix Colors 及用途规范](https://x.com/ZaynHao/status/2049479990815883639) | 按使用场景组织颜色 |
| [基础 UI 样板与交付](https://x.com/ZaynHao/status/2052401033163530289) | 用具体样板帮助明确设计 |
| [推荐 Honkish](https://x.com/ZaynHao/status/2090273807080763719) | 探索有个性、打破常规的交互细节 |
| [键盘列表的边缘滚动](https://x.com/ZaynHao/status/2112860503064400268) | 连续导航中保留相邻内容与空间线索 |
| [清理结果预览](https://x.com/ZaynHao/status/2085693981279895592) | 在执行前呈现预计影响 |
| [窗口截图的上下文指针](https://x.com/ZaynHao/status/2073403169489764506) | 反馈同时表达目标对象与动作 |
| [Tooltip 的首次与连续触发](https://x.com/ZaynHao/status/2072607944651477447) | 按交互阶段安排节奏，不固定沿用延迟参数 |
| [倍率调节的操作隐喻](https://x.com/ZaynHao/status/2099412560865087806) | 从当前操作寻找可理解的表达方式 |
| [复用精调实现](https://x.com/ZaynHao/status/2089899297773154653)、[设置页样板](https://x.com/ZaynHao/status/2111682049937670388) | 让 AI 参考已认可的真实实现，再迁移同类规则 |
| [图标的手调与迭代](https://x.com/ZaynHao/status/2098409274041114656) | 对生成结果继续作具体修正 |
| [可亲自操作的产品展示](https://x.com/ZaynHao/status/2076591004568920301) | 实际操作提供静态画面之外的证据 |
| [案例拆解](https://x.com/ZaynHao/status/2086713248716632483)、[设计讨论的重要性](https://x.com/ZaynHao/status/2054866581382139934) | 关注设计决定的理由，不把时间比例变成流程规定 |

**材料范围（2026-10-23）**：通过搜索引擎对原始 X 页面的索引核对可见片段；X 正文直接读取受限，未完整核验各帖全文、配图或视频。只采用能识别为主帖的内容，不将混入搜索摘要的回复当作作者观点。表中方向包含本技能的应用推导，不是逐字转录，也不据未观看的视频判断时序、手感或实现质量。

个人经验中的特定颜色库、字号数量、边框粗细、动画参数和设计讨论时间比例不作为本技能的通用硬标准。条件、例子、例外与停止规则是本仓库为实际任务作出的整理。

作者长文：[使 PWA 更像 Native App 的 6 个技巧](https://fehey.com/5-pwa-tips)（页面日期 2021-11-18）。已读取正文，参考其区分浏览器与独立应用场景的思路；不将文中的全局禁选、清空标题或替换导航历史作为通用要求，具体实现需按当前平台重新核验。

### Benji Taylor：Honkish

- [Honkish](https://benji.org/honkish)（2025-05-23）：作者从在场感、趣味与细节回顾 Honk 的设计，作为情感表达和情境反馈的案例来源。

已读取文章正文，未观看其演示视频。它是设计回顾，不是通用效率或留存结论。允许趣味作为体验目标、从已有动作发展个性，以及连续输入、取消和降级检查，是本技能结合案例与工程要求的应用推导；不要求复制 Honk 的聊天机制或新增玩法。

### 技术核对

- [Radix Colors — Understanding the scale](https://www.radix-ui.com/colors/docs/palette-composition/understanding-the-scale)：核对十二阶颜色的用途划分及例外。采用色阶不等于任意前景、背景组合都符合可读性要求。

## 原则对应

| 技能内容 | 主要依据 | 说明 |
| --- | --- | --- |
| 额外疑问、扫读、选择、删减无效文字 | Krug | 强调用户对名称、位置、操作、结果的理解 |
| 亲密性、对齐、重复、对比 | Williams | 强调视觉关系与信息组织 |
| 用视觉表达重要性、相似性与包含关系 | Krug + Williams | 两本书的交集 |
| 最小改动、保留密集信息、不默认新增功能 | 应用推导 | 为现代产品开发及评审增加的范围约束 |
| 截图、运行、真实任务观察分级 | 应用推导 | 避免把主观推测当成用户研究结论 |
| 参考转化、视觉方向、按任务选择改动幅度 | 应用推导 | 支持新设计与明确授权的视觉改稿，不扩大产品范围 |
| 光学对齐、颜色角色、字号与动效收敛 | ZaynHao 公开索引片段 + 应用推导 | 将实践提示改写为有使用条件的打磨方法 |
| 结果预览、对象附近反馈、空间上下文与阶段节奏 | ZaynHao 交互案例 + 应用推导 | 从当前动作及状态判断，不照搬特定控件 |
| 趣味、情感回应与体验性格 | Honkish + ZaynHao 推荐 + 应用推导 | 可成立的设计目标，按情境取舍 |
| 读取成熟样板、代表性区域与具体迭代 | ZaynHao 实践 + 应用推导 | 复用已成立的规则，不预建全套系统 |
| Radix 颜色阶用途 | Radix 官方文档 | 技术示例，可选用，不要求替换现有配色体系 |

## 使用边界

- 不将“减少思考”解释成禁止用户分析业务问题；要减少的是界面额外产生的困惑。
- 不将“更少点击”作为无条件的衡量标准；还要考虑每一步的不确定性、等待与返工。
- 不将“精简”理解为省略必要标签、信息与风险提示。
- 不将四项视觉原则理解为单一视觉风格；相关内容可以变化，品牌特征可以保留。
- 不把趣味等同于低效，也不把“有趣”变成所有页面必须增加动画、声音或新功能的要求。
- 本技能中的场景示例、工作流程和输出格式是重新组织的设计实践，不是上述作者的原文或官方认证标准。
- 日常执行无需重新检索书籍或推文；涉及具体库、平台行为与标准时，再核对相应一手文档。

**版权说明**：本仓库仅包含原创总结、条件化方法及公开参考链接，不包含书籍正文的连续摘录或完整推文搬运。
