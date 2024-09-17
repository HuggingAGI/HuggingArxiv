# 基于 LLM 的集成学习助力论文来源追踪：无需 GPU 的创新方案

发布时间：2024年09月14日

`LLM应用` `人工智能`

> LLM-Powered Ensemble Learning for Paper Source Tracing: A GPU-Free Approach

# 摘要

> 我们在 KDD CUP 2024 论文来源追踪竞赛中荣获第三名。不同于多数团队通过微调 BERT 或 ChatGLM 等预训练模型来识别论文参考来源，我们主要采用闭源大型语言模型 (LLM)。得益于 LLM 技术的进步，闭源 LLM 在零-shot 或 few-shot 场景下展现了强大的推理能力。因此，即便没有 GPU，我们也能利用闭源 LLM 直接生成预测的参考来源，并通过集成学习优化结果。值得一提的是，我们的方法在获奖方案中独树一帜，无需 GPU 进行模型训练。代码已公开，详见 https://github.com/Cklwanfifa/KDDCUP2024-PST。

> We participated in the KDD CUP 2024 paper source tracing competition and achieved the 3rd place. This competition tasked participants with identifying the reference sources (i.e., ref-sources, as referred to by the organizers of the competition) of given academic papers. Unlike most teams that addressed this challenge by fine-tuning pre-trained neural language models such as BERT or ChatGLM, our primary approach utilized closed-source large language models (LLMs). With recent advancements in LLM technology, closed-source LLMs have demonstrated the capability to tackle complex reasoning tasks in zero-shot or few-shot scenarios. Consequently, in the absence of GPUs, we employed closed-source LLMs to directly generate predicted reference sources from the provided papers. We further refined these predictions through ensemble learning. Notably, our method was the only one among the award-winning approaches that did not require the use of GPUs for model training. Code available at https://github.com/Cklwanfifa/KDDCUP2024-PST.

[Arxiv](https://arxiv.org/abs/2409.09383)