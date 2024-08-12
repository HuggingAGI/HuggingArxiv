# 探索语言神经表征学习及从脑电图记录中提取句子的方法

发布时间：2024年08月07日

`LLM应用` `脑机接口`

> Towards Linguistic Neural Representation Learning and Sentence Retrieval from Electroencephalogram Recordings

# 摘要

> 利用 EEG 技术从非侵入性脑信号中解码语言信息，因其巨大的应用前景而备受瞩目。近期研究多采用基于生成的方法，借助预训练大型语言模型的强大生成能力，将脑电图信号转换为句子。然而，这种方法存在一些问题，如 EEG 编码器学习语义信息的能力存疑，以及 LLM 解码器过度依赖训练记忆生成句子。为此，我们提出了一种创新的两步流程，旨在解决这些限制，并提升语言 EEG 解码的可靠性。首先，我们证实通过训练 Conformer 编码器，可以有效从自然阅读时的 EEG 数据中提取词级语义信息。接着，我们采用无需训练的检索方法，根据 EEG 编码器的预测结果检索相应句子。通过广泛的实验和消融研究，我们验证了该方法的有效性。结果显示，模型能将 EEG 片段准确分类，表明其能从未说出的 EEG 记录中学习语义模式。尽管这项研究尚属探索阶段，但其成果预示着我们方法在将 EEG 信号转换为文本方面的巨大潜力。

> Decoding linguistic information from non-invasive brain signals using EEG has gained increasing research attention due to its vast applicational potential. Recently, a number of works have adopted a generative-based framework to decode electroencephalogram (EEG) signals into sentences by utilizing the power generative capacity of pretrained large language models (LLMs). However, this approach has several drawbacks that hinder the further development of linguistic applications for brain-computer interfaces (BCIs). Specifically, the ability of the EEG encoder to learn semantic information from EEG data remains questionable, and the LLM decoder's tendency to generate sentences based on its training memory can be hard to avoid. These issues necessitate a novel approach for converting EEG signals into sentences. In this paper, we propose a novel two-step pipeline that addresses these limitations and enhances the validity of linguistic EEG decoding research. We first confirm that word-level semantic information can be learned from EEG data recorded during natural reading by training a Conformer encoder via a masked contrastive objective for word-level classification. To achieve sentence decoding results, we employ a training-free retrieval method to retrieve sentences based on the predictions from the EEG encoder. Extensive experiments and ablation studies were conducted in this paper for a comprehensive evaluation of the proposed approach. Visualization of the top prediction candidates reveals that our model effectively groups EEG segments into semantic categories with similar meanings, thereby validating its ability to learn patterns from unspoken EEG recordings. Despite the exploratory nature of this work, these results suggest that our method holds promise for providing more reliable solutions for converting EEG signals into text.

[Arxiv](https://arxiv.org/abs/2408.04679)