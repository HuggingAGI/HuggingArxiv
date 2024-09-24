# 通过 MBR 解码，从 NMT 和 LLM 的候选翻译中精选出最终版本：HW-TSC 为 WMT24 通用机器翻译任务提交的方案

发布时间：2024年09月23日

`LLM应用` `翻译服务` `机器翻译`

> Choose the Final Translation from NMT and LLM hypotheses Using MBR Decoding: HW-TSC's Submission to the WMT24 General MT Shared Task

# 摘要

> 本文展示了华为翻译服务中心 (HW-TSC) 在 WMT24 通用机器翻译 (MT) 任务中的英汉 (en2zh) 语言对提交。我们沿用了往年的训练策略，如正则化 dropout、双向训练等，并基于深度 Transformer-big 架构训练 NMT 模型。此外，我们还引入了继续预训练、监督微调及对比偏好优化，以训练基于 LLM 的 MT 模型。通过 MBR 解码从多个候选中选出最佳翻译，我们的提交在最终评估中表现出色。

> This paper presents the submission of Huawei Translate Services Center (HW-TSC) to the WMT24 general machine translation (MT) shared task, where we participate in the English to Chinese (en2zh) language pair. Similar to previous years' work, we use training strategies such as regularized dropout, bidirectional training, data diversification, forward translation, back translation, alternated training, curriculum learning, and transductive ensemble learning to train the neural machine translation (NMT) model based on the deep Transformer-big architecture. The difference is that we also use continue pre-training, supervised fine-tuning, and contrastive preference optimization to train the large language model (LLM) based MT model. By using Minimum Bayesian risk (MBR) decoding to select the final translation from multiple hypotheses for NMT and LLM-based MT models, our submission receives competitive results in the final evaluation.

[Arxiv](https://arxiv.org/abs/2409.14800)