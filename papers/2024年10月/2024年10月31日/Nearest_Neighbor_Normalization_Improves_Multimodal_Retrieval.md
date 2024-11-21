# 最近邻归一化提升了多模态检索效果

发布时间：2024年10月31日

`LLM应用` `图像检索` `多模态`

> Nearest Neighbor Normalization Improves Multimodal Retrieval

# 摘要

> 多模态模型借助大规模预训练，在图像描述、视觉问答和跨模态检索等任务中取得了强劲但仍有不足的表现。本文中，我们呈现了一种简便高效的方法——最近邻归一化（NNN），能在无需额外训练的情况下，纠正已训练的对比图像-文本检索模型中的错误。我们发现，在我们测试的所有对比模型（CLIP、BLIP、ALBEF、SigLIP、BEiT）以及所使用的两个数据集（MS-COCO 和 Flickr30k）中，文本检索和图像检索的指标均有提升。NNN 需要一个参考数据库，但无需针对该数据库进行任何训练，甚至在微调后还能提高模型的检索准确率。

> Multimodal models leverage large-scale pre-training to achieve strong but still imperfect performance on tasks such as image captioning, visual question answering, and cross-modal retrieval. In this paper, we present a simple and efficient method for correcting errors in trained contrastive image-text retrieval models with no additional training, called Nearest Neighbor Normalization (NNN). We show an improvement on retrieval metrics in both text retrieval and image retrieval for all of the contrastive models that we tested (CLIP, BLIP, ALBEF, SigLIP, BEiT) and for both of the datasets that we used (MS-COCO and Flickr30k). NNN requires a reference database, but does not require any training on this database, and can even increase the retrieval accuracy of a model after finetuning.

[Arxiv](https://arxiv.org/abs/2410.24114)