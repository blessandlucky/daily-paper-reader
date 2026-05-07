---
title: A High-Fidelity 3D Fluid-Structure Interaction Framework for Predictive Microfluidic Design
title_zh: 用于预测性微流控设计的高保真三维流固耦合框架
authors: "Shen, L., Zhang, Y., Chen, Y., Ding, X., Wen, P., Wang, C., Sun, P., Gong, S., Xu, J., Han, J."
date: 2026-04-30
pdf: "https://www.biorxiv.org/content/10.64898/2026.04.28.721227v1.full.pdf"
tags: ["query:gas-bubble-dynamics-her-oer-water-electrolysis-metal-batteries-bubble-regulation-strategies-electrode-gas-management-multiphase-flow-electrolysis-bubble-suppression-electrochemical-gas-evolution-gas-management-in-batteries"]
score: 6.0
evidence: 用于多尺度流体动力学行为的高保真3D流固耦合框架。
tldr: 针对微流控设计长期依赖经验原型且缺乏预测能力的现状，本研究开发了一种高保真三维流固耦合（FSI）框架。该框架结合高阶ALE有限元法与局部分层动态网格策略，能够精确解析复杂的多尺度流体动力学行为。通过在确定性侧向位移结构中的验证，该模型实现了亚微米级的粒子轨迹预测，并揭示了临界尺寸波动等深层物理机制，为微流控数字化设计提供了关键的预测性基础设施。
source: biorxiv
selection_source: fresh_fetch
motivation: 传统的二维或解耦模拟无法准确捕捉微流控中复杂的流体与粒子相互作用，限制了高效的预测性数字化设计。
method: 建立了一种结合高阶任意拉格朗日-欧拉映射有限元法与局部层次动态网格策略的三维流固耦合计算框架。
result: 该框架在预测粒子轨迹和分离直径方面达到了亚微米精度，并成功解释了局部尺寸阈值的M型波动及粒子垂直迁移等物理现象。
conclusion: 该研究为复杂微流控结构的预测性优化提供了强有力工具，推动了微流控开发从经验试错向精密仿真驱动工程的范式转变。
---

## 摘要
微流控技术的商业化成熟仍受限于经验性的原型设计以及预测性数字设计能力的缺失。由于优化被动粒子分离等先进技术从根本上取决于流体动力学与粒子力学的精确耦合，传统的二维或解耦流体模拟本质上无法捕捉真实的多尺度行为。为了弥补这一差距，我们建立了一个高保真三维流固耦合框架，该框架结合了基于高阶任意拉格朗日-欧拉映射的有限元方法与局部层次化动态网格策略。该架构旨在精确解析复杂的多尺度流体动力学，并利用确定性侧向位移结构作为严格的测试案例。通过对硬质微球和肿瘤细胞的实验数据进行验证，该框架能以亚微米级的精度预测输运轨迹和临界分离直径。至关重要的是，该模拟明确解析了局部尺寸阈值的M型空间波动以及粒子的动态垂直迁移。揭示这些隐藏的物理机制为混合模式输运等极具争议的现象提供了确定性的解释。通过实现对复杂非周期性结构的严谨计算机模拟评估，该框架成为预测性结构优化的强大工具。这些能力为微流控数字设计建立了必要的基础设施，加速了从经验性试错向精密模拟驱动工程的转变。

## Abstract
The commercial maturation of microfluidics remains bottlenecked by empirical prototyping and an absence of predictive digital design capabilities. Because optimizing advanced technologies such as passive particle separation fundamentally hinges on the precise coupling of fluid dynamics and particle mechanics, conventional two-dimensional or decoupled fluid simulations inherently fail to capture authentic multiscale behaviors. To bridge this gap, we establish a high-fidelity three-dimensional fluid-structure interaction framework combining a high-order Arbitrary Lagrangian-Eulerian mapping-based finite element method with a localized hierarchical dynamic mesh strategy. Engineered to accurately resolve complex multiscale hydrodynamics, this architecture utilizes deterministic lateral displacement structures as a stringent test case. Validated against experimental data for rigid microspheres and tumor cells, the framework predicts transport trajectories and critical separation diameters with sub-micron precision. Crucially, the simulation explicitly resolves the M-shaped spatial fluctuation of local size thresholds alongside the dynamic vertical migration of particles. Unveiling these hidden physical mechanisms provides a deterministic explanation for highly debated phenomena such as mixed-mode transport. By enabling the rigorous in silico evaluation of complex non-periodic architectures, this framework serves as a powerful instrument for predictive structural optimization. Such capabilities establish the essential infrastructure for microfluidic digital design, accelerating the transition from empirical trial-and-error to precision simulation-driven engineering.