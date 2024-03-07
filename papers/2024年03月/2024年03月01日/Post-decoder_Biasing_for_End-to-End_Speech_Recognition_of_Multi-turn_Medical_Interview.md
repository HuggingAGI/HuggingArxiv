# [在多轮医疗访谈端到端语音识别技术中，我们采用了解码器后置偏置策略以优化识别效果。](https://arxiv.org/abs/2403.00370)

发布时间：2024年03月01日

`Agent`

> Post-decoder Biasing for End-to-End Speech Recognition of Multi-turn Medical Interview

> 随着E2E方法逐步替代混合模型在ASR任务中的应用，针对E2E模型在处理解码偏移问题上缺乏直观优化手段的问题日益凸显，尤其是在包含许多带有特定关键意义的领域罕见词汇场景下。鉴于学术界对知识密集型语音数据集的匮乏现状，这一短板严重影响了模型的实际表现，现有常用语音数据集与真实对话情境间存在着较大差距。为应对这些挑战，我们精心打造了一个名为“MED-IT”的多轮医疗咨询语音数据集，其中富含大量的知识密集型命名实体。同时，我们探索了提升E2E模型识别罕见词效果的新途径，并提出了“后解码器加权”这一新颖方法。此方法通过建立基于训练转写文本分布的转换概率矩阵，促使模型优先识别加权列表中的词汇。实验证明，在针对训练语音中出现频率介于10至20次以及1至5次的罕见词子集中，上述方法分别取得了9.3%和5.1%的相对性能提升。

> End-to-end (E2E) approach is gradually replacing hybrid models for automatic speech recognition (ASR) tasks. However, the optimization of E2E models lacks an intuitive method for handling decoding shifts, especially in scenarios with a large number of domain-specific rare words that hold specific important meanings. Furthermore, the absence of knowledge-intensive speech datasets in academia has been a significant limiting factor, and the commonly used speech corpora exhibit significant disparities with realistic conversation. To address these challenges, we present Medical Interview (MED-IT), a multi-turn consultation speech dataset that contains a substantial number of knowledge-intensive named entities. We also explore methods to enhance the recognition performance of rare words for E2E models. We propose a novel approach, post-decoder biasing, which constructs a transform probability matrix based on the distribution of training transcriptions. This guides the model to prioritize recognizing words in the biasing list. In our experiments, for subsets of rare words appearing in the training speech between 10 and 20 times, and between 1 and 5 times, the proposed method achieves a relative improvement of 9.3% and 5.1%, respectively.