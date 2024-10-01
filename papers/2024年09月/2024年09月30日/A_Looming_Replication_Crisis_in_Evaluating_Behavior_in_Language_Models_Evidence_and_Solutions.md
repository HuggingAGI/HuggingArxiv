# 语言模型行为评估是否面临复制危机？这里有证据，也有解决方案。

发布时间：2024年09月30日

`LLM理论` `人工智能` `研究方法论`

> A Looming Replication Crisis in Evaluating Behavior in Language Models? Evidence and Solutions

# 摘要

> 随着大型语言模型 (LLM) 在日常应用中的普及，对其行为的研究也日益增多。然而，由于该领域尚属新兴，缺乏明确的方法论指导，这引发了关于研究结果可重复性和普遍性的担忧。本研究探讨了复制危机的风险，并通过一系列针对提示工程技术的复制实验来验证。我们测试了 GPT-3.5、GPT-4o 等模型，在链式思维、情感提示等技术上，使用推理基准的手动双重检查子集。结果显示，几乎所有技术在统计学上均无显著差异，揭示了之前研究中的方法论缺陷。我们建议，未来应开发稳健的评估方法、建立健全的基准，并设计严格的实验框架，以确保模型输出的准确性和可靠性。

> In an era where large language models (LLMs) are increasingly integrated into a wide range of everyday applications, research into these models' behavior has surged. However, due to the novelty of the field, clear methodological guidelines are lacking. This raises concerns about the replicability and generalizability of insights gained from research on LLM behavior. In this study, we discuss the potential risk of a replication crisis and support our concerns with a series of replication experiments focused on prompt engineering techniques purported to influence reasoning abilities in LLMs. We tested GPT-3.5, GPT-4o, Gemini 1.5 Pro, Claude 3 Opus, Llama 3-8B, and Llama 3-70B, on the chain-of-thought, EmotionPrompting, ExpertPrompting, Sandbagging, as well as Re-Reading prompt engineering techniques, using manually double-checked subsets of reasoning benchmarks including CommonsenseQA, CRT, NumGLUE, ScienceQA, and StrategyQA. Our findings reveal a general lack of statistically significant differences across nearly all techniques tested, highlighting, among others, several methodological weaknesses in previous research. We propose a forward-looking approach that includes developing robust methodologies for evaluating LLMs, establishing sound benchmarks, and designing rigorous experimental frameworks to ensure accurate and reliable assessments of model outputs.

[Arxiv](https://arxiv.org/abs/2409.20303)