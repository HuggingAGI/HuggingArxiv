# RankPrompt技术通过步步对比，助力提升语言模型的推理能力

发布时间：2024年03月18日

`LLM应用` `推理系统`

> RankPrompt: Step-by-Step Comparisons Make Language Models Better Reasoners

> LLMs在多种推理任务中成绩斐然，但即使是ChatGPT这样的尖端模型在推理过程中也会犯逻辑错误。现有对策需依赖大量人工标注或在响应冲突情况下失效。为此，我们创新提出了RankPrompt这一新型提示方法，让LLMs能够自行对其生成的回复进行排序，无需任何额外资源。RankPrompt通过巧妙地运用LLMs内在的能力生成比较链作为情境示例，将排序难题转化为一系列多样的响应间对比。实验证明，在涵盖11个算术和常识推理任务中，RankPrompt成功提升了ChatGPT和GPT-4的推理效果，最高提升达13%。此外，RankPrompt在开放式生成任务的LLM自动化评估上表现卓越，尤其在AlpacaEval集合中，其评价结果有74%的时间与人类偏好相吻合。并且，无论回复排序如何变化或一致性如何，RankPrompt都能保持稳定高效的性能。

> Large Language Models (LLMs) have achieved impressive performance across various reasoning tasks. However, even state-of-the-art LLMs such as ChatGPT are prone to logical errors during their reasoning processes. Existing solutions, which include deploying task-specific verifiers or voting over multiple reasoning paths, either require extensive human annotations or fail in scenarios with inconsistent responses. To address these challenges, we introduce RankPrompt, a new prompting method that enables LLMs to self-rank their responses without additional resources. RankPrompt breaks down the ranking problem into a series of comparisons among diverse responses, leveraging the inherent capabilities of LLMs to generate chains of comparison as contextual exemplars. Our experiments across 11 arithmetic and commonsense reasoning tasks show that RankPrompt significantly enhances the reasoning performance of ChatGPT and GPT-4, with improvements of up to 13\%. RankPrompt also excels in LLM-based automatic evaluations for open-ended generation, aligning with human preferences 74\% of the time in the AlpacaEval set. Moreover, RankPrompt demonstrates robustness against variations in the orderings and consistencies of responses.

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x1.png)

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x2.png)

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x3.png)

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x4.png)

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x5.png)

![RankPrompt技术通过步步对比，助力提升语言模型的推理能力](../../../paper_images/2403.12373/x6.png)

[Arxiv](https://arxiv.org/abs/2403.12373)