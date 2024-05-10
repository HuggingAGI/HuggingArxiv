# 解码人类判断，构建预测模型：探索代码混合语言的可接受性之谜

发布时间：2024年05月09日

`LLM应用

这篇论文主要关注的是多语言大型语言模型（MLLMs）在混合代码句子生成任务中的应用，特别是如何通过创建一个新的数据集（Cline）来提高生成文本的自然性和可接受性。论文通过实验比较了不同模型的性能，并强调了微调的多语言大型语言模型在混合代码任务上的优势。这与LLM应用的分类相符，因为它涉及到了大型语言模型的实际应用和性能改进，而不是专注于理论研究或Agent的设计与实现。` `多语言处理`

> From Human Judgements to Predictive Models: Unravelling Acceptability in Code-Mixed Sentences

# 摘要

> 现有的混合代码句子分析与生成方法，并未直接模拟“自然性”与“可接受性”，而是依赖训练语料库来反映可接受混合代码句子的分布。为了区分自然混合代码文本并实现质量控制生成，我们创建了Cline数据集，它包含了人类对英语-印地语混合代码文本可接受性的判断。Cline拥有16,642个句子，样本来自合成生成和社交媒体收集。分析发现，常用的混合代码度量与人类判断关联性低，凸显了Cline的重要性。实验显示，微调的多语言大型语言模型在混合代码任务上优于简单MLP模型。XLM-Roberta和Bernice在各种配置下超越了IndicBERT。与ChatGPT相比，微调的MLLMs在更大数据上表现更佳，为混合代码任务的改进提供了空间。我们的模型在从英语-印地语到英语-泰卢固语的可接受性判断上优于随机基线，为其他混合代码语言对的研究开辟了新途径。我们公开了人工标注数据集、训练模型、混合代码语料库及生成与训练代码。

> Current computational approaches for analysing or generating code-mixed sentences do not explicitly model "naturalness" or "acceptability" of code-mixed sentences, but rely on training corpora to reflect distribution of acceptable code-mixed sentences. Modelling human judgement for the acceptability of code-mixed text can help in distinguishing natural code-mixed text and enable quality-controlled generation of code-mixed text. To this end, we construct Cline - a dataset containing human acceptability judgements for English-Hindi (en-hi) code-mixed text. Cline is the largest of its kind with 16,642 sentences, consisting of samples sourced from two sources: synthetically generated code-mixed text and samples collected from online social media. Our analysis establishes that popular code-mixing metrics such as CMI, Number of Switch Points, Burstines, which are used to filter/curate/compare code-mixed corpora have low correlation with human acceptability judgements, underlining the necessity of our dataset. Experiments using Cline demonstrate that simple Multilayer Perceptron (MLP) models trained solely on code-mixing metrics are outperformed by fine-tuned pre-trained Multilingual Large Language Models (MLLMs). Specifically, XLM-Roberta and Bernice outperform IndicBERT across different configurations in challenging data settings. Comparison with ChatGPT's zero and fewshot capabilities shows that MLLMs fine-tuned on larger data outperform ChatGPT, providing scope for improvement in code-mixed tasks. Zero-shot transfer from English-Hindi to English-Telugu acceptability judgments using our model checkpoints proves superior to random baselines, enabling application to other code-mixed language pairs and providing further avenues of research. We publicly release our human-annotated dataset, trained checkpoints, code-mix corpus, and code for data generation and model training.

[Arxiv](https://arxiv.org/abs/2405.05572)