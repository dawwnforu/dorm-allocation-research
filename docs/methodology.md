# 研究方法与证据范围 / Methods and evidence

## 当前可复核的分析

研究对象为本科生宿舍生活，原问卷以重庆大学本科生为目标人群。问卷有 50 个题号，包括单选、多选、排序、数字填空及开放题。一个题号可能对应多个导出列，题号不能直接当作 Excel 列号使用。

本版使用 58 份问卷星原始导出记录。57 份旧导出与 58 份新导出的前 57 行一致，不能相加为 115 份。110 行整理表并非独立验证的新一轮回收，新增记录来源有待核实，因此不参与本版统计。

处理流程：原问卷选项 → 导出列核查 → 逐题有效值与跳转检查 → 全样本频数和比例 → 近期体验均值及中位数 → 汇总图表。数据复算脚本与来源映射保存在私有研究仓库，公开版不附原始数据。

| 题号 | 变量 | 正确口径 |
| --- | --- | --- |
| Q10 | 调宿或外出租房想法 | 编码 1=从未，2=偶尔，3=经常，4=已行动；展示合并 2—4，N=58 |
| Q20 | 冲突处理方式 | 1=主动沟通，2=等待对方或冷处理，3=向辅导员或宿管求助，4=避免正面冲突但保留不满 |
| Q21 | 关系总体评价 | 从非常融洽到很差递增，不能把高分解释为关系更好 |
| Q13 / Q15 / Q18 | 近期体验 | 仅对符合住宿状态条件的回答计算，n=56；跳转空值不置为零，也不因此删除整份记录 |
| Q39 | 分配需求 | 多选，每个选项以全部 58 份有效二元回答为分母；仅展示作息和安静学习两项 |
| Q46 | 学校改善方向 | 多选，每个选项均以 N=58 为分母；比例不相加为 100% |
| Q41 | 室友选择排序 | 原题有六项，包括“其他”；排名 6 本身不是越界，本版不沿用旧清洗结果 |

原 Q40 是七类睡眠与声音接受情境，不能未经论证地当作等距敏感度量表。Q43 是原始自编角色分类，不能直接解释为标准 MBTI 测量。

## 历史探索与当前展示的区别

保留的历史脚本涉及交叉表、相关检验、组间比较、效应量、聚类、回归、中介及信效度探索。这些是项目曾经探索的分析路径，其数据来源与部分编码存在问题，结果未被当前复核确认。因此公开发现只使用描述统计，不将历史显著性、聚类有效性或中介结果列为已证实成果。

后续角色问答原型与原调查不是同一套测量工具。它的题目与角色映射是设计探索，不能反向赋予原问卷心理测量效度。

## 局限

- 抽样与招募的实际执行记录不足，历史材料同时出现便利、系统和分层随机抽样表述，不能据此确认概率抽样。
- 单一学校、小样本、自愿填答和自我报告限制外推；本版不估算全校或全国比例。
- 时间窗口、题意及跳转规则不同，不能混用分母，也不能把调宿想法等同实际行为。
- 无纵向对照或真实分配效果记录，不支持因果推断。
- 开放建议仅用于归纳设计主题，未宣称完成独立编码、饱和度分析或正式访谈研究。

## English summary

This showcase uses descriptive analysis of one traceable 58-record export. Question labels and response codes were checked against the original questionnaire. Overall proportions use 58 responses; conditional recent-experience items use 56 valid responses. Missing routed answers are neither imputed as zero nor used to discard an entire questionnaire.

The earlier 57-record export is a subset, not another sample. A separate 110-row working file has unresolved provenance. Historical inferential and clustering analyses remain archived explorations rather than verified findings. Recruitment documentation does not establish a probability sample, and no causal or intervention-effect claim is made.
