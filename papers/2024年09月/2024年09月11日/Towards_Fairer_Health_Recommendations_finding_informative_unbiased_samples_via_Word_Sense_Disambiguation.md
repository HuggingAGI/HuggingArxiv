# 探索更公平的健康建议：利用词义消歧技术，寻找信息丰富且无偏的样本。

发布时间：2024年09月11日

`LLM应用` `人工智能`

> Towards Fairer Health Recommendations: finding informative unbiased samples via Word Sense Disambiguation

# 摘要

> 高风险应用依赖于偏差数据训练的模型，导致偏差预测，常伤害弱势群体，引发广泛担忧。特别是，偏差医疗数据可能危及患者护理，扩大健康差距。最近提出的“通过AI实现公平”框架建议，应通过AI消除数据偏差，而非纠正模型偏差。受此启发，我们使用NLP模型（包括LLM）检测医学课程偏差，并在4105个医学专家标注的金标准数据集上评估。我们扩充负样本集，包含社会标识符术语的未标注文本，但某些术语（如种族相关）含义多样（如“脊髓白质”）。为此，我们提出使用词义消歧模型剔除无关句子，提升数据集质量。随后，我们评估了微调的BERT和GPT模型（零样本和少样本提示）。结果显示，LLM虽在多NLP任务中表现优异，但不适用于偏差检测，而微调的BERT模型在各评估指标上表现出色。

> There have been growing concerns around high-stake applications that rely on models trained with biased data, which consequently produce biased predictions, often harming the most vulnerable. In particular, biased medical data could cause health-related applications and recommender systems to create outputs that jeopardize patient care and widen disparities in health outcomes. A recent framework titled Fairness via AI posits that, instead of attempting to correct model biases, researchers must focus on their root causes by using AI to debias data. Inspired by this framework, we tackle bias detection in medical curricula using NLP models, including LLMs, and evaluate them on a gold standard dataset containing 4,105 excerpts annotated by medical experts for bias from a large corpus. We build on previous work by coauthors which augments the set of negative samples with non-annotated text containing social identifier terms. However, some of these terms, especially those related to race and ethnicity, can carry different meanings (e.g., "white matter of spinal cord"). To address this issue, we propose the use of Word Sense Disambiguation models to refine dataset quality by removing irrelevant sentences. We then evaluate fine-tuned variations of BERT models as well as GPT models with zero- and few-shot prompting. We found LLMs, considered SOTA on many NLP tasks, unsuitable for bias detection, while fine-tuned BERT models generally perform well across all evaluated metrics.

[Arxiv](https://arxiv.org/abs/2409.07424)