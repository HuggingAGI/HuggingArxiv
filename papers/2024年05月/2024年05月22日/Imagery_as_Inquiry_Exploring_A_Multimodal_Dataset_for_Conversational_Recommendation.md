# 图像探究：深入多模态数据集，助力对话推荐研究

发布时间：2024年05月22日

`RAG

理由：这篇论文介绍了一个多模态数据集，并针对该数据集提出了新的方法（图像链提示法）来提升模型性能，特别是在视觉-语言模型上的应用。这与RAG（Retrieval-Augmented Generation）的概念相符，因为RAG模型通常涉及从外部知识源检索信息以增强生成过程，而这篇论文中的图像链提示法可以看作是一种检索增强的方法，用于改善视觉-语言模型的性能。此外，论文中提到的数据集和实验结果也支持了这一分类。` `推荐系统` `数据集构建`

> Imagery as Inquiry: Exploring A Multimodal Dataset for Conversational Recommendation

# 摘要

> 我们推出了一款多模态数据集，用户通过图像来表达个人喜好，这些图像丰富多彩，从自然风光到艺术作品应有尽有。用户希望获得与图像情感相契合的书籍或音乐推荐，而社区的点赞则代表了这些推荐的认可度。该数据集涵盖了标题生成和多选推荐两大任务。我们的实验发现，即便是大型基础模型，在这些任务上也存在局限。尤其是，视觉-语言模型并未展现出比仅依赖文本描述的模型更显著的优势，这可能是因为视觉潜能未被充分挖掘。为此，我们创新性地提出了“图像链提示法”，这一方法显著提升了模型性能。同时，我们也公开了相关的代码和数据集。

> We introduce a multimodal dataset where users express preferences through images. These images encompass a broad spectrum of visual expressions ranging from landscapes to artistic depictions. Users request recommendations for books or music that evoke similar feelings to those captured in the images, and recommendations are endorsed by the community through upvotes. This dataset supports two recommendation tasks: title generation and multiple-choice selection. Our experiments with large foundation models reveal their limitations in these tasks. Particularly, vision-language models show no significant advantage over language-only counterparts that use descriptions, which we hypothesize is due to underutilized visual capabilities. To better harness these abilities, we propose the chain-of-imagery prompting, which results in notable improvements. We release our code and datasets.

[Arxiv](https://arxiv.org/abs/2405.14142)