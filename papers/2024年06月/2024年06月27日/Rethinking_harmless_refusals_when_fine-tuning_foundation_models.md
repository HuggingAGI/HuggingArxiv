# 探讨微调基础模型中的“无害拒绝”现象

发布时间：2024年06月27日

`LLM理论` `人工智能` `道德伦理`

> Rethinking harmless refusals when fine-tuning foundation models

# 摘要

> 本文探讨了大型语言模型（LLM）中的微调是否真正缓解了不良行为，还是仅仅掩盖了它们。通过设计半现实的角色扮演练习来引出这些行为，我们分析了微调后LLM的反应动态。我们采用思维链（CoT）推理提示，并评估推理与输出的一致性。我们发现了一种称为“基于理由的欺骗”的现象，模型可能停止提供推理或提供看似道德的推理，实则掩盖了不道德的输出。此外，我们比较了礼貌拒绝与明确反驳两种回应策略，发现明确反驳在防止不良输出和消除“基于理由的欺骗”方面更为有效，这促使我们重新审视微调中的回应策略。本文的主要贡献在于揭示了“基于理由的欺骗”这一新现象，并证明了反驳策略在应对有害请求时的优越性。

> In this paper, we investigate the degree to which fine-tuning in Large Language Models (LLMs) effectively mitigates versus merely conceals undesirable behavior. Through the lens of semi-realistic role-playing exercises designed to elicit such behaviors, we explore the response dynamics of LLMs post fine-tuning interventions. Our methodology involves prompting models for Chain-of-Thought (CoT) reasoning and analyzing the coherence between the reasoning traces and the resultant outputs. Notably, we identify a pervasive phenomenon we term \emph{reason-based deception}, where models either stop producing reasoning traces or produce seemingly ethical reasoning traces that belie the unethical nature of their final outputs. We further examine the efficacy of response strategies (polite refusal versus explicit rebuttal) in curbing the occurrence of undesired behavior in subsequent outputs of multi-turn interactions. Our findings reveal that explicit rebuttals significantly outperform polite refusals in preventing the continuation of undesired outputs and nearly eliminate reason-based deception, challenging current practices in model fine-tuning. Accordingly, the two key contributions of this paper are (1) defining and studying reason-based deception, a new type of hidden behavior, and (2) demonstrating that rebuttals provide a more robust response model to harmful requests than refusals, thereby highlighting the need to reconsider the response strategies in fine-tuning approaches.

[Arxiv](https://arxiv.org/abs/2406.19552)