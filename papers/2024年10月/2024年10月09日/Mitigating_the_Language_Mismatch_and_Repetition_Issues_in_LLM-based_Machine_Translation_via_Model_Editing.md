# 通过模型编辑技术，我们致力于解决基于LLM的机器翻译中存在的语言不匹配和重复问题。

发布时间：2024年10月09日

`LLM应用` `机器翻译`

> Mitigating the Language Mismatch and Repetition Issues in LLM-based Machine Translation via Model Editing

# 摘要

> LLM 在 NLP 领域掀起革命，但在某些下游任务中仍显不足。我们专注于利用 LLM 进行机器翻译，发现语言不匹配和重复两大错误频发，严重影响翻译质量。为此，我们探索通过模型编辑方法，如定位并停用负责错误的 FFN 神经元，来缓解这些问题。然而，直接应用这些方法效果有限，甚至损害整体翻译质量，表明这些定位组件对确保翻译质量至关重要。因此，我们提出通过不同语言设置下定位结果的交集来细化组件，过滤无关信息。实验证明，我们的方法能有效减少语言不匹配和重复，同时保持或提升整体翻译质量。

> Large Language Models (LLMs) have recently revolutionized the NLP field, while they still fall short in some specific down-stream tasks. In the work, we focus on utilizing LLMs to perform machine translation, where we observe that two patterns of errors frequently occur and drastically affect the translation quality: language mismatch and repetition. The work sets out to explore the potential for mitigating these two issues by leveraging model editing methods, e.g., by locating Feed-Forward Network (FFN) neurons or something that are responsible for the errors and deactivating them in the inference time. We find that directly applying such methods either limited effect on the targeted errors or has significant negative side-effect on the general translation quality, indicating that the located components may also be crucial for ensuring machine translation with LLMs on the rails. To this end, we propose to refine the located components by fetching the intersection of the locating results under different language settings, filtering out the aforementioned information that is irrelevant to targeted errors. The experiment results empirically demonstrate that our methods can effectively reduce the language mismatch and repetition ratios and meanwhile enhance or keep the general translation quality in most cases.

[Arxiv](https://arxiv.org/abs/2410.07054)