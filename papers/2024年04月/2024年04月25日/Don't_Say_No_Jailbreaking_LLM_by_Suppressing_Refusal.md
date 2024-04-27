# 切莫拒绝：抑制回绝行为以解锁语言巨模的潜能

发布时间：2024年04月25日

`LLM应用` `人工智能安全`

> Don't Say No: Jailbreaking LLM by Suppressing Refusal

# 摘要

> 保障大型语言模型（LLMs）的安全一致性对于生成符合人类价值观的响应非常关键。尽管LLMs能够识别并规避有害的查询，但它们仍然容易受到“越狱”攻击的威胁，这类攻击通过精心构造的提示诱使模型生成有害内容。其中一种越狱攻击手段是将任务转化为对抗性攻击，诱导LLMs给出肯定的回答。但是，这种常见的GCG攻击手段成功率并不高。本研究中，为了更深入地研究越狱攻击，我们提出了DSN（不要说不）攻击，它不仅诱导LLMs生成肯定的回答，还创新性地增加了阻止拒绝的目标。此外，越狱攻击的评估工作也面临挑战，因为直接且精确地评估攻击的有害程度相当困难。目前使用的评估方法，比如拒绝关键词匹配，存在局限性，因为它会产生许多误报和漏报。为了应对这一挑战，我们提出了一个集成评估流程，包括自然语言推理（NLI）的矛盾评估和两个外部LLM评估器。广泛的实验证明了DSN攻击的有效性，以及与基线方法相比，集成评估的高效性。

> Ensuring the safety alignment of Large Language Models (LLMs) is crucial to generating responses consistent with human values. Despite their ability to recognize and avoid harmful queries, LLMs are vulnerable to "jailbreaking" attacks, where carefully crafted prompts elicit them to produce toxic content. One category of jailbreak attacks is reformulating the task as adversarial attacks by eliciting the LLM to generate an affirmative response. However, the typical attack in this category GCG has very limited attack success rate. In this study, to better study the jailbreak attack, we introduce the DSN (Don't Say No) attack, which prompts LLMs to not only generate affirmative responses but also novelly enhance the objective to suppress refusals. In addition, another challenge lies in jailbreak attacks is the evaluation, as it is difficult to directly and accurately assess the harmfulness of the attack. The existing evaluation such as refusal keyword matching has its own limitation as it reveals numerous false positive and false negative instances. To overcome this challenge, we propose an ensemble evaluation pipeline incorporating Natural Language Inference (NLI) contradiction assessment and two external LLM evaluators. Extensive experiments demonstrate the potency of the DSN and the effectiveness of ensemble evaluation compared to baseline methods.

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/examples.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/DSN_mainfig.jpg)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/sliding.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/ASR_step_Llama_only_searching.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/ASR_step_Llama_both.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/ASR_step_Vicuna_only_searching.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/ASR_step_Vicuna_both.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/max_ASR_vs_alpha_Llama.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/max_ASR_vs_alpha_Vicuna.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/AUROC.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/max_ASR_vs_alpha_Llama_eval_ensemble.png)

![切莫拒绝：抑制回绝行为以解锁语言巨模的潜能](../../../paper_images/2404.16369/max_ASR_vs_alpha_Vicuna_eval_ensemble.png)

[Arxiv](https://arxiv.org/abs/2404.16369)