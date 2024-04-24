# 在 GSM8K 测试中突破 97% 的高标：深入剖析问题，让大型语言模型化身为卓越的推理专家。

发布时间：2024年04月23日

`LLM应用` `人工智能`

> Achieving >97% on GSM8K: Deeply Understanding the Problems Makes LLMs Perfect Reasoners

# 摘要

> 链式思考提示法显著提升了大型语言模型在多样的自然语言处理任务中的性能。但面对复杂推理挑战，如理解偏差、计算失误和逻辑漏洞等，该方法仍有局限。本研究深入剖析了各类错误，认识到全面把握问题本质对于攻克复杂推理至关重要。本文提出了一种创新的提示策略——深度理解问题（DUP）提示法，灵感源自人类解决复杂问题的思维方式，旨在帮助语言模型深化对问题的理解。该策略分为三步：提炼核心疑问、基于核心问题搜寻解题信息、由语言模型生成及提炼答案。我们在十种不同的推理数据集上测试了DUP提示法的效果，实验数据显示其在所有数据集上均显著超越了传统的零样本链式思考方法。特别值得一提的是，DUP在SVAMP和GSM8K数据集上取得了行业领先的成绩，准确率分别从90.4\%提升至94.2\%，以及从94.6\%提升至97.1\%。

> Chain of Thought prompting strategy has enhanced the performance of Large Language Models (LLMs) across various NLP tasks. However, it still has shortcomings when dealing with complex reasoning tasks, following~\citet{cot_wei}, including understanding errors, calculation errors and process errors (e.g. missing-step and hallucinations). Subsequently, Our in-depth analysis of various error types has found that deeply understanding the whole problem is critical in addressing complicated reasoning tasks. In this paper, we proposed a novel prompt strategy called Deeply Understanding the Problems (DUP) prompting, inspired by how humans solve complex reasoning problems, designed to enhance the comprehensive understanding of problems by LLMs. It consists of three stages: 1) extract the core question; 2) find out problem-solving information based on the core question; 3) generate and extract answers by LLMs. We evaluate the performance of DUP prompting on ten diverse reasoning datasets. Experimental results suggest that DUP prompting significantly outperforms Zero-Shot CoT ~\cite{kojima2022large} across all datasets. Notably, DUP achieves \textbf{state-of-the-art on SVAMP (90.4\% to 94.2\%) and GSM8K (94.6\% to 97.1\%).}

[Arxiv](https://arxiv.org/abs/2404.14963)