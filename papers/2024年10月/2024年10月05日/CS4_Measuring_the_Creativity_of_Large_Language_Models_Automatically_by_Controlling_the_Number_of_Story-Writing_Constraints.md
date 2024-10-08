# CS4：通过调控故事创作的限制条件，自动评估大型语言模型的创造力

发布时间：2024年10月05日

`LLM应用` `文学创作` `人工智能`

> CS4: Measuring the Creativity of Large Language Models Automatically by Controlling the Number of Story-Writing Constraints

# 摘要

> 评估 LLM 在故事创作中的创造力颇具挑战，因为它们生成的故事虽看似新颖，却可能与训练数据中的某些故事高度相似。为此，我们推出了 CS4 基准数据集，通过调整提示中的要求与约束，提升提示的具体性，从而限制 LLM 重复高质量叙事。CS4 使我们能在无人工干预下，间接衡量 LLM 的创造力。  实验显示，LLaMA、Gemma 和 Mistral 在处理高度具体提示时，创造力面临挑战，且在不同约束下表现各异，需在指令遵循与叙事连贯间寻求平衡。OLMo 实验表明，LHF 虽能助 LLM 精选训练数据中的佳作，但在激发其创作全新故事方面作用有限。CS4 基准已公开于 https://github.com/anirudhlakkaraju/cs4_benchmark。

> Evaluating the creativity of large language models (LLMs) in story writing is difficult because LLM-generated stories could seemingly look creative but be very similar to some existing stories in their huge and proprietary training corpus. To overcome this challenge, we introduce a novel benchmark dataset with varying levels of prompt specificity: CS4 ($\mathbf{C}$omparing the $\mathbf{S}$kill of $\mathbf{C}$reating $\mathbf{S}$tories by $\mathbf{C}$ontrolling the $\mathbf{S}$ynthesized $\mathbf{C}$onstraint $\mathbf{S}$pecificity). By increasing the number of requirements/constraints in the prompt, we can increase the prompt specificity and hinder LLMs from retelling high-quality narratives in their training data. Consequently, CS4 empowers us to indirectly measure the LLMs' creativity without human annotations.
  Our experiments on LLaMA, Gemma, and Mistral not only highlight the creativity challenges LLMs face when dealing with highly specific prompts but also reveal that different LLMs perform very differently under different numbers of constraints and achieve different balances between the model's instruction-following ability and narrative coherence. Additionally, our experiments on OLMo suggest that Learning from Human Feedback (LHF) can help LLMs select better stories from their training data but has limited influence in boosting LLMs' ability to produce creative stories that are unseen in the training corpora. The benchmark is released at https://github.com/anirudhlakkaraju/cs4_benchmark.

[Arxiv](https://arxiv.org/abs/2410.04197)