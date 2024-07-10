# 预训练模型中的基于片段的交互式机器翻译

发布时间：2024年07月09日

`LLM应用` `机器翻译` `交互式系统`

> Segment-Based Interactive Machine Translation for Pre-trained Models

# 摘要

> 预训练的大型语言模型 (LLM) 正逐渐在众多应用中得到广泛应用。本研究聚焦于这些模型在交互式机器翻译 (IMT) 环境中的应用，特别选用了 mBART 和 mT5 进行实验。系统通过用户反馈，在每次交互中生成精准翻译。神经机器翻译 (NMT) 模型依据反馈提出初步翻译假设，用户则验证并修正单词，直至翻译准确无误。我们在基准数据集上对比了 mBART、mT5 与最先进 (SoTA) 机器翻译模型的性能，评估了用户努力、单词敲击比 (WSR)、关键敲击比 (KSR) 和鼠标动作比 (MAR)。实验显示，mBART 性能与 SoTA 模型不相上下，表明其在 IMT 领域具有应用潜力。这一发现还启示我们，为交互式环境开发新机器翻译模型时，应考虑利用这些预训练模型，它们在特定领域展现出与 SoTA 相当的性能，凸显了定制化调整的潜在优势。

> Pre-trained large language models (LLM) are starting to be widely used in many applications. In this work, we explore the use of these models in interactive machine translation (IMT) environments. In particular, we have chosen mBART (multilingual Bidirectional and Auto-Regressive Transformer) and mT5 (multilingual Text-to-Text Transfer Transformer) as the LLMs to perform our experiments. The system generates perfect translations interactively using the feedback provided by the user at each iteration. The Neural Machine Translation (NMT) model generates a preliminary hypothesis with the feedback, and the user validates new correct segments and performs a word correction--repeating the process until the sentence is correctly translated. We compared the performance of mBART, mT5, and a state-of-the-art (SoTA) machine translation model on a benchmark dataset regarding user effort, Word Stroke Ratio (WSR), Key Stroke Ratio (KSR), and Mouse Action Ratio (MAR). The experimental results indicate that mBART performed comparably with SoTA models, suggesting that it is a viable option for this field of IMT. The implications of this finding extend to the development of new machine translation models for interactive environments, as it indicates that some novel pre-trained models exhibit SoTA performance in this domain, highlighting the potential benefits of adapting these models to specific needs.

[Arxiv](https://arxiv.org/abs/2407.06990)