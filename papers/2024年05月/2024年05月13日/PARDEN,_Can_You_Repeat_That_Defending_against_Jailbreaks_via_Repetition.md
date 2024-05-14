# PARDEN，请再说一次？——以重复为盾，抵御越狱之矛

发布时间：2024年05月13日

`LLM应用

这篇论文讨论了大型语言模型（LLMs）的安全性问题，特别是针对越狱风险的防范。它提出了一种名为“保护盾”的新策略，利用LLM自身来检测和预防不希望的行为，并通过PARDEN方法在实验中展示了其有效性。这种方法直接应用于LLM的实际应用场景中，旨在提高模型的安全性，因此属于LLM应用类别。` `人工智能安全`

> PARDEN, Can You Repeat That? Defending against Jailbreaks via Repetition

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域大放异彩，然而，即便经过严密的安全对齐，如Llama 2和Claude 2等模型仍面临越狱风险，引发安全隐忧。为此，我们提出了一种创新的“保护盾”策略，即利用LLM自身来检测和防范不希望的行为。尽管现有方法如自我分类有毒内容效果有限，我们发现这是因为模型在训练中形成了自我审查的习惯，而自我分类则将其推向了分类模式。为此，我们推出了PARDEN，一种无需微调或模型内部访问的新方法，它通过让模型重复输出来规避领域转移。实验证明，PARDEN在Llama-2和Claude-2上的越狱检测能力远超现有基线。在Llama2-7B模型上，PARDEN在保持90%真阳性率的同时，将假阳性率从24.8%大幅降至2.0%。代码和数据已公开，详情请访问https://github.com/Ed-Zh/PARDEN。

> Large language models (LLMs) have shown success in many natural language processing tasks. Despite rigorous safety alignment processes, supposedly safety-aligned LLMs like Llama 2 and Claude 2 are still susceptible to jailbreaks, leading to security risks and abuse of the models. One option to mitigate such risks is to augment the LLM with a dedicated "safeguard", which checks the LLM's inputs or outputs for undesired behaviour. A promising approach is to use the LLM itself as the safeguard. Nonetheless, baseline methods, such as prompting the LLM to self-classify toxic content, demonstrate limited efficacy. We hypothesise that this is due to domain shift: the alignment training imparts a self-censoring behaviour to the model ("Sorry I can't do that"), while the self-classify approach shifts it to a classification format ("Is this prompt malicious"). In this work, we propose PARDEN, which avoids this domain shift by simply asking the model to repeat its own outputs. PARDEN neither requires finetuning nor white box access to the model. We empirically verify the effectiveness of our method and show that PARDEN significantly outperforms existing jailbreak detection baselines for Llama-2 and Claude-2. Code and data are available at https://github.com/Ed-Zh/PARDEN.
  We find that PARDEN is particularly powerful in the relevant regime of high True Positive Rate (TPR) and low False Positive Rate (FPR). For instance, for Llama2-7B, at TPR equal to 90%, PARDEN accomplishes a roughly 11x reduction in the FPR from 24.8% to 2.0% on the harmful behaviours dataset.

[Arxiv](https://arxiv.org/abs/2405.07932)