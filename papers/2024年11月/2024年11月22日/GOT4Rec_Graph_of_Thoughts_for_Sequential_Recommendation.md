# GOT4Rec：用于序列推荐的思维图谱

发布时间：2024年11月22日

`LLM应用` `推荐系统` `用户序列`

> GOT4Rec: Graph of Thoughts for Sequential Recommendation

# 摘要

> 随着大型语言模型（LLMs）的进步，研究人员一直在探索各种办法，以便在顺序推荐场景中，把它们的理解和生成能力发挥到极致。不过，在这个探索过程中，还是存在一些难题。其一，现有的大多数方法都依赖输入 - 输出提示模式，这可能会带来不相关或者不准确的回应。其二，虽然有人尝试用像思维链（CoT）这样的提示策略来强化LLMs，但这些尝试既没有充分发挥LLMs的推理能力，也没能有效捕捉到用户序列里的多面信息。为了克服这些局限，我们提出了GOT4Rec，这是一种采用思维图（GoT）提示策略的顺序推荐方法。具体而言，我们在用户历史序列中识别并运用了三类关键信息：短期兴趣、长期兴趣以及来自其他用户的协作信息。我们的方法能让LLMs依据这些不同类型的信息独立推理并生成推荐，然后在GoT框架内整合结果，得出最终的推荐项目。这种方法让推理能力得到增强的LLMs能更有效地考虑用户序列中的各类信息，进而给出更精准的推荐和更全面的解释。在真实世界数据集上开展的大量实验证明了GOT4Rec的有效性，表明它比现有的最先进基线表现更出色。我们的代码可在https://anonymous.4open.science/r/GOT4Rec-ED99获取。

> With the advancement of large language models (LLMs), researchers have explored various methods to optimally leverage their comprehension and generation capabilities in sequential recommendation scenarios. However, several challenges persist in this endeavor. Firstly, most existing approaches rely on the input-output prompting paradigm, which can result in irrelevant or inaccurate responses. Secondly, while there have been attempts to enhance LLMs using prompting strategies such as chain-of-thought (CoT), these efforts have not fully harnessed the reasoning abilities of LLMs or effectively captured the multifaceted information contained within user sequences. To address these limitations, we propose GOT4Rec, a sequential recommendation method that utilizes the graph of thoughts (GoT) prompting strategy. Specifically, we identify and utilize three key types of information within user history sequences: short-term interests, long-term interests and collaborative information from other users. Our approach enables LLMs to independently reason and generate recommendations based on these distinct types of information, subsequently aggregating the results within the GoT framework to derive the final recommended items. This method allows LLMs, with enhanced reasoning capabilities, to more effectively consider the diverse information within user sequences, resulting in more accurate recommendations and more comprehensive explanations. Extensive experiments on real-world datasets demonstrate the effectiveness of GOT4Rec, indicating that it outperforms existing state-of-the-art baselines. Our code is available at https://anonymous.4open.science/r/GOT4Rec-ED99.

[Arxiv](https://arxiv.org/abs/2411.14922)