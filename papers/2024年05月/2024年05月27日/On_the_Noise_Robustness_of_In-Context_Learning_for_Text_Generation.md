# 探究文本生成任务中，情境学习对噪声干扰的稳健性

发布时间：2024年05月27日

`LLM应用

这篇论文主要探讨了大型语言模型（LLMs）在文本生成任务中如何处理噪声标注的问题，并提出了一种新的方法——局部困惑度排序（LPR）来解决这一问题。这种方法通过选择更可能无噪声的近邻来替换噪声候选，从而提高ICL在文本生成任务中的性能。因此，这篇论文属于LLM应用类别，因为它关注的是LLMs在实际应用中的具体问题和解决方案，而不是理论研究或Agent、RAG相关的研究。` `文本生成` `文本分类`

> On the Noise Robustness of In-Context Learning for Text Generation

# 摘要

> 大型语言模型（LLMs）通过情境学习（ICL）在下游任务中表现出色，关键在于从众多标注示例中精选出高质量的演示。尽管有研究指出ICL在文本分类中对噪声演示具有较强的鲁棒性，但我们发现，在文本生成任务中，噪声标注却严重影响了ICL的性能。为此，我们提出了一种名为局部困惑度排序（LPR）的新方法，它通过选择更可能无噪声的近邻来替换噪声候选，有效规避了这一问题。LPR的灵感来源于对噪声标签导致的困惑度偏差的分析，以及将困惑度细分为固有与匹配两个维度。我们的核心策略是在语义空间内对邻近样本进行排序，以解耦匹配困惑度，从而在维持原有选择方法效力的同时，避免选入不匹配的输入-标签对。大量实验结果显示，LPR在噪声标注的基准测试中显著提升了EM分数，最高可达18.75。

> Large language models (LLMs) have shown impressive performance on downstream tasks by in-context learning (ICL), which heavily relies on the quality of demonstrations selected from a large set of annotated examples. Recent works claim that in-context learning is robust to noisy demonstrations in text classification. In this work, we show that, on text generation tasks, noisy annotations significantly hurt the performance of in-context learning. To circumvent the issue, we propose a simple and effective approach called Local Perplexity Ranking (LPR), which replaces the "noisy" candidates with their nearest neighbors that are more likely to be clean. Our method is motivated by analyzing the perplexity deviation caused by noisy labels and decomposing perplexity into inherent perplexity and matching perplexity. Our key idea behind LPR is thus to decouple the matching perplexity by performing the ranking among the neighbors in semantic space. Our approach can prevent the selected demonstrations from including mismatched input-label pairs while preserving the effectiveness of the original selection methods. Extensive experiments demonstrate the effectiveness of LPR, improving the EM score by up to 18.75 on common benchmarks with noisy annotations.

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x1.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x2.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x3.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x4.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x5.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x6.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x7.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x8.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x9.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x10.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x11.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x12.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x13.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x14.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x15.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x16.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x17.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x18.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x19.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x20.png)

![探究文本生成任务中，情境学习对噪声干扰的稳健性](../../../paper_images/2405.17264/x21.png)

[Arxiv](https://arxiv.org/abs/2405.17264)