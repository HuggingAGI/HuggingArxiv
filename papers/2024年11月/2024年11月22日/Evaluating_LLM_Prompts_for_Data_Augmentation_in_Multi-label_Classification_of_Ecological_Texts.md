# 评估用于生态文本多标签分类中数据增强的 LLM 提示语

发布时间：2024年11月22日

`LLM应用` `社交媒体`

> Evaluating LLM Prompts for Data Augmentation in Multi-label Classification of Ecological Texts

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）任务中起着至关重要的作用，在诸如翻译、总结和文本分类等领域提升了对人类语言的理解、生成及处理水平。以往研究表明，基于指令的LLMs能有效用于数据增强，从而生成多样且逼真的文本样本。本研究采用基于提示的数据增强方法来检测俄罗斯社交媒体中提及的绿色实践。检测社交媒体中的绿色实践有助于了解其普及程度，并有助于制定扩大环保行动以缓解环境问题的建议。我们在多标签分类任务中对多个用于增强文本的提示进行了评估，包括使用LLMs重写现有数据集、生成新数据或者将两种方式相结合。我们的结果显示，与仅在原始数据集上微调的模型相比，所有策略都提高了分类性能，在多数情况下都超越了基线。其中，在对原始文本进行改写并清晰指明相关类别的提示下取得了最佳结果。

> Large language models (LLMs) play a crucial role in natural language processing (NLP) tasks, improving the understanding, generation, and manipulation of human language across domains such as translating, summarizing, and classifying text. Previous studies have demonstrated that instruction-based LLMs can be effectively utilized for data augmentation to generate diverse and realistic text samples. This study applied prompt-based data augmentation to detect mentions of green practices in Russian social media. Detecting green practices in social media aids in understanding their prevalence and helps formulate recommendations for scaling eco-friendly actions to mitigate environmental issues. We evaluated several prompts for augmenting texts in a multi-label classification task, either by rewriting existing datasets using LLMs, generating new data, or combining both approaches. Our results revealed that all strategies improved classification performance compared to the models fine-tuned only on the original dataset, outperforming baselines in most cases. The best results were obtained with the prompt that paraphrased the original text while clearly indicating the relevant categories.

[Arxiv](https://arxiv.org/abs/2411.14896)