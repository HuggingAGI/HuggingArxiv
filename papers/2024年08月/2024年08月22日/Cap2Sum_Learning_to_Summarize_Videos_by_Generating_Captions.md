# Cap2Sum：一种通过生成字幕来学习视频摘要的新方法

发布时间：2024年08月22日

`LLM应用` `视频处理` `人工智能`

> Cap2Sum: Learning to Summarize Videos by Generating Captions

# 摘要

> 随着网络视频数据的激增，视频摘要技术显得尤为重要。但高昂的标注成本限制了研究规模，导致现有技术性能和泛化能力受限。为此，我们创新性地采用密集视频字幕作为训练信号，研发了Cap2Sum模型，该模型通过生成字幕来提炼视频精华。这种弱监督方法让我们得以在大规模数据集上训练，显著提升了性能和泛化能力。此外，我们结合CLIP模型，强化了对视频中易被忽视的关键对象的学习。Cap2Sum不仅支持零-shot视频摘要，还能通过目标数据集的实际摘要或字幕进行精准微调。为验证其性能，我们构建了TVSum-Caption和SumMe-Caption两个新数据集，并计划公开发布。实验结果显示，我们的方法在性能和泛化能力上均超越了现有技术。

> With the rapid growth of video data on the internet, video summarization is becoming a very important AI technology. However, due to the high labelling cost of video summarization, existing studies have to be conducted on small-scale datasets, leading to limited performance and generalization capacity. In this work, we introduce the use of dense video captions as a supervision signal to train video summarization models. Motivated by this, we propose Cap2Sum, a model that learns to summarize videos by generating captions, to exploit dense video caption annotations. This weakly-supervised approach allows us to train the models on large-scale dense video caption datasets to achieve better performance and generalization capacity. To further improve the generalization capacity, we introduce a CLIP (a strong vision-language model) Prior mechanism to enhance the learning of important objects that captions may ignore in the videos. In practice, Cap2Sum can perform zero-shot video summarization or be fine-tuned by the ground-truth summary or video caption of the target dataset. To examine the performance of Cap2Sum after weakly-supervised fine-tuning by the video captions, we propose two new datasets, TVSum-Caption and SumMe-Caption, which are derived from two common video summarization datasets and will be publicly released. We conduct extensive experiments and the results demonstrate that our method achieves significant improvements in performance and generalization capacity compared with previous methods.

[Arxiv](https://arxiv.org/abs/2408.12800)