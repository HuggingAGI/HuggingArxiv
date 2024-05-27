# 文化公园：增强大型语言模型中的跨文化理解力

发布时间：2024年05月23日

`Agent

这篇论文介绍了一个基于大型语言模型（LLMs）的多代理通信框架CulturePark，旨在通过模拟跨文化沟通来收集文化数据。这个框架通过多代理系统生成包含人类信仰、规范和习俗的高质量对话，并利用这些数据微调了特定文化的LLMs。这种方法不仅用于减少文化偏见，还推动了AI的民主化，并强调了文化包容性数据在模型训练中的重要性。因此，这篇论文更符合Agent分类，因为它涉及使用多代理系统来解决特定问题，即文化数据的收集和模型的微调。` `文化教育` `内容审核`

> CulturePark: Boosting Cross-cultural Understanding in Large Language Models

# 摘要

> 大型语言模型（LLMs）普遍存在文化偏见，主要源于缺乏代表多元文化的数据。现有的文化数据集和基准多依赖于现实数据和人工标注，成本高且难以扩展。本文受社会沟通认知理论启发，推出了CulturePark，一个基于LLM的多代理通信框架，旨在收集文化数据。通过模拟跨文化沟通，CulturePark生成了包含人类信仰、规范和习俗的高质量对话。我们利用这些数据微调了八个特定文化的LLMs，并在内容审核、文化对齐和文化教育三个任务上进行了评估。结果表明，我们的模型在多个方面超越了GPT-4，特别是在文化教育和内容审核方面。CulturePark不仅有助于减少文化偏见，还推动了AI的民主化，凸显了文化包容性数据在模型训练中的重要性。

> Cultural bias is pervasive in many large language models (LLMs), largely due to the deficiency of data representative of different cultures. Typically, cultural datasets and benchmarks are constructed either by extracting subsets of existing datasets or by aggregating from platforms such as Wikipedia and social media. However, these approaches are highly dependent on real-world data and human annotations, making them costly and difficult to scale. Inspired by cognitive theories on social communication, this paper introduces CulturePark, an LLM-powered multi-agent communication framework for cultural data collection. CulturePark simulates cross-cultural human communication with LLM-based agents playing roles in different cultures. It generates high-quality cross-cultural dialogues encapsulating human beliefs, norms, and customs. Using CulturePark, we generated 41,000 cultural samples to fine-tune eight culture-specific LLMs. We evaluated these models across three downstream tasks: content moderation, cultural alignment, and cultural education. Results show that for content moderation, our GPT-3.5-based models either match or outperform GPT-4 on datasets. Regarding cultural alignment, our models surpass GPT-4 on Hofstede's VSM 13 framework. Furthermore, for cultural education of human participants, our models demonstrate superior outcomes in both learning efficacy and user experience compared to GPT-4. CulturePark proves an important step in addressing cultural bias and advancing the democratization of AI, highlighting the critical role of culturally inclusive data in model training.

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x1.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x2.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x3.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x5.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x6.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x7.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x8.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x9.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x10.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x11.png)

![文化公园：增强大型语言模型中的跨文化理解力](../../../paper_images/2405.15145/x12.png)

[Arxiv](https://arxiv.org/abs/2405.15145)