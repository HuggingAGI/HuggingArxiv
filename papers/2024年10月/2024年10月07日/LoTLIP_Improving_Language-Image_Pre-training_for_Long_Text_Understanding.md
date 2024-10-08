# LoTLIP：提升长文本理解的语言-图像预训练效果

发布时间：2024年10月07日

`LLM应用` `计算机视觉`

> LoTLIP: Improving Language-Image Pre-training for Long Text Understanding

# 摘要

> 理解长文本在实际应用中至关重要，但大多数语言-图像预训练模型难以胜任。我们发现，训练图像常与短标题配对，导致某些信息被忽略。为解决此问题，我们尝试用长标题重新标注数据，但直接使用可能导致短文本理解能力下降。通过引入角标记整合多样文本信息，我们不仅恢复了模型对短文本的理解能力，还显著提升了其对长文本的理解。进一步研究发现，模型在处理更长标题时存在性能与效率的权衡。我们使用自建的1亿长标题文本-图像对数据集验证了方法的有效性，在长文本图像检索任务中，性能提升了11.1%。我们将公开代码、模型和数据集，助力后续研究。项目详情请访问https://wuw2019.github.io/lotlip。

> Understanding long text is of great demands in practice but beyond the reach of most language-image pre-training (LIP) models. In this work, we empirically confirm that the key reason causing such an issue is that the training images are usually paired with short captions, leaving certain tokens easily overshadowed by salient tokens. Towards this problem, our initial attempt is to relabel the data with long captions, however, directly learning with which may lead to performance degradation in understanding short text (e.g., in the image classification task). Then, after incorporating corner tokens to aggregate diverse textual information, we manage to help the model catch up to its original level of short text understanding yet greatly enhance its capability of long text understanding. We further look into whether the model can continuously benefit from longer captions and notice a clear trade-off between the performance and the efficiency. Finally, we validate the effectiveness of our approach using a self-constructed large-scale dataset, which consists of 100M long caption oriented text-image pairs. It is noteworthy that, on the task of long-text image retrieval, we beat the competitor using long captions with 11.1% improvement (i.e., from 72.62% to 83.72%). We will release the code, the model, and the new dataset to facilitate the reproducibility and further research. The project page is available at https://wuw2019.github.io/lotlip.

[Arxiv](https://arxiv.org/abs/2410.05249)