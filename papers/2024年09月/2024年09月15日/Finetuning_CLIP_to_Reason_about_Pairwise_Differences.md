# 微调 CLIP，使其能够推理成对差异

发布时间：2024年09月15日

`LLM应用` `计算机视觉`

> Finetuning CLIP to Reason about Pairwise Differences

# 摘要

> 视觉-语言模型如CLIP通过对比学习训练，生成对齐的图像和文本嵌入，广泛应用于下游任务。然而，CLIP的嵌入空间缺乏纯文本嵌入的结构，例如无法进行向量算术类比。本文提出一种对比方式训练CLIP的方法，使图像嵌入差异对应于“图像差异的文本描述”，由大型语言模型生成。实验表明，该方法显著提升图像按属性排序的能力，改善零样本分类性能，并引入“比较提示”推理机制，进一步提升分类性能。最终，生成的嵌入展现出更强的几何属性，如在文本到图像生成中的应用。

> Vision-language models (VLMs) such as CLIP are trained via contrastive learning between text and image pairs, resulting in aligned image and text embeddings that are useful for many downstream tasks. A notable drawback of CLIP, however, is that the resulting embedding space seems to lack some of the structure of their purely text-based alternatives. For instance, while text embeddings have been long noted to satisfy \emph{analogies} in embedding space using vector arithmetic, CLIP has no such property. In this paper, we propose an approach to natively train CLIP in a contrastive manner to reason about differences in embedding space. We finetune CLIP so that the differences in image embedding space correspond to \emph{text descriptions of the image differences}, which we synthetically generate with large language models on image-caption paired datasets. We first demonstrate that our approach yields significantly improved capabilities in ranking images by a certain attribute (e.g., elephants are larger than cats), which is useful in retrieval or constructing attribute-based classifiers, and improved zeroshot classification performance on many downstream image classification tasks. In addition, our approach enables a new mechanism for inference that we refer to as comparative prompting, where we leverage prior knowledge of text descriptions of differences between classes of interest, achieving even larger performance gains in classification. Finally, we illustrate that the resulting embeddings obey a larger degree of geometric properties in embedding space, such as in text-to-image generation.

[Arxiv](https://arxiv.org/abs/2409.09721)