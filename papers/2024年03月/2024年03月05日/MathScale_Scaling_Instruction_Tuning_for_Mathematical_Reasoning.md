# MathScale 是一种专门针对数学推理能力提升而设计的指令调优扩展方案。

发布时间：2024年03月05日

`LLM应用`

> MathScale: Scaling Instruction Tuning for Mathematical Reasoning

# 摘要

> 尽管LLMs在诸多问题解决领域表现出卓越才能，但在数学难题破解上仍有待加强。为此，我们创新提出了一种名为MathScale的方法，它简洁而高效，利用尖端LLMs（比如GPT-3.5）生成高质量的数学推理数据。灵感来源于人类数学学习的认知过程，MathScale先从基础数学问题中提炼出主题和知识点，构建概念网络，再由此生成全新的数学题目。此方法在拓展数学数据集规模上表现出了强大的扩展性，并成功创建了一个拥有两百万题数学问答对的数学推理数据集——MathScaleQA。为了全方位测评LLMs的数学推理力，我们精心打造了{\sc MwpBench}这一涵盖K-12至大学及竞赛级别的数学应用题综合评测基准，包含了诸如GSM8K和MATH等在内的十大数据集。将MathScaleQA用于开源LLMs（例如LLaMA-2和Mistral）的微调训练后，其数学推理能力得到显著提升。最终，在{\sc MwpBench}基准测试中，MathScale-7B脱颖而出，横扫各大数据集，分别在微观平均准确率和宏观平均准确率上超越同等规模最优模型42.9\%和43.7\%，树立了全新标杆。

> Large language models (LLMs) have demonstrated remarkable capabilities in problem-solving. However, their proficiency in solving mathematical problems remains inadequate. We propose MathScale, a simple and scalable method to create high-quality mathematical reasoning data using frontier LLMs (e.g., {\tt GPT-3.5}). Inspired by the cognitive mechanism in human mathematical learning, it first extracts topics and knowledge points from seed math questions and then build a concept graph, which is subsequently used to generate new math questions. MathScale exhibits effective scalability along the size axis of the math dataset that we generate. As a result, we create a mathematical reasoning dataset (MathScaleQA) containing two million math question-answer pairs. To evaluate mathematical reasoning abilities of LLMs comprehensively, we construct {\sc MwpBench}, a benchmark of Math Word Problems, which is a collection of ten datasets (including GSM8K and MATH) covering K-12, college, and competition level math problems. We apply MathScaleQA to fine-tune open-source LLMs (e.g., LLaMA-2 and Mistral), resulting in significantly improved capabilities in mathematical reasoning. Evaluated on {\sc MwpBench}, MathScale-7B achieves state-of-the-art performance across all datasets, surpassing its best peers of equivalent size by 42.9\% in micro average accuracy and 43.7\% in macro average accuracy, respectively.

[Arxiv](https://arxiv.org/abs/2403.02884)