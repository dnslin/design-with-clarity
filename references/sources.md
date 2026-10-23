# 参考资料与归纳边界

本技能以两本设计书中的通用原则为基础，结合公开 UI 打磨经验，将其转化为网页、应用和信息排版任务中的执行方法。这里列出可核对的公开材料，**不宣称复现或替代全书，也不完整转录他人的提示词**。

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

- [十条 UI 优化提示词](https://x.com/ZaynHao/status/2113456751915982917)：参考其中可核实的文案、色彩规范、光学对齐、边框、字号与动效打磨方向。
- [对调整效果的后续说明](https://x.com/ZaynHao/status/2113482619480690729)：作者展示尝试后的界面，并说明仍有改善空间；用于提醒执行者检查实际结果。
- [Radix Colors 及用途规范](https://x.com/ZaynHao/status/2049479990815883639)：参考按颜色使用场景约束选择的思路。
- [基础 UI 样板与交付](https://x.com/ZaynHao/status/2052401033163530289)：参考用基础样板帮助明确设计的思路。

**材料范围（2026-10-23）**：本次修订通过搜索引擎对原始 X 页面的索引核对可见片段；X 正文直接读取受限，未完整核验全文与配图。只将可核实的内容作为灵感来源，不把未见内容、第三方转录或本技能的推导写成作者的逐字主张。

个人经验中的特定颜色库、字号数量、边框粗细和动画参数不作为本技能的通用硬标准。条件、例子、例外与停止规则是本仓库为实际任务作出的整理。

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
| Radix 颜色阶用途 | Radix 官方文档 | 技术示例，可选用，不要求替换现有配色体系 |

## 使用边界

- 不将“减少思考”解释成禁止用户分析业务问题；要减少的是界面额外产生的困惑。
- 不将“更少点击”作为无条件的衡量标准；还要考虑每一步的不确定性、等待与返工。
- 不将“精简”理解为省略必要标签、信息与风险提示。
- 不将四项视觉原则理解为单一视觉风格；相关内容可以变化，品牌特征可以保留。
- 本技能中的场景示例、工作流程和输出格式是重新组织的设计实践，不是上述作者的原文或官方认证标准。
- 日常执行无需重新检索书籍或推文；涉及具体库、平台行为与标准时，再核对相应一手文档。

**版权说明**：本仓库仅包含原创总结、条件化方法及公开参考链接，不包含书籍正文的连续摘录或完整推文搬运。
