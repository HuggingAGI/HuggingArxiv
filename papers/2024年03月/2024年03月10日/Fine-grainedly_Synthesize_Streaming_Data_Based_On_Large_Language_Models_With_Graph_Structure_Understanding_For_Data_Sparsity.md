# 为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。

发布时间：2024年03月10日

`LLM应用`

> Fine-grainedly Synthesize Streaming Data Based On Large Language Models With Graph Structure Understanding For Data Sparsity

# 摘要

> 电商平台上，用户评论的情感分析因用户数据稀疏而困扰，尤其在处理极稀疏数据和长尾标签时效果欠佳。近年来，LLMs凭借利用图结构构建附加用户画像的新方法为这类问题提供了新解。但以往的手段并未充分挖掘LLMs的图理解潜能，且难以适应复杂的流式数据场景。本文创新提出一种针对细粒度流式数据的合成框架，将稀疏用户划分为中尾部、长尾部及极端稀疏三类。特别地，我们设计的LLMs能深入理解流式数据中的三大图要素——局部与全局图理解、二阶关系提取和商品属性认知，从而生成高品质合成数据，有效应对各类别间的稀疏问题。实验证明，在三个真实数据集上，该方法取得了显著的效果改进，合成数据使MSE分别降低了45.85%、3.16%和62.21%。

> Due to the sparsity of user data, sentiment analysis on user reviews in e-commerce platforms often suffers from poor performance, especially when faced with extremely sparse user data or long-tail labels. Recently, the emergence of LLMs has introduced new solutions to such problems by leveraging graph structures to generate supplementary user profiles. However, previous approaches have not fully utilized the graph understanding capabilities of LLMs and have struggled to adapt to complex streaming data environments. In this work, we propose a fine-grained streaming data synthesis framework that categorizes sparse users into three categories: Mid-tail, Long-tail, and Extreme. Specifically, we design LLMs to comprehensively understand three key graph elements in streaming data, including Local-global Graph Understanding, Second-Order Relationship Extraction, and Product Attribute Understanding, which enables the generation of high-quality synthetic data to effectively address sparsity across different categories. Experimental results on three real datasets demonstrate significant performance improvements, with synthesized data contributing to MSE reductions of 45.85%, 3.16%, and 62.21%, respectively.

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x1.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x2.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x3.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x4.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x5.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x6.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x7.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x8.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x9.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x10.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x11.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x12.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x13.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x14.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x15.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x16.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x17.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x18.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x19.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x20.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x21.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x22.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x23.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x24.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x25.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x26.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x27.png)

![为了应对数据稀疏性挑战，本研究提出利用具备图结构理解能力的大型语言模型，对流式数据进行精细化合成。](../../../paper_images/2403.06139/x28.png)

[Arxiv](https://arxiv.org/abs/2403.06139)