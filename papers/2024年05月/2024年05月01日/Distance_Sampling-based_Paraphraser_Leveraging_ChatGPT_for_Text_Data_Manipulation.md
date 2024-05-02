# 利用 ChatGPT 的距离抽样技术，打造文本数据的释义神器。

发布时间：2024年05月01日

`分类：LLM应用` `音频检索`

> Distance Sampling-based Paraphraser Leveraging ChatGPT for Text Data Manipulation

# 摘要

> 音频-语言检索领域正受到越来越多的关注，旨在揭示音频与文本之间的联系。尽管如此，现有的音频-文本配对数据集往往在文本表达的丰富性上不及音频样本。一个特别的难题是，不同的音频样本可能伴有相似或完全相同的描述。这导致在多对一的映射情境下，检索任务的表现不尽人意。本文提出了一种创新的方法来应对音频-语言检索中的不平衡数据问题。我们引入了一种基于距离采样的释义技术，结合ChatGPT，通过距离函数来生成可控的文本数据分布。对于一组具有相同语境的句子，利用距离来衡量句子间的修改程度，并采用Jaccard相似性定义的相似距离的文本集进行ChatGPT的少量示例提示。这样，ChatGPT在进行少量示例提示时，能够根据距离来调节文本的多样性。实验结果表明，我们的方法显著提升了音频-文本检索的效果，超越了传统的文本增强方法。

> There has been growing interest in audio-language retrieval research, where the objective is to establish the correlation between audio and text modalities. However, most audio-text paired datasets often lack rich expression of the text data compared to the audio samples. One of the significant challenges facing audio-text datasets is the presence of similar or identical captions despite different audio samples. Therefore, under many-to-one mapping conditions, audio-text datasets lead to poor performance of retrieval tasks. In this paper, we propose a novel approach to tackle the data imbalance problem in audio-language retrieval task. To overcome the limitation, we introduce a method that employs a distance sampling-based paraphraser leveraging ChatGPT, utilizing distance function to generate a controllable distribution of manipulated text data. For a set of sentences with the same context, the distance is used to calculate a degree of manipulation for any two sentences, and ChatGPT's few-shot prompting is performed using a text cluster with a similar distance defined by the Jaccard similarity. Therefore, ChatGPT, when applied to few-shot prompting with text clusters, can adjust the diversity of the manipulated text based on the distance. The proposed approach is shown to significantly enhance performance in audio-text retrieval, outperforming conventional text augmentation techniques.

[Arxiv](https://arxiv.org/abs/2405.00367)