# ArtVLM：利用视觉前缀语言模型实现属性识别

发布时间：2024年08月07日

`LLM应用` `计算机视觉` `视觉语言模型`

> ArtVLM: Attribute Recognition Through Vision-Based Prefix Language Modeling

# 摘要

> 识别并分离视觉属性与物体是计算机视觉应用的基石。尽管 CLIP 等大型视觉语言模型在零-shot 物体识别上表现出色，但零-shot 视觉属性识别仍具挑战，因其难以捕捉物体与属性的依赖关系。本文针对此短板，提出一种创新的基于句子生成的属性识别方法，通过 1) 将物体-属性关系建模为条件概率图，将识别问题转化为依赖敏感的语言建模问题，以及 2) 利用预训练的大型视觉语言模型（VLM），自然地提炼其对图像-物体-属性关系的知识，用于属性识别。具体来说，对于图像中的每个属性，我们计算生成描述该属性与物体关系的短句子的视觉条件概率。与全局对齐句子与图像元素的对比检索不同，生成检索更关注句子中物体和属性的顺序及依赖关系。实验表明，在 Visual Attribute in the Wild（VAW）和我们新提出的 Visual Genome Attribute Ranking（VGARank）数据集上，生成检索持续超越对比检索。

> Recognizing and disentangling visual attributes from objects is a foundation to many computer vision applications. While large vision language representations like CLIP had largely resolved the task of zero-shot object recognition, zero-shot visual attribute recognition remains a challenge because CLIP's contrastively-learned vision-language representation cannot effectively capture object-attribute dependencies. In this paper, we target this weakness and propose a sentence generation-based retrieval formulation for attribute recognition that is novel in 1) explicitly modeling a to-be-measured and retrieved object-attribute relation as a conditional probability graph, which converts the recognition problem into a dependency-sensitive language-modeling problem, and 2) applying a large pretrained Vision-Language Model (VLM) on this reformulation and naturally distilling its knowledge of image-object-attribute relations to use towards attribute recognition. Specifically, for each attribute to be recognized on an image, we measure the visual-conditioned probability of generating a short sentence encoding the attribute's relation to objects on the image. Unlike contrastive retrieval, which measures likelihood by globally aligning elements of the sentence to the image, generative retrieval is sensitive to the order and dependency of objects and attributes in the sentence. We demonstrate through experiments that generative retrieval consistently outperforms contrastive retrieval on two visual reasoning datasets, Visual Attribute in the Wild (VAW), and our newly-proposed Visual Genome Attribute Ranking (VGARank).

[Arxiv](https://arxiv.org/abs/2408.04102)