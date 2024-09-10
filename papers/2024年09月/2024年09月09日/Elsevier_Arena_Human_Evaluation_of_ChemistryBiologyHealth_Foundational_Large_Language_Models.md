# Elsevier Arena：探索化学、生物与健康领域基础大型语言模型的人类评估

发布时间：2024年09月09日

`LLM应用` `生物医学`

> Elsevier Arena: Human Evaluation of Chemistry/Biology/Health Foundational Large Language Models

# 摘要

> 大型语言模型的质量和能力目前无法仅通过自动化基准评估来全面衡量，而需要结合自然语言生成文献中的传统定性技术进行人类评估。最近的最佳实践之一是采用A/B测试框架，以捕捉人类评估者对特定模型的偏好。本文介绍了一项在Elsevier进行的生物医学领域（涵盖健康、生物学、化学/药理学）的人类评估实验。实验中，一个8.8B参数的非大规模仅解码器基础变压器，训练于135B标记的高度精选Elsevier数据集，与OpenAI的GPT-3.5-turbo和Meta的7B参数Llama 2模型在多个标准下进行对比。结果显示，尽管IRR分数普遍较低，但GPT-3.5-turbo更受青睐，这表明具备对话能力、规模庞大且训练数据集巨大的模型更具优势。然而，实验也指出，对于规模较小的模型，若能在精心策划的小规模训练集上进行训练，也可能在生物医学领域成为有力的竞争者。

> The quality and capabilities of large language models cannot be currently fully assessed with automated, benchmark evaluations. Instead, human evaluations that expand on traditional qualitative techniques from natural language generation literature are required. One recent best-practice consists in using A/B-testing frameworks, which capture preferences of human evaluators for specific models. In this paper we describe a human evaluation experiment focused on the biomedical domain (health, biology, chemistry/pharmacology) carried out at Elsevier. In it a large but not massive (8.8B parameter) decoder-only foundational transformer trained on a relatively small (135B tokens) but highly curated collection of Elsevier datasets is compared to OpenAI's GPT-3.5-turbo and Meta's foundational 7B parameter Llama 2 model against multiple criteria. Results indicate -- even if IRR scores were generally low -- a preference towards GPT-3.5-turbo, and hence towards models that possess conversational abilities, are very large and were trained on very large datasets. But at the same time, indicate that for less massive models training on smaller but well-curated training sets can potentially give rise to viable alternatives in the biomedical domain.

[Arxiv](https://arxiv.org/abs/2409.05486)