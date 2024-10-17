# 超越准确性：探索从弱到强的泛化在安全、毒性和法律推理中的应用

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Weak-to-Strong Generalization beyond Accuracy: a Pilot Study in Safety, Toxicity, and Legal Reasoning

# 摘要

> 随着 LLM 的进步，确保其与人类价值观的一致性变得至关重要。传统方法依赖人类反馈微调模型，但面对输出超越人类理解的超人类模型，这一方法面临巨大挑战。近期研究采用弱监督者从更强模型中提取知识，但现有研究与实际对齐目标存在差异。本文将对齐相关的弱到强生成扩展至实际对齐任务，通过安全性、毒性和法律推理三个复杂任务，展示了弱到强生成的普遍现象。我们还探讨了提升对齐性能的有效策略，并总结了特定对齐任务的挑战与解决方案，旨在推动弱到强泛化研究。代码已发布于 https://github.com/yeruimeng/WTS.git。

> As large language models (LLMs) continue to advance, ensuring their alignment with human values becomes increasingly critical. Traditional alignment methods heavily rely on human feedback to fine-tune models. With the emergence of superhuman models whose outputs may surpass human understanding, evaluating and aligning these models using human judgments poses significant challenges. To address the challenges, recent works use weak supervisors to elicit knowledge from much stronger models. However, there are important disanalogies between the empirical setup in the existing works and the genuine goal of alignment. We remark that existing works investigate the phenomenon of weak-to-strong generation in analogous setup (i.e., binary classification), rather than practical alignment-relevant tasks (e.g., safety). In this paper, we bridge this gap by extending weak-to-strong generation to the context of practical alignment. We empirically demonstrate the widespread phenomenon of weak-to-strong generation in three complicated alignment tasks: safety, toxicity, and legal reasoning}. Furthermore, we explore efficient strategies for improving alignment performance to enhance the quality of model outcomes. Lastly, we summarize and analyze the challenges and potential solutions in regard to specific alignment tasks, which we hope to catalyze the research progress on the topic of weak-to-strong generalization. Our code is released at https://github.com/yeruimeng/WTS.git.

[Arxiv](https://arxiv.org/abs/2410.12621)