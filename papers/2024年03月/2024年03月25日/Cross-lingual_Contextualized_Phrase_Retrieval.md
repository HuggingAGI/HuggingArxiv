# 跨语言情境化短语检索技术步骤解释：

发布时间：2024年03月25日

`LLM应用` `跨语言处理` `信息检索`

> Cross-lingual Contextualized Phrase Retrieval

> 短语级稠密检索技术凭借其捕捉到的细致信息，在下游NLP任务中展现出引人注目的优点。在此研究中，我们创新性地提出了“跨语言上下文化短语检索”这一新任务范式，旨在借助上下文信息解决多义性问题，从而提升跨语言应用场景的表现。然而，专门的训练数据和模型的缺失成为了实现这一目标的主要难题。为此，我们利用平行句中自动生成的词语对齐信息抽取跨语言短语对。然后，我们运用对比学习策略训练我们的“跨语言上下文化短语检索器”（CCPR），促使语境与语义相似的短语隐层表示相互贴近。在跨语言短语检索任务以及下游任务如机器翻译上开展的综合实验有力证明了CCPR的有效性。在短语检索任务上，CCPR以显著的优势超越基准，top-1准确率至少提升了13个百分点。进一步地，当将CCPR应用于大型语言模型驱动的翻译系统时，在WMT16数据集上，针对从X到En及反之的翻译任务，其平均BERTScore得分分别提高了0.7和1.5。我们的代码和数据已公开在GitHub地址：\url{https://github.com/ghrua/ccpr_release}。

> Phrase-level dense retrieval has shown many appealing characteristics in downstream NLP tasks by leveraging the fine-grained information that phrases offer. In our work, we propose a new task formulation of dense retrieval, cross-lingual contextualized phrase retrieval, which aims to augment cross-lingual applications by addressing polysemy using context information. However, the lack of specific training data and models are the primary challenges to achieve our goal. As a result, we extract pairs of cross-lingual phrases using word alignment information automatically induced from parallel sentences. Subsequently, we train our Cross-lingual Contextualized Phrase Retriever (CCPR) using contrastive learning, which encourages the hidden representations of phrases with similar contexts and semantics to align closely. Comprehensive experiments on both the cross-lingual phrase retrieval task and a downstream task, i.e, machine translation, demonstrate the effectiveness of CCPR. On the phrase retrieval task, CCPR surpasses baselines by a significant margin, achieving a top-1 accuracy that is at least 13 points higher. When utilizing CCPR to augment the large-language-model-based translator, it achieves average gains of 0.7 and 1.5 in BERTScore for translations from X=>En and vice versa, respectively, on WMT16 dataset. Our code and data are available at \url{https://github.com/ghrua/ccpr_release}.

![跨语言情境化短语检索技术步骤解释：](../../../paper_images/2403.16820/x1.png)

[Arxiv](https://arxiv.org/abs/2403.16820)