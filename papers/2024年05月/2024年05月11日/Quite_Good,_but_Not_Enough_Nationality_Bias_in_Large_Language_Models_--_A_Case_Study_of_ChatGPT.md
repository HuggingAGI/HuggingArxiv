# 尚可但不足：探究大型语言模型中的国籍偏见——以ChatGPT为例

发布时间：2024年05月11日

`LLM理论

这篇论文关注的是大型语言模型（LLM）中的国籍偏见问题，特别是针对ChatGPT（GPT-3.5）模型。研究通过广泛的实验和分析，揭示了模型在文本生成中存在的国籍偏见，并探讨了这种偏见在不同语言和文化背景下的表现。这项工作不仅对模型的性能进行了评估，还深入分析了模型背后的理论问题，即模型如何反映和潜在地强化现实世界的偏见。因此，这篇论文属于LLM理论分类，因为它探讨了LLM的内在机制和潜在的社会影响，而不是专注于特定的应用场景或Agent的设计。` `社会科学`

> Quite Good, but Not Enough: Nationality Bias in Large Language Models -- A Case Study of ChatGPT

# 摘要

> 国籍虽是提升语言模型性能的关键因素，但其内在偏见却鲜少被审视。本研究深入探讨了ChatGPT（GPT-3.5）这一大型语言模型在文本生成中的国籍偏见问题，覆盖了全球195个国家，采用4种温度设置和3种提示类型，生成了4,680篇中英文国籍描述。通过自动化工具和专家评估，揭示了ChatGPT生成的文本虽以正面为主，但在负面提示下亦会流露负面情绪。ChatGPT虽自认为文本中性，但在与人类注释者相同的评估框架下，显露出对国籍偏见的自我认知。研究指出，ChatGPT的文本虽显友好，却映射出现实世界的国籍偏见，且这种偏见在不同语言版本中呈现出文化多样性。本研究强调了大型语言模型中偏见的微妙与普遍，呼吁对其进行更深入的审视。

> While nationality is a pivotal demographic element that enhances the performance of language models, it has received far less scrutiny regarding inherent biases. This study investigates nationality bias in ChatGPT (GPT-3.5), a large language model (LLM) designed for text generation. The research covers 195 countries, 4 temperature settings, and 3 distinct prompt types, generating 4,680 discourses about nationality descriptions in Chinese and English. Automated metrics were used to analyze the nationality bias, and expert annotators alongside ChatGPT itself evaluated the perceived bias. The results show that ChatGPT's generated discourses are predominantly positive, especially compared to its predecessor, GPT-2. However, when prompted with negative inclinations, it occasionally produces negative content. Despite ChatGPT considering its generated text as neutral, it shows consistent self-awareness about nationality bias when subjected to the same pair-wise comparison annotation framework used by human annotators. In conclusion, while ChatGPT's generated texts seem friendly and positive, they reflect the inherent nationality biases in the real world. This bias may vary across different language versions of ChatGPT, indicating diverse cultural perspectives. The study highlights the subtle and pervasive nature of biases within LLMs, emphasizing the need for further scrutiny.

[Arxiv](https://arxiv.org/abs/2405.06996)