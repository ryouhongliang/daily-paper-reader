---
title: Conformation-Dependent Donor Selectivity in the Xanthan Gum Glycosyltransferase GumK Revealed by AI-Based Docking
title_zh: 基于AI对接揭示黄原胶糖基转移酶GumK中构象依赖的供体选择性
authors: "Luciano, D., Alenfalk, T., Courtade, G."
date: 2026-06-22
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.10.717502v2.full.pdf"
tags: ["query:caos-poly"]
score: 7.0
evidence: 基于AI的虚拟筛选用于多糖合成酶的供体底物
tldr: GT-B糖基转移酶局部构象如何影响供体选择性尚不清晰。本研究利用AI增强对接和共折叠方法，探究黄原胶糖基转移酶GumK的打开与关闭两种供体结合口袋构象与不同配体类似物的相互作用。结果表明，打开状态优先与带负电糖的羧基结合，而关闭状态倾向与焦磷酸基团作用。该发现揭示供体特异性源自配体化学与结合位点可塑性的互作，而非单一刚性模式，并展示了对接与共折叠方法在研究柔性CAZymes中的互补优势。
source: biorxiv
selection_source: fresh_fetch
motivation: GT-B糖基转移酶局部构象对供体选择性的影响机制不清，GumK的供体结合口袋存在两种构象状态，需揭示其作用。
method: 利用AI增强对接GNINA分析GumK构象状态与配体类似物的结合，并通过AlphaFold3和Boltz共折叠进行正交验证。
result: 打开状态中，带负电糖优先通过羧基与Lys307结合；关闭状态则倾向焦磷酸结合。GNINA生成的集合捕捉到构象选择性，与物理模拟一致。
conclusion: 供体特异性由配体化学与结合位点可塑性共同决定，而非单一刚性模式。AI对接与共折叠方法在研究柔性CAZymes中具互补优势。
---

## 摘要
GT-B折叠糖基转移酶的结构域间灵活性调节底物结合与催化，然而局部结构变异在供体底物特异性中的作用尚不明确。GumK是一种来自野油菜黄单胞菌的GT70家族酶，其供体结合口袋内表现出局部可塑性。我们将这种可塑性分为两种构象状态，由稳定口袋的保守疏水相互作用的存在（闭合状态）或缺失（开放状态）来定义。利用AI增强的对接方法GNINA，我们通过比较UDP-葡萄糖醛酸与五种酸性和中性配体类似物，研究了这些状态与底物特异性之间的关系。尽管对接评分对配体的区分有限，但基于糖C6原子与Lys307之间距离的分析揭示了构象依赖的趋势。在开放状态下，带负电荷的糖优先通过其羧酸基团与Lys307相互作用。相反，闭合状态则有利于与焦磷酸部分的相互作用。为了提供正交验证，我们使用基于AI的共折叠方法（AlphaFold3和Boltz）生成了GumK-底物复合物的系综。尽管Boltz-2亲和力正确排出了底物特异性顺序，但只有GNINA生成的系综与基于物理的模拟一致，捕获了选择性的构象基础。这些结果表明，供体特异性源于配体化学性质与结合位点可塑性之间的相互作用，而非单一的刚性结合模式，并突显了对接和共折叠方法在研究柔性CAZymes时的互补优势。

## Abstract
The interdomain flexibility of GT-B fold glycosyltransferases regulates substrate binding and catalysis, yet the role of local structural variations in donor substrate specificity remains unclear. GumK, a GT70 enzyme from Xanthomonas campestris, exhibits local plasticity within its donor-binding pocket. We classify this plasticity into two conformational states, defined by the presence (closed state) or absence (open state) of a conserved hydrophobic interaction stabilizing the pocket. Using the AI-enhanced docking approach GNINA, we investigated the relationship between these states and substrate specificity by comparing UDP-glucuronate with five acidic and neutral ligand analogs. While docking scores showed limited discrimination among ligands, distance-based analysis between the sugar C6 atom and Lys307 revealed conformation-dependent trends. In the open state, negatively charged sugars preferentially interact with Lys307 via their carboxylate groups. Conversely, the closed state favors interactions with the pyrophosphate moiety. To provide orthogonal validation, we generated ensembles of GumK-substrate complexes using AI-based cofolding methods (AlphaFold3 and Boltz). While Boltz-2 affinities correctly ranked substrate specificity, only the GNINA-generated ensembles were consistent with physics-based simulations in capturing the conformational basis of selectivity. These results suggest that donor specificity arises from the interplay between ligand chemistry and binding-site plasticity rather than from a single rigid binding mode, and highlight complementary strengths of docking and cofolding approaches for studying flexible CAZymes.