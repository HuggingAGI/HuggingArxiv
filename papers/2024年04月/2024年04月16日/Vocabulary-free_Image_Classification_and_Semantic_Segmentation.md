# 无需词汇的图像分类与语义分割技术

发布时间：2024年04月16日

`分类：LLM应用` `图像处理`

> Vocabulary-free Image Classification and Semantic Segmentation

# 摘要

> 大型视觉-语言模型为图像分类和语义分割领域带来了革命性的变化。但它们通常依赖于一组预设的类别或词汇，这在面对未知或变化的语义环境时显得不切实际。为此，我们提出了无需固定词汇表的图像分类（VIC）任务，目的是在不依赖已知词汇的情况下，为输入图像指定一个来自开放语言空间的类别。VIC面临的挑战在于其广阔的语义空间，涵盖数百万概念，包括精细的类别划分。为应对这一挑战，我们设计了一种无需训练的方法——从外部数据库进行类别搜索（CaSED），它利用了预训练的视觉-语言模型和外部数据库。CaSED通过从数据库中提取与图像语义最接近的候选类别，然后利用同一视觉-语言模型将图像归类到最佳匹配的候选类别。此外，我们还证明了CaSED可以本地部署，生成粗略的分割掩模，对图像区域进行分类，从而开创了无需词汇表的语义分割新领域。在分类和语义分割的基准测试中，CaSED及其变体在参数使用更少的情况下，性能超越了其他更为复杂的视觉-语言模型。

> Large vision-language models revolutionized image classification and semantic segmentation paradigms. However, they typically assume a pre-defined set of categories, or vocabulary, at test time for composing textual prompts. This assumption is impractical in scenarios with unknown or evolving semantic context. Here, we address this issue and introduce the Vocabulary-free Image Classification (VIC) task, which aims to assign a class from an unconstrained language-induced semantic space to an input image without needing a known vocabulary. VIC is challenging due to the vastness of the semantic space, which contains millions of concepts, including fine-grained categories. To address VIC, we propose Category Search from External Databases (CaSED), a training-free method that leverages a pre-trained vision-language model and an external database. CaSED first extracts the set of candidate categories from the most semantically similar captions in the database and then assigns the image to the best-matching candidate category according to the same vision-language model. Furthermore, we demonstrate that CaSED can be applied locally to generate a coarse segmentation mask that classifies image regions, introducing the task of Vocabulary-free Semantic Segmentation. CaSED and its variants outperform other more complex vision-language models, on classification and semantic segmentation benchmarks, while using much fewer parameters.

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x1.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x2.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x3.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x4.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x5.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x6.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/x7.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/caltech101_chandelier.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/caltech101_dalmatian.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/caltech101_ibis.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/caltech101_gramophone.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/caltech101_cellphone.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/food101_bibimbap.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/food101_cheesecake.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/food101_guacamole.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/food101_caprese_salad.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/food101_pizza.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sun397_galley.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sun397_shed.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sun397_restaurant.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sun397_football.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sun397_garbage_dump.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_ade_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_ade_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_ade_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_ade_003.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_ade_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_ade_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_ctx_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_ctx_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_ctx_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_ctx_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_ctx_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_ctx_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_voc_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/sam_llava_voc_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_voc_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/san_wordnet_voc_002.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_voc_001.png)

![无需词汇的图像分类与语义分割技术](../../../paper_images/2404.10864/densecased_voc_002.png)

[Arxiv](https://arxiv.org/abs/2404.10864)