# VAIYAKARANA：孟加拉语自动语法修正的标杆

发布时间：2024年06月20日

`LLM应用

这篇论文主要关注孟加拉语的自动语法纠正技术，并提出了一种新的方法来生成语法错误的语料库。这种方法涉及将错误分类并系统地从正确句子生成错误句子，以创建一个大规模的数据集。论文中还提到了与神经模型和大型语言模型（LLMs）的对比，以及孟加拉语母语者的评估。因此，这项工作更偏向于应用层面，即如何利用LLMs来改进特定语言（如孟加拉语）的语法纠正技术，而不是理论研究或Agent、RAG相关的研究。` `语言技术`

> VAIYAKARANA : A Benchmark for Automatic Grammar Correction in Bangla

# 摘要

> 孟加拉语作为全球第五大语言，其自动语法纠正技术尚处于起步阶段，主要因缺乏包含大量语法错误及其正确版本的语料库。现有技术通过随机交换、插入和删除单词来构建此类语料库，但这些方法在孟加拉语中并不总能奏效。为此，我们提出了一种实用方法：首先将孟加拉语中的错误分为5大类和12小类，然后从正确句子出发，系统地生成语法错误句子。这种方法能有效生成大量错误句子，缓解了缺乏大规模语料库的问题。我们创建了名为Vaiyakarana的数据集，包含92,830个错误句子和18,426个正确句子，并从孟加拉语母语者的文章中收集了619个句子，以识别常见错误。通过与神经模型和LLMs的对比，以及孟加拉语母语者的评估，我们发现母语者的准确性远超现有模型。我们的方法同样适用于其他印度语言。

> Bangla (Bengali) is the fifth most spoken language globally and, yet, the problem of automatic grammar correction in Bangla is still in its nascent stage. This is mostly due to the need for a large corpus of grammatically incorrect sentences, with their corresponding correct counterparts. The present state-of-the-art techniques to curate a corpus for grammatically wrong sentences involve random swapping, insertion and deletion of words. However,these steps may not always generate grammatically wrong sentences in Bangla. In this work, we propose a pragmatic approach to generate grammatically wrong sentences in Bangla. We first categorize the different kinds of errors in Bangla into 5 broad classes and 12 finer classes. We then use these to generate grammatically wrong sentences systematically from a correct sentence. This approach can generate a large number of wrong sentences and can, thus, mitigate the challenge of lacking a large corpus for neural networks. We provide a dataset, Vaiyakarana, consisting of 92,830 grammatically incorrect sentences as well as 18,426 correct sentences. We also collected 619 human-generated sentences from essays written by Bangla native speakers. This helped us to understand errors that are more frequent. We evaluated our corpus against neural models and LLMs and also benchmark it against human evaluators who are native speakers of Bangla. Our analysis shows that native speakers are far more accurate than state-of-the-art models to detect whether the sentence is grammatically correct. Our methodology of generating erroneous sentences can be applied for most other Indian languages as well.

[Arxiv](https://arxiv.org/abs/2406.14284)