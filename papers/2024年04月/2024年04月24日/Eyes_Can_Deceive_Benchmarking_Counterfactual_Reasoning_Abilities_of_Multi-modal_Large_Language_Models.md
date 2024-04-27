# 眼睛或有误导：评估多模态大型语言模型的反事实推理能力。

发布时间：2024年04月24日

`分类：LLM应用

这篇论文讨论了多模态大型语言模型（MLLMs）在处理反事实问题时的表现，并构建了一个名为CFMM的反事实多模态推理基准来评估MLLMs的反事实推理能力。这表明论文关注的是大型语言模型（LLM）在特定应用场景（即反事实推理）下的表现和潜在改进，因此将其归类为LLM应用。` `人工智能` `视觉问答`

> Eyes Can Deceive: Benchmarking Counterfactual Reasoning Abilities of Multi-modal Large Language Models

# 摘要

> 反事实推理是人类智慧的关键体现，它涉及基于确凿事实提出假设并推演可能的结果。目前，多模态大型语言模型（MLLMs）在视觉问答（VQA）的多项基准测试中已展现出卓越的认知和推理技能。但当这些模型遭遇反事实问题时，它们的表现又将如何？为解答这一疑问，我们首次构建了一个名为CFMM的反事实多模态推理基准，旨在全面评估MLLMs的反事实推理能力。CFMM包含六项挑战性任务，每个任务都涵盖了数百个精心设计的反事实问题，用以多角度评价MLLMs的推理技能。实验结果显示，现有MLLMs倾向于信赖直观所见，却忽视了问题中提出的反事实前提，这导致了反应的不精确性。此外，我们在CFMM上对多种主流MLLMs进行了评估，发现它们在CFMM上的表现与VQA基准测试有显著差异，这表明MLLMs在达到人类智能水平方面还有很大的提升空间。展望未来，通过提升MLLMs在CFMM上的表现，我们有望探索出发展更高级智能MLLMs的潜在路径。

> Counterfactual reasoning, as a crucial manifestation of human intelligence, refers to making presuppositions based on established facts and extrapolating potential outcomes. Existing multimodal large language models (MLLMs) have exhibited impressive cognitive and reasoning capabilities, which have been examined across a wide range of Visual Question Answering (VQA) benchmarks. Nevertheless, how will existing MLLMs perform when faced with counterfactual questions? To answer this question, we first curate a novel \textbf{C}ounter\textbf{F}actual \textbf{M}ulti\textbf{M}odal reasoning benchmark, abbreviated as \textbf{CFMM}, to systematically assess the counterfactual reasoning capabilities of MLLMs. Our CFMM comprises six challenging tasks, each including hundreds of carefully human-labeled counterfactual questions, to evaluate MLLM's counterfactual reasoning capabilities across diverse aspects. Through experiments, interestingly, we find that existing MLLMs prefer to believe what they see, but ignore the counterfactual presuppositions presented in the question, thereby leading to inaccurate responses. Furthermore, we evaluate a wide range of prevalent MLLMs on our proposed CFMM. The significant gap between their performance on our CFMM and that on several VQA benchmarks indicates that there is still considerable room for improvement in existing MLLMs toward approaching human-level intelligence. On the other hand, through boosting MLLMs performances on our CFMM in the future, potential avenues toward developing MLLMs with advanced intelligence can be explored.

![眼睛或有误导：评估多模态大型语言模型的反事实推理能力。](../../../paper_images/2404.12966/intro.png)

![眼睛或有误导：评估多模态大型语言模型的反事实推理能力。](../../../paper_images/2404.12966/x1.png)

![眼睛或有误导：评估多模态大型语言模型的反事实推理能力。](../../../paper_images/2404.12966/exps.png)

![眼睛或有误导：评估多模态大型语言模型的反事实推理能力。](../../../paper_images/2404.12966/x2.png)

[Arxiv](https://arxiv.org/abs/2404.12966)