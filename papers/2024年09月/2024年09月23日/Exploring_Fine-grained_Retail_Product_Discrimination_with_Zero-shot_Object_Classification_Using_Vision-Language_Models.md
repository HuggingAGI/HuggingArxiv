# 通过视觉-语言模型，我们探索了零-shot 对象分类在细粒度零售产品辨别中的应用。

发布时间：2024年09月23日

`LLM应用` `人工智能`

> Exploring Fine-grained Retail Product Discrimination with Zero-shot Object Classification Using Vision-Language Models

# 摘要

> 在智能零售领域，大量产品和频繁更替要求我们采用可靠的零-shot 物体分类技术。零-shot 假设避免了每次新品上架或产品重新品牌化时重新训练分类器的麻烦。本文中，我们有三项重要贡献：首先，我们推出了 MIMEX 数据集，涵盖 28 种不同产品类别，专注于细粒度分类，产品种类丰富。其次，我们在 MIMEX 数据集上测试了最先进视觉-语言模型的零-shot 分类性能，发现其在细粒度分类上表现不佳，凸显了专门方法的必要性。最后，我们提出了一种集成方法，结合 CLIP 和 DINOv2 的嵌入与降维技术，显著提升了分类效果，有效捕捉了细粒度产品区分的视觉线索。此外，我们还引入了一种类适应方法，在标签数据稀缺时利用有限样本进行视觉原型，应对零售环境中产品种类频繁变化的挑战。为推动相关研究，我们将发布 MIMEX 数据集和基准，感兴趣的研究人员可联系作者获取使用详情。代码已公开：https://github.com/AnilOsmanTur/Zero-shot-Retail-Product-Classification。

> In smart retail applications, the large number of products and their frequent turnover necessitate reliable zero-shot object classification methods. The zero-shot assumption is essential to avoid the need for re-training the classifier every time a new product is introduced into stock or an existing product undergoes rebranding. In this paper, we make three key contributions. Firstly, we introduce the MIMEX dataset, comprising 28 distinct product categories. Unlike existing datasets in the literature, MIMEX focuses on fine-grained product classification and includes a diverse range of retail products. Secondly, we benchmark the zero-shot object classification performance of state-of-the-art vision-language models (VLMs) on the proposed MIMEX dataset. Our experiments reveal that these models achieve unsatisfactory fine-grained classification performance, highlighting the need for specialized approaches. Lastly, we propose a novel ensemble approach that integrates embeddings from CLIP and DINOv2 with dimensionality reduction techniques to enhance classification performance. By combining these components, our ensemble approach outperforms VLMs, effectively capturing visual cues crucial for fine-grained product discrimination. Additionally, we introduce a class adaptation method that utilizes visual prototyping with limited samples in scenarios with scarce labeled data, addressing a critical need in retail environments where product variety frequently changes. To encourage further research into zero-shot object classification for smart retail applications, we will release both the MIMEX dataset and benchmark to the research community. Interested researchers can contact the authors for details on the terms and conditions of use. The code is available: https://github.com/AnilOsmanTur/Zero-shot-Retail-Product-Classification.

[Arxiv](https://arxiv.org/abs/2409.14963)