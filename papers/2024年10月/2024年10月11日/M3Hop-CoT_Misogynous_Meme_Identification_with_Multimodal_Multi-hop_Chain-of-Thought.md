# M3Hop-CoT：通过多模态多跳链式思维识别厌女表情包

发布时间：2024年10月11日

`LLM应用` `社交媒体` `性别研究`

> M3Hop-CoT: Misogynous Meme Identification with Multimodal Multi-hop Chain-of-Thought

# 摘要

> 近年来，社交媒体上针对女性的仇恨现象激增，尤其是通过厌恶女性的表情包。这些表情包以微妙和隐晦的方式针对女性，使得自动化检测变得困难。尽管大型语言模型（LLMs）在使用链式思维（CoT）提示进行推理方面表现出色，但往往忽视了文化多样性和视觉模态中的情感与上下文知识。为此，我们提出了多模态多跳链式思维（M3Hop-CoT）框架，结合CLIP分类器和多模态CoT模块，用于厌恶女性表情包的识别。M3Hop-CoT通过三步多模态提示原则，引导情感、目标意识和上下文知识进行表情包分析。实证评估显示，该框架在SemEval-2022任务5（MAMI任务）数据集上表现优异，宏观F1分数突出。此外，我们在多个基准表情包数据集上评估了模型的泛化能力，全面展示了我们方法的有效性。

> In recent years, there has been a significant rise in the phenomenon of hate against women on social media platforms, particularly through the use of misogynous memes. These memes often target women with subtle and obscure cues, making their detection a challenging task for automated systems. Recently, Large Language Models (LLMs) have shown promising results in reasoning using Chain-of-Thought (CoT) prompting to generate the intermediate reasoning chains as the rationale to facilitate multimodal tasks, but often neglect cultural diversity and key aspects like emotion and contextual knowledge hidden in the visual modalities. To address this gap, we introduce a Multimodal Multi-hop CoT (M3Hop-CoT) framework for Misogynous meme identification, combining a CLIP-based classifier and a multimodal CoT module with entity-object-relationship integration. M3Hop-CoT employs a three-step multimodal prompting principle to induce emotions, target awareness, and contextual knowledge for meme analysis. Our empirical evaluation, including both qualitative and quantitative analysis, validates the efficacy of the M3Hop-CoT framework on the SemEval-2022 Task 5 (MAMI task) dataset, highlighting its strong performance in the macro-F1 score. Furthermore, we evaluate the model's generalizability by evaluating it on various benchmark meme datasets, offering a thorough insight into the effectiveness of our approach across different datasets.

[Arxiv](https://arxiv.org/abs/2410.09220)