# 约翰·斯图亚特·穆勒：原版女娲独立研究补证

研究补证；不评分，不授予A级，不等于全集完成

2026-10-13。默认中性思想；独立可选表达只在用户明确选择时启用，文游禁文风。未改canonical；未读答题与评分结果。

## 覆盖与未读
- **On Liberty（1859）**：继承I188–232、II245–262、III509–524、V765–798及805–834选段；未读：全书未通读；IV及帝国例外语境未系统补足。
- **Utilitarianism（1861/1863）**：继承II94–106、IV266–288；本轮长度限定抽样20段逐段查看，跨I–V但不等于全章连续阅读；未读：未列各章段落、原版页影校勘。
- **The Subjection of Women（1869）**：本轮I网页92–133连续段，原版显示pp.16–28附近；未读：I其他部分及II–IV。
- **Autobiography / Auguste Comte and Positivism（1873 / 1865）**：继承自传V危机回顾与论孔德Part II674–694；未读：完整逻辑学、政治经济学、议会及通信。

标为继承的范围来自已读本地来源目录及10/11记录，不宣称本轮重新阅读所有原作；网页行号为工具当时定位，复核须结合章节/段落指纹。

## 本轮连续原作补证
- [I网页92–133；段首If people are mostly...至formation of character](https://www.gutenberg.org/files/27083/27083-h/27083-h.htm)：习惯的持续不能证明正当；女性表面同意须放回权力、教育、依赖与公开异议条件。 边界：论证为特定19世纪制度批判；不以女性沉默推出每个人实际愿望，历史细节非本轮独立史实查证。

## 逐项三验证审查（不打分）

### 规范边界
- 公共言论/竞争：[定位](https://www.gutenberg.org/files/34901/34901-h/34901-h.htm) III开头及V既读选段；损失与强制理由非同一。
- 婚姻与性别制度：[定位](https://www.gutenberg.org/files/27083/27083-h/27083-h.htm) I92–133；依赖与训练影响所谓自愿接受的证据。
跨域：新著作扩至性别制度，可支持检验同意条件；不能把它直接称同一伤害原则的完整演绎。
生成力：可对“有同意即正当”作条件审查；未独立测试。 独立测试未完成。
区分度：将强制理由、个人发展及同意形成条件一起审查，比任意自由口号具体。
地位：保留有限程序；未完成三重独立验证。

### 异议检查
- 公众思想争论：[定位](https://www.gutenberg.org/files/34901/34901-h/34901-h.htm) II既读245–262；可错性与异议作用。
- 性别制度中异议可见性：[定位](https://www.gutenberg.org/files/27083/27083-h/27083-h.htm) I120–128；公开抗议及无从知道的沉默，不能以未反抗证明赞同。
跨域：公共认识与制度压制下的证言两域形成局部相互支持，尚缺完整方法同一性论证。
生成力：可询问反对意见是否有真实表达条件；这是现代操作化。 独立测试未完成。
区分度：异议为认识和发展条件；不要求不同证据强度的说法获得相同权重。
地位：保留有限程序；未完成三重独立验证。

### 幸福比较
- 伦理的快乐质差：[定位](https://www.gutenberg.org/files/11224/11224-h/11224-h.htm) II，sample p15；熟悉两者的判断者优先。
- 自我教育/精神危机：[定位](https://www.gutenberg.org/files/10378/10378-h/10378-h.htm) 无新增第二领域；旧M3自传V507–519、553–564仅回顾材料；旧自传不能充当独立验证或同一比较法直接应用。
跨域：仍不满足严密两域复现；新增V正义段不是快乐质量模型的第二域。
生成力：可生成经验资格检查；未新实测。 独立测试未完成。
区分度：质量不可由数量简单替换，但此原则不能转换成人的等级。
地位：保留有限程序；未完成三重独立验证。

## 可复核表达抽样
见可复跑脚本nuwa_a_research_2_sampler.py：固定种子20261013，HTML p序号从0起，规范化空白后取SHA256。通常仅30–180词段，故不是全文均匀抽样；所有最终选中段已在工具输出逐段实际查看。霍克海默为10个合格段的全取；奥斯汀未建立可靠分段。
实取20段；指标：`{"words": 2547, "sentences": 64, "question_sentences": 5, "first_person_tokens": 6, "contrast_tokens": 18, "mean_words_per_sentence": 39.797, "question_sentence_ratio": 0.07812, "first_person_per_1000_words": 2.356, "contrast_per_1000_words": 7.067}`。类比密度与确定性比例未计算。
逐段来源/HTML定位/指纹/原始计数见[mill-perspective-sample.json](mill-perspective-sample.json)。

可直接用于独立表达附录的高层规则：
- 把反对者理由说完整，再指出尚未证明的那一步。
- 用“即使承认……仍须……”区分论证阶段；每个原则带适用条件。
- 保留道德论证力度，但不把长串例外写成不敢判断。

反模式与边界：
- 不反复拼接自由与快乐名句。
- 不以多数欲望直接证明善，不把女性既有行为当未经塑造的自然。
- 不清洗帝国/殖民例外为当代平等主义。
- Length-restricted sampling (30–180 words), not representative of the full work; Horkheimer uses ten eligible original paragraphs without length filtering.
- Sentence boundary regex splits after punctuation; abbreviations/quoted questions may distort counts.
- First-person and contrast are lexical counts, not manually coded rhetorical intentions.
- Analogy density and certainty ratio not measured.
- Electronic transcription not collated with first-edition page images.
- 中文输出只迁移高层修辞功能，不把英法词长/词频硬套到中文。
- 统计中的第一人称可来自作者构造的示范/虚拟对话，不证明真实自述；所概述的他人观点也不是作者赞同。
- 只用于用户明确选用的独立表达附录；默认中性思想，文游禁文风。

## 两项有原作依据的张力
- 自由原则限制以本人利益进行强制；同时最终仍从广义效用及发展利益辩护原则。[原作定位](https://www.gutenberg.org/files/34901/34901-h/34901-h.htm)：I既读188–232与V既读选段，历史原典范围继承。共同要求之间的张力，非简单自相矛盾。
- 承认个人能够为他人牺牲最大利益；同时牺牲本身不因痛苦而有价值，仍问它增进谁的幸福。[原作定位](https://www.gutenberg.org/files/11224/11224-h/11224-h.htm)：II sample p27。共同要求之间的张力，非简单自相矛盾。

## 尚待完成
- 幸福质量条目第二域仍弱。
- 表达20段仅来自功利主义短中段，长度筛选显著排除了穆勒很长的论证段。
- 性别制度仅一段连续补读；帝国政策、议会活动及逻辑学仍缺。

访问：
- web.open成功；requests只读获取用于段落计数；仅保留SHA256、指标和原创笔记，不保存原作全文。

三道已知立场题均为作者实际讨论的问题；仅设计，不作答、不评分。逐题方向及来源另见proposals同名JSON。
