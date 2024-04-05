# 英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？

发布时间：2024年04月03日

`LLM应用` `语言模型` `代词使用`

> Robust Pronoun Use Fidelity with English LLMs: Are they Reasoning, Repeating, or Just Biased?

# 摘要

> 随着语言模型应用日益广泛，确保个体使用稳健、准确且无害的代词变得至关重要。然而，以往的研究往往只针对这些要素中的一两个进行探讨。为了全面评估这一目标的实现情况，我们提出了代词使用保真度的测试任务：在一个已引入相关实体和代词的上下文中，要求模型在后续内容中正确地重复使用相应的代词，忽略任何可能的干扰项。我们构建了一个包含逾五百万案例的精细数据集，用以评估英语中代词使用的正确性，并以此检验了37种流行大型语言模型在不同架构（包括仅编码器、仅解码器及编码器-解码器组合）和规模（参数量从1100万到700亿不等）的表现。研究发现，在没有干扰项干扰的情况下，模型大多能够准确重复之前指定的代词，但在处理she/her/her、单数they和新代词时表现欠佳。而且，模型对代词的忠实度并不稳定，容易受到外界干扰。仅增加一句含有干扰代词的内容，准确率就会平均下降34%。当干扰句子达到五句时，仅解码器模型的准确率会下降52%，而仅编码器模型则下降13%。这一发现揭示了当前广泛使用的大型语言模型在推理和处理不同代词方面存在显著不足，尽管这些任务对人类而言轻而易举。我们呼吁研究者们关注并弥补这些在偏见和推理领域的缺陷。

> Robust, faithful and harm-free pronoun use for individuals is an important goal for language models as their use increases, but prior work tends to study only one or two of these components at a time. To measure progress towards the combined goal, we introduce the task of pronoun use fidelity: given a context introducing a co-referring entity and pronoun, the task is to reuse the correct pronoun later, independent of potential distractors. We present a carefully-designed dataset of over 5 million instances to evaluate pronoun use fidelity in English, and we use it to evaluate 37 popular large language models across architectures (encoder-only, decoder-only and encoder-decoder) and scales (11M-70B parameters). We find that while models can mostly faithfully reuse previously-specified pronouns in the presence of no distractors, they are significantly worse at processing she/her/her, singular they and neopronouns. Additionally, models are not robustly faithful to pronouns, as they are easily distracted. With even one additional sentence containing a distractor pronoun, accuracy drops on average by 34%. With 5 distractor sentences, accuracy drops by 52% for decoder-only models and 13% for encoder-only models. We show that widely-used large language models are still brittle, with large gaps in reasoning and in processing different pronouns in a setting that is very simple for humans, and we encourage researchers in bias and reasoning to bridge them.

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x1.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x2.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x3.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x4.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x5.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x6.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x7.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x8.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x9.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x10.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x11.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x12.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x13.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x14.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x15.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x16.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x17.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x18.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x19.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x20.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x21.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x22.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x23.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x24.png)

![英语大型语言模型的代词使用准确度：它们真的在进行逻辑推理，还是仅仅在重复或受到偏见的驱使？](../../../paper_images/2404.03134/x25.png)

[Arxiv](https://arxiv.org/abs/2404.03134)