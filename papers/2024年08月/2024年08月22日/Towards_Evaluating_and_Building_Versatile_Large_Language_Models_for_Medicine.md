# 探索构建与评估医学领域多功能大型语言模型的路径

发布时间：2024年08月22日

`LLM应用` `人工智能`

> Towards Evaluating and Building Versatile Large Language Models for Medicine

# 摘要

> 本研究中，我们推出了 MedS-Bench，一个专为评估大型语言模型在临床场景中性能的综合基准。与侧重于选择题的现有基准不同，MedS-Bench 覆盖了从临床报告摘要到治疗建议等 11 项高级临床任务。我们测试了 MEDITRON、Mistral 等六大领先 LLM，发现即便是最先进的模型在这些复杂任务上也力不从心。为此，我们创建了 MedS-Ins，一个包含 1350 万样本的医学指令调整数据集，涵盖 122 项任务。通过在一个轻量级开源医学语言模型上进行指令调整，我们验证了数据集的有效性，新模型 MMedIns-Llama 3 在多项临床任务上表现卓越。我们已开放 MedS-Ins 数据集，并设立动态排行榜，以推动 LLM 在医学领域的应用发展。排行榜与 Github 链接如下：https://henrychur.github.io/MedS-Bench/ 和 https://github.com/MAGIC-AI4Med/MedS-Ins。

> In this study, we present MedS-Bench, a comprehensive benchmark designed to evaluate the performance of large language models (LLMs) in clinical contexts. Unlike existing benchmarks that focus on multiple-choice question answering, MedS-Bench spans 11 high-level clinical tasks, including clinical report summarization, treatment recommendations, diagnosis, named entity recognition, and medical concept explanation, among others. We evaluated six leading LLMs, e.g., MEDITRON, Mistral, InternLM 2, Llama 3, GPT-4, and Claude-3.5 using few-shot prompting, and found that even the most sophisticated models struggle with these complex tasks. To address these limitations, we developed MedS-Ins, a large-scale instruction tuning dataset for medicine. MedS-Ins comprises 58 medically oriented language corpora, totaling 13.5 million samples across 122 tasks. To demonstrate the dataset's utility, we conducted a proof-of-concept experiment by performing instruction tuning on a lightweight, open-source medical language model. The resulting model, MMedIns-Llama 3, significantly outperformed existing models across nearly all clinical tasks. To promote further advancements in the application of LLMs to clinical challenges, we have made the MedS-Ins dataset fully accessible and invite the research community to contribute to its expansion.Additionally, we have launched a dynamic leaderboard for MedS-Bench, which we plan to regularly update the test set to track progress and enhance the adaptation of general LLMs to the medical domain. Leaderboard: https://henrychur.github.io/MedS-Bench/. Github: https://github.com/MAGIC-AI4Med/MedS-Ins.

[Arxiv](https://arxiv.org/abs/2408.12547)