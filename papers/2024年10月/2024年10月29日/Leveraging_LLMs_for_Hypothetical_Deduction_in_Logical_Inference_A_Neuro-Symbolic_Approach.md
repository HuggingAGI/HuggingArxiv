# 借助大型语言模型实现逻辑推理中的假设演绎：一种神经符号化的途径

发布时间：2024年10月29日

`LLM应用` `逻辑推理`

> Leveraging LLMs for Hypothetical Deduction in Logical Inference: A Neuro-Symbolic Approach

# 摘要

> 大型语言模型（LLMs）在众多推理任务，比如逻辑推理方面，展现出了非凡的潜力。尽管为了借助外部逻辑符号求解器增强LLMs的逻辑推理能力付出了诸多努力，然而，符号求解器驱动方式存在对不同特征问题泛化能力欠佳以及不可避免的问题信息丢失等关键难题，至今仍未解决。为减轻这些问题，我们推出了LINA，这是一种由LLM驱动的神经符号方法，用于实现可靠的逻辑推理。LINA能让LLM自主完成从命题逻辑提取到复杂逻辑推理的转变，不但增强了推理过程的韧性，还摆脱了对外部求解器的依赖。另外，通过采用假设演绎推理模式，LINA有效避开了传统正向推理方法所面临的广阔搜索空间难题。实证评估显示，在五个逻辑推理任务中，LINA显著优于已有的命题逻辑框架和传统的提示技术。具体来说，在FOLIO数据集上，LINA比LINC提升了24.34%，同时比CoT和CoT-SC等提示策略最多高出24.02%。我们的代码可在https://github.com/wufeiwuwoshihua/nshy获取。

> Large Language Models (LLMs) have exhibited remarkable potential across a wide array of reasoning tasks, including logical reasoning. Although massive efforts have been made to empower the logical reasoning ability of LLMs via external logical symbolic solvers, crucial challenges of the poor generalization ability to questions with different features and inevitable question information loss of symbolic solver-driven approaches remain unresolved. To mitigate these issues, we introduce LINA, a LLM-driven neuro-symbolic approach for faithful logical reasoning. By enabling an LLM to autonomously perform the transition from propositional logic extraction to sophisticated logical reasoning, LINA not only bolsters the resilience of the reasoning process but also eliminates the dependency on external solvers. Additionally, through its adoption of a hypothetical-deductive reasoning paradigm, LINA effectively circumvents the expansive search space challenge that plagues traditional forward reasoning methods. Empirical evaluations demonstrate that LINA substantially outperforms both established propositional logic frameworks and conventional prompting techniques across a spectrum of five logical reasoning tasks. Specifically, LINA achieves an improvement of 24.34% over LINC on the FOLIO dataset, while also surpassing prompting strategies like CoT and CoT-SC by up to 24.02%. Our code is available at https://github.com/wufeiwuwoshihua/nshy.

[Arxiv](https://arxiv.org/abs/2410.21779)