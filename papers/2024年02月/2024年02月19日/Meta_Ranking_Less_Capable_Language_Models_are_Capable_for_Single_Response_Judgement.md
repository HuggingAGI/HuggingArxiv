# 元排名机制表明，即便是能力相对较弱的语言模型，在进行单一响应判断时也表现出了足够的能力。

发布时间：2024年02月19日

`LLM应用` `人工智能`

> Meta Ranking: Less Capable Language Models are Capable for Single Response Judgement

# 摘要

> 大型语言模型（LLMs）虽然在众多任务上表现卓越，但仍存在可靠性问题，如产生幻觉。研究表明，像 GPT-4 这样的高效能 LLMs 能有效评估单个回答的可信度，而低效能 LLMs 则常被优化以评估同一问题下不同回答的相对可信度。为此，我们引入了一种创新方法——元排序（Meta Ranking，MR），它不是直接评价回答，而是通过比较目标查询-回答对与参考查询-回答对来进行判断。MR 在推理任务中对 LLM 回答的错误检测展现出了显著效果，即便是低效能 LLMs，在无需微调的情况下也能超越优秀基准。此外，MR 还被证实能提升 LLMs 在查询路由和迭代训练数据筛选两个实际应用中的性能。在查询路由方面，MR 以不到 GPT-4-turbo 一半的令牌消耗实现了相似的性能；在迭代训练数据筛选方面，MR 助力经过指令调整的 LLaMA-7B 和 Phi-2（2.7B 模型）在较少训练样本的情况下显著超越了 Alpaca-13B，彰显了我们方法的巨大潜力。

> Although Large Language Models (LLMs) have demonstrated strong performance on a wide range of tasks, they still face reliability challenges such as hallucination. Previous studies reveal that highly capable LLMs like GPT-4 are effective in judging the reliability of individual responses, while less capable ones are often tuned to evaluate the relative reliability of responses to the same query. To enable less capable LLMs to effectively judge the reliability of individual responses, we propose a novel method named $\textit{Meta}$ $\textit{Ranking}$ (MR). Unlike previous methods, which assess the response directly, we achieve the judgement by comparing the target query-response pair with reference query-response pairs. We found its remarkable effectiveness in error detection for LLM responses on reasoning tasks, where less capable LLMs could outperform strong baselines, even without fine-tuning. We further demonstrate that MR can be used to enhance the performance of LLMs in two practical applications: query routing and iterative training data filtering. The former achieves GPT-4-turbo comparable performance with less than half the token consumption, while the latter makes the instruction-tuned LLaMA-7B and Phi-2, a 2.7B model, significantly surpass Alpaca-13B over fewer training samples, underscoring the high potential of our proposed method.

[Arxiv](https://arxiv.org/abs/2402.12146)