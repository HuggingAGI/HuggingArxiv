# 探究多模态大型语言模型在视频问答基准测试中的模态偏差
发布时间：2024年08月22日

`多模态大模型`
> Assessing Modality Bias in Video Question Answering Benchmarks with Multimodal Large Language Models
>
> 多模态大型语言模型 (MLLMs) 能同时处理视觉、文本和听觉数据，提供补充人类分析的洞察。然而，现有视频问答 (VidQA) 基准和数据集常偏向单一模态，尽管目标是需要整合多种模态的高级推理技能。为此，我们引入了模态重要性分数 (MIS) 来识别这种偏差，旨在评估哪种模态包含回答问题所需信息。我们还提出了一种创新方法，利用最先进的 MLLMs 估计模态重要性，作为人类模态感知判断的代理。通过 MIS，我们揭示了现有数据集中的单模态偏差和真正多模态问题的稀缺性。通过多项消融研究，我们验证了 MIS，评估了 MLLMs 在排列特征集上的性能。结果显示，因数据集模态不平衡，当前模型未能有效整合信息。我们提出的 MLLM 衍生的 MIS 能指导制作模态平衡的数据集，推动多模态学习，增强 MLLMs 理解和利用跨模态协同关系的能力。
>
> https://arxiv.org/abs/2408.12763

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.12763](https://arxiv.org/abs/2408.12763)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)