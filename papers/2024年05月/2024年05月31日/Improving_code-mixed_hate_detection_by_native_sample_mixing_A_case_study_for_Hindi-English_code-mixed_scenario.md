# 本研究探讨了通过本地样本混合策略提升印地语-英语混合文本中的仇恨言论检测效果，为跨语言环境下的内容监管提供了新的视角。

发布时间：2024年05月31日

`LLM应用

理由：这篇论文主要探讨了在多语言语言模型（MLMs）的背景下，如何利用母语仇恨样本来检测代码混合环境中的仇恨言论。研究内容涉及模型的应用层面，即如何改进模型以更好地理解和检测特定类型的文本（仇恨言论），特别是在代码混合的语言环境中。因此，这篇论文更符合LLM应用分类，因为它关注的是语言模型的实际应用和性能提升，而不是模型的理论基础或Agent的设计与实现。` `社交媒体`

> Improving code-mixed hate detection by native sample mixing: A case study for Hindi-English code-mixed scenario

# 摘要

> 仇恨言论检测在NLP领域一直是个难题。在代码混合环境中，任务更为复杂，模型需理解通过语言变化表达的仇恨。由于缺乏大规模注释的仇恨语料库，相关研究甚少。为此，我们提出利用母语仇恨样本来解决这一难题。我们认为，在多语言语言模型（MLMs）的时代，主要依赖母语样本足以检测代码混合环境中的仇恨。尽管MLMs在跨语言仇恨检测中表现出色，但在代码混合环境中的全面评估尚待进行。本文通过一系列严格的实验，旨在填补这一研究空白。我们以印地语-英语代码混合环境为例，利用我们的语言学专业知识进行研究。实验结果显示：(i) 即使少量加入母语仇恨样本，也能显著提升MLMs在代码混合仇恨检测上的性能；(ii) 仅用母语样本训练的MLMs能有效识别代码混合仇恨；(iii) 加入母语样本后，MLMs能更精准地锁定代码混合语境中的仇恨词汇；(iv) 然而，对于主观或讽刺性的仇恨，简单混合母语样本效果有限。我们将公开数据和代码，以便复现实验结果。

> Hate detection has long been a challenging task for the NLP community. The task becomes complex in a code-mixed environment because the models must understand the context and the hate expressed through language alteration. Compared to the monolingual setup, we see very less work on code-mixed hate as large-scale annotated hate corpora are unavailable to make the study. To overcome this bottleneck, we propose using native language hate samples. We hypothesise that in the era of multilingual language models (MLMs), hate in code-mixed settings can be detected by majorly relying on the native language samples. Even though the NLP literature reports the effectiveness of MLMs on hate detection in many cross-lingual settings, their extensive evaluation in a code-mixed scenario is yet to be done. This paper attempts to fill this gap through rigorous empirical experiments. We considered the Hindi-English code-mixed setup as a case study as we have the linguistic expertise for the same. Some of the interesting observations we got are: (i) adding native hate samples in the code-mixed training set, even in small quantity, improved the performance of MLMs for code-mixed hate detection, (ii) MLMs trained with native samples alone observed to be detecting code-mixed hate to a large extent, (iii) The visualisation of attention scores revealed that, when native samples were included in training, MLMs could better focus on the hate emitting words in the code-mixed context, and (iv) finally, when hate is subjective or sarcastic, naively mixing native samples doesn't help much to detect code-mixed hate. We will release the data and code repository to reproduce the reported results.

[Arxiv](https://arxiv.org/abs/2405.20755)