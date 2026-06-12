---
title: "MolDeBERTa: Foundational Model for Physicochemical and Substructure-Informed Molecular Representation Learning"
title_zh: MolDeBERTa：基于物理化学与亚结构信息的分子表征学习基础模型
authors: "de Oliveira, G. B., Saeed, F."
date: 2026-06-10
pdf: "https://www.biorxiv.org/content/10.64898/2026.02.15.706011v2.full.pdf"
tags: ["query:caos-poly"]
score: 7.0
evidence: 有益于虚拟筛选的分子表示学习模型
tldr: "传统分子语言模型依赖掩码语言建模，预训练目标与分子理化性质及结构信息脱节，导致表征偏差。MolDeBERTa 采用字节级BPE分词，并设计三项新颖预训练任务，将分子属性与子结构相似性直接注入潜在空间。在9项 MoleculeNet 基准上，回归误差最多降低16%，分类ROC-AUC提升3.0点，全面超越现有模型。该工作以大规模数据预训练，实现了数据高效的化学感知表示学习，推动分子发现领域基础模型发展。"
source: biorxiv
selection_source: fresh_fetch
motivation: 现有掩码语言模型忽略分子理化与结构特性，预训练目标通用，导致表示与物理属性存在鸿沟。
method: 提出 MolDeBERTa，采用字节级 BPE 分词，并设计三种新预训练目标注入分子性质与结构相似性偏置。
result: "在 MoleculeNet 基准上回归误差降幅达16%，分类 ROC-AUC 提升3.0点，优于现有掩码语言模型。"
conclusion: MolDeBERTa 实现数据高效化学表示学习，推进大规模无监督分子编码器发展。
---

## 摘要
学习分子语言的基础模型对于加速材料和药物发现至关重要。这些自学习模型可以在大量未标记的分子上进行训练，从而支持属性预测、分子设计（从头生成、优化）以及特定功能筛选等应用。然而，现有的分子语言模型建立在第一代Transformer架构之上，并使用掩码语言建模进行预训练，这是一种与物理化学和结构分子属性无关的通用令牌级目标。在此，我们提出了MolDeBERTa，一种结构感知的自监督分子编码器，它利用字节级字节对编码（BPE）分词策略。MolDeBERTa在PubChem中多达1.23亿个SMILES分子上进行了预训练，这是目前公开可用的最大SMILES语料库之一。为实现这一目标，我们引入了三个新颖的预训练目标，旨在将分子属性和结构相似性的强归纳偏置直接注入潜在空间，从而缩小语言化学表示与物理分子属性之间的差距。随后，我们在三种架构规模、两种数据集大小和五个不同的预训练目标下系统地研究了该模型。在9个下游MoleculeNet基准测试上的评估表明，MolDeBERTa优于现有的掩码语言模型，在回归任务上误差降低高达16%，在分类基准上ROC-AUC提高最多达3.0点。MolDeBERTa在预训练数据和下游评估方面推动了基于无监督编码器的基础模型大规模发展，实现了数据高效的化学信息表征学习。源代码公开于https://github.com/pcdslab/MolDeBERTa，Hugging Face平台位于https://huggingface.co/collections/SaeedLab/moldeberta。所有预训练数据集可在https://huggingface.co/datasets/SaeedLab/MolDeBERTa获取。

## Abstract
Foundational models that learn the language of molecules are essential for accelerating the material and drug discovery. These self-learning models can be trained on a large number of unlabelled molecules, enabling applications like property prediction, molecule de-sign (de novo generation, optimization), and screening for specific functions. However, existing molecular language models are built upon first-generation transformer architectures and are pretrained using masked language modeling, a generic token-level objective that is agnostic to physicochemical and structural molecular properties. Here we introduce MolDe-BERTa, a structure-informed self-supervised molecular encoder that leverages a byte-level Byte-Pair Encoding (BPE) tokenization strategy. MolDeBERTa is pretrained on up to 123 million SMILES molecules from PubChem, representing one of the largest publicly available SMILES-based corpora. To achieve this, we introduce three novel pretraining objectives designed to inject strong inductive biases for molecular properties and structural similarity directly into the latent space, resulting in reduced gap between linguistic chemical representations and physical molecular properties. The model was then systematically investigated across three architectural scales, two dataset sizes, and five distinct pretraining objectives. MolDeBERTa when evaluated on 9 downstream MoleculeNet benchmarks outperformed existing masked language models, achieving up to a 16% reduction in regression error and improvements of up to 3.0 ROC-AUC points on classification benchmarks. MolDeBERTa advances unsupervised encoder-based foundational models at scale both for pretraining data and downstream evaluation, enabling data-efficient chemistry-informed representation learning. The source code is publicly available at https://github.com/pcdslab/MolDeBERTa, and Hugging Face at https://huggingface.co/collections/SaeedLab/moldeberta. All the pretraining datasets are available at https://huggingface.co/datasets/SaeedLab/MolDeBERTa