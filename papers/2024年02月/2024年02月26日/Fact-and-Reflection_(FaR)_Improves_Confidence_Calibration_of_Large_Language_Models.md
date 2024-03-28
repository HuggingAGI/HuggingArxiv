# FaR 策略能够有效提升大型语言模型在输出时的信心校准度，让模型对自身预测的准确性有更好的把握。

发布时间：2024年02月26日

`LLM理论`

> Fact-and-Reflection (FaR) Improves Confidence Calibration of Large Language Models

# 摘要

> 为了让LLM更具可靠性，其输出的自信程度应准确反映其实际表现。当前已知LLM的表现很大程度上取决于提示方式，但关于如何有效校准提示引导下的LLM自信心的研究尚不充分。在这项研究中，我们探索了不同提示策略如何影响LLM的自信心校准，并寻求提升校准度的方法。经过对六种提示方法在问答环境下的深入实验，我们发现尽管这些方法总体上有助于提升LLM校准预期，但也存在促使LLM在处理部分实例时过于自信的现象。参照人类认知过程，我们创新性地提出了一种名为事实与反思（FaR）的提示策略，它分两步提升LLM校准度：首先从LLM中引出与输入提示紧密关联的“事实信息”，继而要求模型基于这些事实进行深度“反思”，从而生成最终答案。实验证明，FaR提示法能大幅改善校准效果，使我们在多种QA任务上的预期校准误差降低了23.5%。尤其值得一提的是，FaR提示还能够激发LLM在面临不确定情况时表达疑惑的能力，进而启动检索增强机制，助力解决更复杂的难题。

> For a LLM to be trustworthy, its confidence level should be well-calibrated with its actual performance. While it is now common sense that LLM performances are greatly impacted by prompts, the confidence calibration in prompting LLMs has yet to be thoroughly explored. In this paper, we explore how different prompting strategies influence LLM confidence calibration and how it could be improved. We conduct extensive experiments on six prompting methods in the question-answering context and we observe that, while these methods help improve the expected LLM calibration, they also trigger LLMs to be over-confident when responding to some instances. Inspired by human cognition, we propose Fact-and-Reflection (FaR) prompting, which improves the LLM calibration in two steps. First, FaR elicits the known "facts" that are relevant to the input prompt from the LLM. And then it asks the model to "reflect" over them to generate the final answer. Experiments show that FaR prompting achieves significantly better calibration; it lowers the Expected Calibration Error by 23.5% on our multi-purpose QA tasks. Notably, FaR prompting even elicits the capability of verbally expressing concerns in less confident scenarios, which helps trigger retrieval augmentation for solving these harder instances.

[Arxiv](https://arxiv.org/abs/2402.17124)