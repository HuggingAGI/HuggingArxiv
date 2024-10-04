# CulturalBench：一个稳健、多样且具有挑战性的基准，旨在衡量大型语言模型（LLMs）的文化知识水平。

发布时间：2024年10月03日

`LLM应用` `文化研究` `人工智能`

> CulturalBench: a Robust, Diverse and Challenging Benchmark on Measuring the (Lack of) Cultural Knowledge of LLMs

# 摘要

> 为了让大型语言模型 (LLM) 在多元文化中更实用，建立有效的文化知识基准至关重要。我们推出了 CulturalBench，包含 1,227 个由人类编写和验证的问题，覆盖 45 个全球区域，特别是那些代表性不足的地区。这些问题涉及 17 个不同主题，从饮食习惯到社交礼仪。我们通过 CulturalBench-Easy 和 CulturalBench-Hard 两种设置评估模型，发现 LLM 对提问方式的差异非常敏感。尽管 GPT-4o 在某些方面表现优异，但所有模型在涉及南美和中东的问题上表现普遍不佳，显示出对多元文化理解的挑战。

> To make large language models (LLMs) more helpful across diverse cultures, it is essential to have effective cultural knowledge benchmarks to measure and track our progress. Effective benchmarks need to be robust, diverse, and challenging. We introduce CulturalBench: a set of 1,227 human-written and human-verified questions for effectively assessing LLMs' cultural knowledge, covering 45 global regions including the underrepresented ones like Bangladesh, Zimbabwe, and Peru. Questions - each verified by five independent annotators - span 17 diverse topics ranging from food preferences to greeting etiquettes. We evaluate models on two setups: CulturalBench-Easy and CulturalBench-Hard which share the same questions but asked differently. We find that LLMs are sensitive to such difference in setups (e.g., GPT-4o with 27.3% difference). Compared to human performance (92.6% accuracy), CulturalBench-Hard is more challenging for frontier LLMs with the best performing model (GPT-4o) at only 61.5% and the worst (Llama3-8b) at 21.4%. Moreover, we find that LLMs often struggle with tricky questions that have multiple correct answers (e.g., What utensils do the Chinese usually use?), revealing a tendency to converge to a single answer. Our results also indicate that OpenAI GPT-4o substantially outperform other proprietary and open source models in questions related to all but one region (Oceania). Nonetheless, all models consistently underperform on questions related to South America and the Middle East.

[Arxiv](https://arxiv.org/abs/2410.02677)