# 深入文化细微之处：探索大型语言模型在资源有限的真实世界场景中的实际效能

发布时间：2024年06月01日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在多语言和代码混合沟通场景中的应用，特别是在一个包含斯瓦希里语、英语和Sheng语的多语言WhatsApp聊天数据集上的情感分析评估。研究不仅关注了模型的性能指标如F1分数，还对模型的预测解释进行了定性分析。这表明论文的重点在于LLMs的实际应用和性能评估，而不是理论研究或Agent的设计与应用，因此最合适的分类是LLM应用。` `情感分析` `多语言沟通`

> Beyond Metrics: Evaluating LLMs' Effectiveness in Culturally Nuanced, Low-Resource Real-World Scenarios

# 摘要

> 大型语言模型（LLMs）在实际应用中展现出机遇与挑战，尤其是在多语言和代码混合的沟通场景中。本研究针对七大领先LLMs，在包含斯瓦希里语、英语和Sheng语的多语言WhatsApp聊天数据集上进行了情感分析评估。评估不仅包括F1分数等定量指标，还涉及对LLMs预测解释的定性分析。研究发现，尽管Mistral-7b和Mixtral-8x7b的F1分数较高，但与GPT-3.5-Turbo、Llama-2-70b和Gemma-7b等模型一样，它们在理解语言和上下文细微差别以及决策透明度方面存在不足。相反，GPT-4和GPT-4-Turbo在处理多样语言输入和上下文信息方面表现卓越，决策过程与人类一致且透明。然而，LLMs在非英语环境中融入文化细微差别时遇到挑战，GPT-4的表现也不稳定。这些结果凸显了持续优化LLMs以应对文化多样性和资源有限现实挑战的重要性。

> The deployment of Large Language Models (LLMs) in real-world applications presents both opportunities and challenges, particularly in multilingual and code-mixed communication settings. This research evaluates the performance of seven leading LLMs in sentiment analysis on a dataset derived from multilingual and code-mixed WhatsApp chats, including Swahili, English and Sheng. Our evaluation includes both quantitative analysis using metrics like F1 score and qualitative assessment of LLMs' explanations for their predictions. We find that, while Mistral-7b and Mixtral-8x7b achieved high F1 scores, they and other LLMs such as GPT-3.5-Turbo, Llama-2-70b, and Gemma-7b struggled with understanding linguistic and contextual nuances, as well as lack of transparency in their decision-making process as observed from their explanations. In contrast, GPT-4 and GPT-4-Turbo excelled in grasping diverse linguistic inputs and managing various contextual information, demonstrating high consistency with human alignment and transparency in their decision-making process. The LLMs however, encountered difficulties in incorporating cultural nuance especially in non-English settings with GPT-4s doing so inconsistently. The findings emphasize the necessity of continuous improvement of LLMs to effectively tackle the challenges of culturally nuanced, low-resource real-world settings.

![深入文化细微之处：探索大型语言模型在资源有限的真实世界场景中的实际效能](../../../paper_images/2406.00343/x1.png)

![深入文化细微之处：探索大型语言模型在资源有限的真实世界场景中的实际效能](../../../paper_images/2406.00343/x2.png)

![深入文化细微之处：探索大型语言模型在资源有限的真实世界场景中的实际效能](../../../paper_images/2406.00343/x3.png)

[Arxiv](https://arxiv.org/abs/2406.00343)