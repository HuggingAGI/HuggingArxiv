# 借助 LLMs 和 LMMs，本研究探索了如何通过上下文图像描述技术提升新闻报道的质量。

发布时间：2024年08月08日

`LLM应用` `新闻业` `人工智能`

> Enhancing Journalism with AI: A Study of Contextualized Image Captioning for News Articles using LLMs and LMMs

# 摘要

> 大型语言模型（LLMs）和大型多模态模型（LMMs）对AI领域产生了深远影响。在新闻业中，AI的整合既带来挑战也带来机遇，尤其是在提升新闻报道的质量和效率方面。本研究探索了LLMs和LMMs如何通过为新闻图片生成情境化标题来辅助新闻工作。我们利用GoodNews数据集进行实验，评估了LMMs（如BLIP-2、GPT-4v和LLaVA）整合新闻全文或提取实体的能力。同时，我们比较了这些模型与两阶段流水线的表现，后者包括标题生成模型和事后情境化LLMs。实验发现，尽管情境化模型的选择对两阶段流水线至关重要，但在LMMs中，较小的开源模型表现出色。此外，控制上下文量能提升性能。这些发现揭示了完全自动化的局限，并强调了交互式、人在回路策略的重要性。

> Large language models (LLMs) and large multimodal models (LMMs) have significantly impacted the AI community, industry, and various economic sectors. In journalism, integrating AI poses unique challenges and opportunities, particularly in enhancing the quality and efficiency of news reporting. This study explores how LLMs and LMMs can assist journalistic practice by generating contextualised captions for images accompanying news articles. We conducted experiments using the GoodNews dataset to evaluate the ability of LMMs (BLIP-2, GPT-4v, or LLaVA) to incorporate one of two types of context: entire news articles, or extracted named entities. In addition, we compared their performance to a two-stage pipeline composed of a captioning model (BLIP-2, OFA, or ViT-GPT2) with post-hoc contextualisation with LLMs (GPT-4 or LLaMA). We assess a diversity of models, and we find that while the choice of contextualisation model is a significant factor for the two-stage pipelines, this is not the case in the LMMs, where smaller, open-source models perform well compared to proprietary, GPT-powered ones. Additionally, we found that controlling the amount of provided context enhances performance. These results highlight the limitations of a fully automated approach and underscore the necessity for an interactive, human-in-the-loop strategy.

[Arxiv](https://arxiv.org/abs/2408.04331)