# 多模态大型语言模型在处理困难任务时表现出色，但在简单任务上却显得懒散。本文将揭示这种“懒惰”现象。

发布时间：2024年10月15日

`LLM应用` `人工智能` `计算机视觉`

> Difficult Task Yes but Simple Task No: Unveiling the Laziness in Multimodal LLMs

# 摘要

> 多模态大型语言模型（MLLM）虽然能理解现实世界并处理复杂任务，但在简单视觉问答（VQA）上仍会失手。本文深入分析，发现模型在回答简单的是/否问题时易错，尽管能准确描述图像。我们将这种在难易问题间的差异称为“模型懒惰”。为系统研究，我们构建了LazyBench基准，包含是/否、选择、简答及图像描述任务。基于此，发现当前先进MLLM（如GPT-4o、Gemini-1.5-pro、Claude 3和LLaVA-v1.5-13B）普遍存在懒惰，且在更强模型中更显著。分析VQA v2基准，约半数失败由懒惰引起，凸显了充分利用模型能力的重要性。我们初步探索发现，思维链（CoT）能有效缓解这一问题。

> Multimodal Large Language Models (MLLMs) demonstrate a strong understanding of the real world and can even handle complex tasks. However, they still fail on some straightforward visual question-answering (VQA) problems. This paper dives deeper into this issue, revealing that models tend to err when answering easy questions (e.g. Yes/No questions) about an image, even though they can correctly describe it. We refer to this model behavior discrepancy between difficult and simple questions as model laziness. To systematically investigate model laziness, we manually construct LazyBench, a benchmark that includes Yes/No, multiple choice, short answer questions, and image description tasks that are related to the same subjects in the images. Based on LazyBench, we observe that laziness widely exists in current advanced MLLMs (e.g. GPT-4o, Gemini-1.5-pro, Claude 3 and LLaVA-v1.5-13B), and it is more pronounced on stronger models. We also analyze the VQA v2 (LLaVA-v1.5-13B) benchmark and find that about half of its failure cases are caused by model laziness, which further highlights the importance of ensuring that the model fully utilizes its capability. To this end, we conduct preliminary exploration on how to mitigate laziness and find that chain of thought (CoT) can effectively address this issue.

[Arxiv](https://arxiv.org/abs/2410.11437)