---
title: "Metal Coordination Dynamics Governs Selective Epoxidation in Hyoscyamine 6β-Hydroxylase: Integrated Experimental and Computational Insights"
title_zh: 金属配位动力学调控莨菪碱 6β-羟化酶的选择性环氧化：实验与计算整合研究
authors: "Zhang, J., Wu, L., Wu, S., Liu, X., Dong, L., Wenger, E. S., Chen, R., Krebs, C., Silakov, A., Bollinger, J. M., Zhou, J., Wang, B."
date: 2026-06-03
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.01.729211v1.full.pdf"
tags: ["query:caos-poly"]
score: 9.0
evidence: 分子动力学与QM/MM计算为实验选择性提供了因果解释
tldr: Fe(II)/2OG酶催化多样C-H活化，但选择性机理未完全阐明。本研究对莨菪碱6β-羟化酶（H6H）进行分子动力学与QM/MM计算，解析其连续羟化和环氧化的机制。发现铁中心配位动力学从直线型转向非直线型，促进环氧形成而抑制羟基反弹。L290位阻效应进一步抑制羟基反应，构成双向调控。该发现确立了金属配位动力学在选择性C-H官能团化中的核心作用。
source: biorxiv
selection_source: fresh_fetch
motivation: 铁(Ⅱ)/2-酮戊二酸依赖酶的选择性控制机制不完全清楚，尤其羟基化与替代转化间选择。
method: 联合分子动力学模拟及QM/MM计算研究莨菪碱6β-羟化酶（H6H）催化机理。
result: 铁配位动力学切换促使环氧环化而非羟基反弹，L290位阻抑制羟基化，构成双向调控。
conclusion: 金属配位动力学是决定H6H选择性环氧化的关键因素，为酶设计提供新视角。
---

## 摘要
铁(II)/2-酮戊二酸依赖型(Fe(II)/2OG)酶催化广泛的C-H键活化和官能团化反应，在生物合成和代谢调控中发挥关键作用。尽管机理研究广泛，但控制典型羟化反应与其它转化途径之间选择性的原理仍不完全清楚。本文研究了莨菪碱 6β-羟化酶(H6H)的催化机制，这是一种Fe(II)/2OG依赖的加氧酶，依次催化莨菪碱的6β-羟化以及随后6β-羟基莨菪碱的6,7-外式环氧化，生成东莨菪碱。分子动力学与QM/MM联合计算揭示，一个线型Fe(IV)-氧中间体引发底物C7位氢原子攫取。产生的Fe(III)-OH物种随后使底物羟基去质子化，该过程伴随底物配位于铁中心以及Fe(III)-OH部分从线型到偏离线型的重排。这一配位动力学机制得到了在同一底物上观察到的氯代反应活性的进一步支持。重要的是，这种配位转换有利于环氧化物形成而非羟基回弹，从而将反应导向选择性环氧化。对L290F变体的进一步计算分析表明，L290施加的空间位阻约束对于抑制羟化至关重要，揭示了一种调控环氧化/羟化选择性的双向调节机制。铁配位动力学促进环氧化反应活性，而精确的底物定位和蛋白来源的空间效应则抑制竞争性的羟化途径。这些发现与现有的实验观察一致，并确立了金属配位动力学是决定Fe(II)/2OG酶中C-H官能团化选择性的关键因素。

## Abstract
Iron(II)- and 2-oxoglutarate-dependent (Fe(II)/2OG) enzymes catalyze a wide range of C-H bond activation and functionalization reactions and play essential roles in biosynthesis and metabolic regulation. Despite extensive mechanistic studies, the principles governing selectivity between canonical hydroxylation and alternative transformations remain incompletely understood. Here, we investigate the catalytic mechanism of hyoscyamine 6{beta}-hydroxylase (H6H), a Fe(II)/2OG-dependent oxygenase that sequentially catalyzes the 6{beta}-hydroxylation of hyoscyamine followed by 6,7-exo-epoxidation of 6{beta}-hydroxyhyoscyamine to generate scopolamine. Combined molecular dynamics and QM/MM calculations reveal that an inline Fe(IV)-oxo intermediate initiates hydrogen atom abstraction from the substrate C7 position. The resulting Fe(III)-OH species subsequently deprotonates the substrate hydroxyl group in a process coupled to substrate coordination to the iron center and an in-line-to-off-line rearrangement of the Fe(III)-OH moiety. This coordination dynamics machinery is further supported by the observed chlorination reactivity on the same substrate. Importantly, this coordination switch favors epoxide formation over hydroxyl rebound, thereby directing the reaction toward selective epoxidation. Further computational analysis of the L290F variant demonstrates that steric constraints imposed by L290 are essential for suppressing hydroxylation, revealing a bidirectional regulatory mechanism governing epoxidation/hydroxylation selectivity. Whereas iron coordination dynamics promote epoxidation reactivity, precise substrate positioning and protein-derived steric effects suppress the competing hydroxylation pathway. These findings are consistent with available experimental observations and establish metal coordination dynamics as a key determinant of selective C-H functionalization in Fe(II)/2OG enzymes.

---

## 论文详细总结（自动生成）

# 论文总结：《金属配位动力学调控莨菪碱 6β-羟化酶的选择性环氧化：实验与计算整合研究》

## 1. 核心问题与整体含义
- **研究背景**：铁(II)/2-酮戊二酸依赖型(Fe(II)/2OG)酶可催化多种C-H键活化反应，但控制典型羟化与其他反应路径（如环氧化）之间选择性的分子原理仍不清楚。
- **研究对象**：莨菪碱 6β-羟化酶(H6H)是一种能连续催化羟化和环氧化的Fe(II)/2OG酶，其第二环氧化反应的选择性机制是理解该酶类功能分化的关键模型。
- **整体目标**：揭示H6H如何以高选择性完成6,7-外式环氧化而非羟基回弹，从金属配位动力学和蛋白环境两个维度阐明选择性的双向调控机制。

## 2. 方法论
- **技术路线**：联合分子动力学(MD)模拟与量子力学/分子力学(QM/MM)计算。
- **核心计算流程**：
  - 构建H6H-底物-铁中心复合物的全原子模型，通过经典MD采样构象空间；
  - 在关键反应步骤上设置QM区（包含铁中心、底物、关键残基），用QM/MM处理电子结构变化；
  - 从线型Fe(IV)=O中间体出发，模拟C7位氢原子攫取反应，得到Fe(III)-OH物种；
  - 追踪Fe(III)-OH的去质子化过程和铁配位几何从直线型到非直线型的重排（配位动力学转换）；
  - 计算不同路径（环氧化 vs. 羟基回弹）的自由能势垒，解析L290位点的空间位阻效应（通过L290F变体模拟）。
- **核心思想**：铁中心配位动力学的“开关”行为促进环氧环化；蛋白残基L290提供的空间约束则抑制竞争性羟化，形成双向调控。

## 3. 实验设计（计算模拟设计）
- **体系构建**：H6H野生型及其L290F变体分别与底物6β-羟基莨菪碱复合。
- **对比分析**：
  - 野生型反应路径 vs. L290F突变体路径；
  - 环氧化路径 vs. 羟基回弹路径的自由能对比；
  - 铁配位状态的线型/非线型转换及其对后续反应的影响。
- **实验证据支撑**：文中提到“观察到的氯代反应活性”进一步支持配位动力学机制，表明底物配位模式与铁中心化学性质的内在联系。
- **基准/比对方法**：未提及与其他计算方法的系统比较，属机理驱动型研究，不涉及method benchmark。

## 4. 资源与算力
- **文中明确信息**：提供的摘要及元数据未报告计算所用的GPU型号、数量、机时等资源信息。
- **可能情况**：通常此类QM/MM研究需高性能计算集群，但具体算力消耗无法从现有文本获知。读者需留意预印本可能在正文中补充了算力细节，但基于本次分析材料，该信息缺失。

## 5. 实验数量与充分性
- **模拟组数估计**：至少涉及野生型与L290F变体两条主要反应路径，每条路径又包含氢攫取、去质子化/配位转换、环化/回弹等多个基元步骤的自由能计算；可能还进行了MD采样、构象分析、氯代反应活性对应的模拟等。
- **充分性判断**：从摘要论证逻辑看，模拟工作覆盖了反应全部关键步骤，并引入定点突变验证空间位阻效应，从而构建了完整的因果关系链，设计充分且具有因果解释力。
- **客观性/公平性**：无对比其他计算方法，不涉及方法间公平性问题；突变体对比仅针对自身酶活性调控，客观性较高。

## 6. 主要结论与发现
- **配位动力学开关**：Fe(IV)=O攫氢后生成的Fe(III)-OH发生从线型到偏离线型的配位重排，促进底物羟基去质子化并配位于铁，这一动力学转换有利于环氧化物形成，而非羟基回弹。
- **双向调控机制**：
  - **正向驱动**：铁配位动力学本身推动环氧化反应活性；
  - **反向抑制**：L290侧链的空间位阻有效抑制羟化途径（L290F突变削弱抑制，改变选择性）。
- **普适性暗示**：金属配位动力学可能是Fe(II)/2OG酶选择性C-H官能团化的一个广泛适用的决定因素，为酶定向设计提供新靶点。

## 7. 优点
- **机制解释深度**：首次将铁中心配位几何的动力学变化与环氧化/羟化选择性直接关联，超越静态结构分析。
- **整合计算证据**：结合自由能计算、突变体模拟及实验线索（氯代反应），构建了多层次的证据链。
- **概念创新**：提出“促进一侧、抑制另一侧”的双向调控逻辑，对酶的选择性机制给出了更完整的描述。
- **可转化价值**：结论对Fe(II)/2OG酶的设计改造具有指导意义，强调了金属中心动力学和远处残基空间效应的协同。

## 8. 不足与局限
- **计算细节缺失**：本次分析仅基于摘要，缺乏QM方法、基组、力场、采样时长、自由能计算方法等技术细节，无法评价计算的精度与收敛性。
- **缺乏实验直接验证**：虽引用了氯代反应活性作为支撑，但关键配位动力学重排的瞬时中间体尚未获谱学直接捕捉，L290F变体的环氧化/羟化选择性改变也未给出实验数据（如果预印本正文中无，则属推断）。
- **底物普适性未知**：研究仅聚焦于H6H及其天然底物，该调控机制是否适用于其他Fe(II)/2OG环氧酶或羟化酶有待拓展。
- **动力学定量缺失**：摘要未提及反应速率常数或动力学同位素效应等计算比较，限制定量预测能力。
- **预印本状态**：未经历同行评审，结论的稳健性需后续验证。

（完）
