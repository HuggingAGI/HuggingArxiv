# NORMAD：衡量大型语言模型文化适应性的基准测试。

发布时间：2024年04月18日

`分类：LLM应用` `文化研究` `人工智能伦理`

> NORMAD: A Benchmark for Measuring the Cultural Adaptability of Large Language Models

# 摘要

> 大型语言模型（LLMs）融入全球多元文化中，面临文化适应的挑战：它们需巧妙处理互动、维护社会规范、并避免文化冲突。目前，LLMs 是否能根据不同文化规范调整输出尚不明确。本研究聚焦此问题，推出 NormAd 数据集，内含 2.6k 个故事，涵盖 75 国的社会文化规范，旨在测试 LLMs 对不同社会文化背景的适应能力，包括国家起源、文化价值观及社会习俗。研究发现，LLMs 在所有文化背景下的文化推理上表现挣扎，对英语主导文化适应性更强。即便是顶尖模型 Mistral-7b-Instruct，在明确社会规范下也仅达到 81.8% 的准确率，低于人类的 95.6%。NormAd 的评估进一步显示，LLMs 在跨文化礼物交换故事的适应上存在挑战。由于内在的一致性或奉承倾向，LLMs 更容易评估遵循文化规范故事的社会接受度。我们的基准测试强调了提升 LLMs 文化适应性的重要性，以期让这些技术更公平、更适用于全球用户。

> The integration of Large Language Models (LLMs) into various global cultures fundamentally presents a cultural challenge: LLMs must navigate interactions, respect social norms, and avoid transgressing cultural boundaries. However, it is still unclear if LLMs can adapt their outputs to diverse cultural norms. Our study focuses on this aspect. We introduce NormAd, a novel dataset, which includes 2.6k stories that represent social and cultural norms from 75 countries, to assess the ability of LLMs to adapt to different granular levels of socio-cultural contexts such as the country of origin, its associated cultural values, and prevalent social norms. Our study reveals that LLMs struggle with cultural reasoning across all contextual granularities, showing stronger adaptability to English-centric cultures over those from the Global South. Even with explicit social norms, the top-performing model, Mistral-7b-Instruct, achieves only 81.8\% accuracy, lagging behind the 95.6\% achieved by humans. Evaluation on NormAd further reveals that LLMs struggle to adapt to stories involving gift-giving across cultures. Due to inherent agreement or sycophancy biases, LLMs find it considerably easier to assess the social acceptability of stories that adhere to cultural norms than those that deviate from them. Our benchmark measures the cultural adaptability (or lack thereof) of LLMs, emphasizing the potential to make these technologies more equitable and useful for global audiences.

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x1.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x2.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x3.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x4.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x5.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x6.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x7.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x8.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_kto_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_ppo_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_ppo_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_kto_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_ppo_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_kto_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-7b-chat_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-13b-chat_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-70b-chat_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/olmo-7b-sft_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/olmo-7b-instruct_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/gpt-3.5-turbo-0125_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/gpt4_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/mistral-chat_iwbin.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_kto_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/7b_sft_ppo_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_ppo_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/13b_sft_kto_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_ppo_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/30b_sft_kto_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-7b-chat_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-13b-chat_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/llama2-70b-chat_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/olmo-7b-sft_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/olmo-7b-instruct_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/gpt-3.5-turbo-0125_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/gpt4_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/mistral-chat_labels.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x9.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x10.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x11.png)

![NORMAD：衡量大型语言模型文化适应性的基准测试。](../../../paper_images/2404.12464/x12.png)

[Arxiv](https://arxiv.org/abs/2404.12464)