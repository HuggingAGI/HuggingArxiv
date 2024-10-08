# 快速定位多语言数据集中的低质量语言子集：大规模多语言音频数据集的实践探索

发布时间：2024年10月05日

`LLM应用` `语音识别` `数据集管理`

> Efficiently Identifying Low-Quality Language Subsets in Multilingual Datasets: A Case Study on a Large-Scale Multilingual Audio Dataset

# 摘要

> 构建跨语言数据集充满挑战。为提高收集效率，研究者常引入语言识别等不完美分类器，但这些模型易出错，导致部分语言数据不可靠。我们提出“偏好比例测试”，通过仅标注20个样本，即可识别X-IPAPack数据集中10种语言的转录错误。实验表明，过滤低质数据显著提升语音转录模型性能，尤其在处理新语言时，准确率提升25.7%。这一方法为多语言数据集的系统审计提供了新思路。

> Curating datasets that span multiple languages is challenging. To make the collection more scalable, researchers often incorporate one or more imperfect classifiers in the process, like language identification models. These models, however, are prone to failure, resulting in some language subsets being unreliable for downstream tasks. We introduce a statistical test, the Preference Proportion Test, for identifying such unreliable subsets. By annotating only 20 samples for a language subset, we're able to identify systematic transcription errors for 10 language subsets in a recent large multilingual transcribed audio dataset, X-IPAPack (Zhu et al., 2024). We find that filtering this low-quality data out when training models for the downstream task of phonetic transcription brings substantial benefits, most notably a 25.7% relative improvement on transcribing recordings in out-of-distribution languages. Our method lays a path forward for systematic and reliable multilingual dataset auditing.

[Arxiv](https://arxiv.org/abs/2410.04292)