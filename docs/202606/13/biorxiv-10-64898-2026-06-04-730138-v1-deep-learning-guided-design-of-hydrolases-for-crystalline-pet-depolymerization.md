---
title: Deep learning-guided design of hydrolases for crystalline PET depolymerization
title_zh: 深度学习引导的聚酯水解酶设计以实现结晶PET解聚
authors: "Wu, B., Li, M., Zhang, J., Li, J., Wang, X., Zhong, B., Liu, J., Wang, B., Tan, Y., Qi, W., Tan, P., Zhao, W., Zheng, L., Hong, L."
date: 2026-06-05
pdf: "https://www.biorxiv.org/content/10.64898/2026.06.04.730138v1.full.pdf"
tags: ["query:caos-poly"]
score: 6.0
evidence: 深度学习指导水解酶设计用于PET解聚，属于催化剂骨架的虚拟筛选
tldr: "聚对苯二甲酸乙二醇酯（PET）塑料污染严重，酶法回收受限于结晶结构导致的低效降解。本研究利用深度学习框架PET-Flow设计出VenusPETase，其水解活性提升3.4倍、热稳定性提高12°C，可在50°C下高效降解结晶度8%–50%的PET，产物中TPA占比超95%。在100 L反应器中24小时完全解聚消费后PET，实现闭环回收，为温和条件处理结晶PET提供了高性能生物催化剂。"
source: biorxiv
selection_source: fresh_fetch
motivation: 现有PET水解酶对结晶PET降解效率低、需高耗能预处理，且热稳定性差、中间产物积累，制约工业应用。
method: 基于PET-Flow计算框架对KbPETase进行深度学习指导的工程改造，获得变体VenusPETase。
result: "VenusPETase活性提升3.4倍，热稳定性提高12°C，降解宽结晶度PET，TPA产率>95%，并在100 L规模24小时完全解聚消费后PET。"
conclusion: VenusPETase在温和条件下实现结晶PET高效闭环回收，为塑料循环经济提供了可行方案。
---

## 摘要
聚对苯二甲酸乙二醇酯（PET）是一种广泛用于包装和纺织品的聚酯，因其高结晶度和稳定性而持久存在于环境中，是导致全球塑料污染的重要因素。PET水解酶（PETase）酶法解聚为将PET转化为其单体结构单元提供了一种化学精确且环境可持续的途径，从而实现回收利用。然而，实际应用仍面临阻碍，因为PET的刚性结晶结构限制了酶的接触，并需要进行能源密集型的预处理才能实现高效解聚。此外，大多数PETase仅能实现部分解聚，对苯二甲酸（TPA）产率低，并积累抑制性中间产物，而有限的热稳定性和缓慢的表面动力学进一步限制了效率。为了克服这些障碍，我们报道了VenusPETase，这是一种利用PET-Flow（一种先进的PETase工程计算框架）设计的KbPETase工程变体。与KbPETase相比，VenusPETase的水解活性提高了3.4倍，蛋白质热处理后最高提升27倍，热稳定性提高了12摄氏度。VenusPETase在50摄氏度下能在广泛的结晶度范围（8%-50%）内快速降解，有效覆盖了所有商业PET产品。此外，VenusPETase在各自最佳条件下优于九种高性能PETase，降解了结晶度从8%到50%的未处理PET底物，产生的释放产物中TPA占比超过95%，且中间产物积累极少。X射线晶体学和分子动力学模拟表明，动态调节和升高的表面静电势增强了VenusPETase与结晶PET的相互作用，从而降低了水解能垒并提高了催化性能。我们还展示了来自九种不同产品的未处理消费后PET均可被VenusPETase降解。回收的单体可以直接重新聚合成原生质量的PET，展示了一个闭环的酶法回收过程。在100升生物反应器中，VenusPETase在50摄氏度下24小时内完全解聚了消费后结晶PET（结晶度28%）。这些结果确立了VenusPETase作为一种强大的生物催化剂，能够在温和条件下实现结晶PET的高效闭环回收。

## Abstract
Poly(ethylene terephthalate) (PET), a ubiquitous polyester used in packaging and textiles, persists in the environment due to its high crystallinity and stability, contributing substantially to global plastic pollution. Enzymatic depolymerization by PET hydrolase (PETase) offers a chemically precise and environmentally sustainable route to convert PET into its monomeric building blocks, enabling recycling. However, practical implementation remains hindered by the rigid, crystalline architecture of PET, which restricts enzyme access and necessitates energy-intensive pretreatment to enable efficient depolymerization. In addition, most PETases achieve only partial depolymerization with low terephthalic acid (TPA) yields and accumulate inhibitory intermediates, while limited thermostability and slow surface kinetics further restrict efficiency. To overcome these barriers, we report VenusPETase, an engineered variant of KbPETase designed using PET-Flow, a state-of-the-art computational framework for PETase engineering. Compared with KbPETase, VenusPETase exhibits a 3.4-fold increase in hydrolytic activity, up to a 27-fold improvement after heat treatment of protein, and a 12 {degrees}C enhancement in thermostability. VenusPETase exhibits rapid degradation across a wide crystallinity range (8%-50%) at 50 {degrees}C, effectively spanning the entire spectrum of commercial PET products. Moreover, VenusPETase outperformed nine high-performance PETases under their respective optimal conditions and degraded untreated PET substrates across 8%-50% crystallinity, producing TPA as over 95% of the released products with minimal intermediate accumulation. X-ray crystallography and molecular dynamics simulations suggest that dynamic modulation, elevated surface electrostatic potential enhance the interaction of VenusPETase with crystalline PET, thereby lowering the hydrolytic energy barrier and improving catalytic performance. We also demonstrate that untreated, postconsumer-PET from nine different products can all be degraded by VenusPETase. The recovered monomers can be directly repolymerized into virgin-quality PET, demonstrating a closed-loop enzymatic recycling process. In a 100 L bioreactor, VenusPETase completely depolymerizes post-consumer crystalline PET (28% crystallinity) within 24 h under 50 {degrees}C. These results establish VenusPETase as a robust biocatalyst that enables efficient, closed-loop recycling of crystalline PET under mild conditions.