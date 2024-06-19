# 揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道

发布时间：2024年06月18日

`LLM理论

理由：这篇论文主要探讨了合成数据在大型语言模型（LLM）训练中的应用及其潜在问题，并提出了一种基于遗忘技术的解决方案。这涉及到对LLM训练过程中数据使用的理论分析和改进方法的研究，因此属于LLM理论分类。论文的核心在于理解和改进LLM训练过程中的数据处理机制，而不是直接应用LLM或探讨其安全性，因此不适合归类为Agent、RAG或LLM应用。` `机器学习` `数据处理`

> Unveiling the Flaws: Exploring Imperfections in Synthetic Data and Mitigation Strategies for Large Language Models

# 摘要

> 合成数据被视为解决大型语言模型训练中高质量数据短缺问题的良策。研究显示，它确实能提升模型在下游测试中的表现。然而，我们的分析揭示了合成数据潜在的内在缺陷：其统一格式易导致模型过度拟合特定模式，进而改变输出分布，削弱模型的指令遵循能力。本研究聚焦于问答对这一常见合成数据的缺陷，并提出一种基于遗忘技术的解决方案。实证表明，该方法在不牺牲性能的前提下，以较低成本有效解决了过度拟合问题，为推动更稳健、高效的LLM训练提供了关键见解。

> Synthetic data has been proposed as a solution to address the issue of high-quality data scarcity in the training of large language models (LLMs). Studies have shown that synthetic data can effectively improve the performance of LLMs on downstream benchmarks. However, despite its potential benefits, our analysis suggests that there may be inherent flaws in synthetic data. The uniform format of synthetic data can lead to pattern overfitting and cause significant shifts in the output distribution, thereby reducing the model's instruction-following capabilities. Our work delves into these specific flaws associated with question-answer (Q-A) pairs, a prevalent type of synthetic data, and presents a method based on unlearning techniques to mitigate these flaws. The empirical results demonstrate the effectiveness of our approach, which can reverse the instruction-following issues caused by pattern overfitting without compromising performance on benchmarks at relatively low cost. Our work has yielded key insights into the effective use of synthetic data, aiming to promote more robust and efficient LLM training.

![揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道](../../../paper_images/2406.12397/x1.png)

![揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道](../../../paper_images/2406.12397/x2.png)

![揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道](../../../paper_images/2406.12397/x3.png)

![揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道](../../../paper_images/2406.12397/x4.png)

![揭秘瑕疵：探究合成数据中的缺陷及大型语言模型缺陷的缓解之道](../../../paper_images/2406.12397/x5.png)

[Arxiv](https://arxiv.org/abs/2406.12397)