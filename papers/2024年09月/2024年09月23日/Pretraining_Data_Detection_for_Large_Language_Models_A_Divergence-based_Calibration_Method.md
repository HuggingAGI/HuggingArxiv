# 大型语言模型的预训练数据检测：一种基于发散的校准方法

发布时间：2024年09月23日

`LLM应用` `数据隐私`

> Pretraining Data Detection for Large Language Models: A Divergence-based Calibration Method

# 摘要

> 随着 LLM 训练数据的规模扩大，开发者越来越不愿公开数据细节，这给科学评估和伦理部署带来了难题。最近，通过黑箱访问推断文本是否属于 LLM 训练数据的预训练数据检测方法备受关注。Min-K% Prob 方法虽表现优异，但因其易将包含高概率常见词的非训练文本误分类，效果受限。为此，我们借鉴随机性发散概念，提出基于发散的校准方法，通过计算标记概率与频率分布间的交叉熵来提升检测准确性。我们还创建了中文基准 PatentMIA，实验表明，该方法在英汉基准测试中均显著超越现有技术。相关代码和基准已公开，详见 https://github.com/zhang-wei-chao/DC-PDD。

> As the scale of training corpora for large language models (LLMs) grows, model developers become increasingly reluctant to disclose details on their data. This lack of transparency poses challenges to scientific evaluation and ethical deployment. Recently, pretraining data detection approaches, which infer whether a given text was part of an LLM's training data through black-box access, have been explored. The Min-K% Prob method, which has achieved state-of-the-art results, assumes that a non-training example tends to contain a few outlier words with low token probabilities. However, the effectiveness may be limited as it tends to misclassify non-training texts that contain many common words with high probabilities predicted by LLMs. To address this issue, we introduce a divergence-based calibration method, inspired by the divergence-from-randomness concept, to calibrate token probabilities for pretraining data detection. We compute the cross-entropy (i.e., the divergence) between the token probability distribution and the token frequency distribution to derive a detection score.We have developed a Chinese-language benchmark, PatentMIA, to assess the performance of detection approaches for LLMs on Chinese text. Experimental results on English-language benchmarks and PatentMIA demonstrate that our proposed method significantly outperforms existing methods. Our code and PatentMIA benchmark are available at https://github.com/zhang-wei-chao/DC-PDD

[Arxiv](https://arxiv.org/abs/2409.14781)