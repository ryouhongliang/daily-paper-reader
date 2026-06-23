---
title: "RetroMol: Parsing a shared encoding from natural products and their biosynthetic gene clusters"
title_zh: RetroMol：从天然产物及其生物合成基因簇中解析共享编码
authors: "Meijer, D., Williams, S. E., Terlouw, B., Charusanti, P., Kok, L., Skinnider, M. A., Weber, T., van der Hooft, J. J. J., Healy, A. R., Medema, M. H."
date: 2026-06-16
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.12.731935v1.full.pdf"
tags: ["query:caos-poly"]
score: 7.0
evidence: 解析天然产物结构及其生物合成基因簇，辅助计算辅助有机合成。
tldr: 天然产物（如聚酮和非核糖体肽）及其编码生物合成基因簇（BGCs）缺乏联合描述的统一语言。为此，提出一种基于序列的表示——primary sequences，桥接化学结构与BGCs。开发RetroMol算法，将天然产物或BGCs解析为primary sequences，支持基于生物合成相似性的化合物与基因簇检索。通过重新发现nocardichelin B BGC及发现结构不相似但生物合成相近的化合物对，证明了统一编码在天然产物比较与BGC优先排序中的价值。
source: biorxiv
selection_source: fresh_fetch
motivation: 天然产物与BGCs分属不同数据模态，缺乏统一的生物化学描述语言，限制了联合检索与分析。
method: 开发RetroMol算法，将天然产物与BGCs解析为primary sequences。
result: 实现了基于相似性的检索，重新发现nocardichelin B BGC，并展示多对结构不相似但生物合成相近的化合物。
conclusion: Primary sequences提供了天然产物与BGC的统一描述，可用于相似性比较和BGC优先排序。
---

## 摘要
天然产物如聚酮和非核糖体肽是生物活性化合物的重要来源，包括许多抗生素。它们多由模块化酶复合体组装，并通过生物合成基因簇编码的后修饰和多样化反应进一步修饰。尽管天然产物及其编码的BGCs描述了同一生化过程的不同数据模态，但缺乏一种统一的语言来共同描述其生化过程。我们在此引入一种基于序列的模块化天然产物核心生物合成的表示方法，称为初级序列，它连接了化学结构和BGCs。我们还呈现了RetroMol算法，该算法将天然产物结构或其编码的BGCs解析为天然产物构建块的初级序列。RetroMol允许在天然产物和BGCs之间进行相似性评分，从而能够基于生物合成相似性检索化合物、BGCs以及二者的组合。例如，可用于检索生物合成相似但结构不相似的化合物，或在大型实验数据集中将天然产物链接到候选编码BGCs。我们通过重新发现nocardichelin B BGC作为原理验证，展示了后者。我们还通过展示各种低结构相似性的生物合成相似化合物对，举例说明了生物合成相似性的实用性。这些结果共同确立了初级序列作为天然产物比较和BGC优先化的共享生物合成编码。

## Abstract
Natural products such as polyketides and nonribosomal peptides (NRPs) are important sources of bioactive compounds, including many antibiotics. Many of them are assembled by modular enzyme complexes and further modified and diversified by tailoring reactions encoded by biosynthetic gene clusters (BGCs). Although natural products and their coding BGCs describe different data modalities of the same biochemical process, a unified language to jointly describe their biochemistry is lacking. Here we introduce a sequence-based representation of the core biosynthesis of modular natural products, which we call primary sequences, that bridges chemical structures and BGCs. We also present RetroMol, an algorithm that parses either natural product structures or their encoding BGCs into their primary sequences of natural product building blocks. RetroMol allows for similarity scoring between natural products and BGCs, enabling the retrieval of compounds, BGCs, and a combination of the two, based on their biosynthetic similarity. This can, for instance, be used to retrieve biosynthetically similar but structurally dissimilar compounds, or link natural products to candidate coding BGCs in large experimental datasets. We demonstrate the latter by rediscovering the nocardichelin B BGC as a proof of principle. We also exemplify the utility of biosynthetic similarity by showing various pairs of biosynthetically similar compounds with low structural similarity. Together, these results establish primary sequences as a shared biosynthetic encoding for natural product comparison and BGC prioritization.