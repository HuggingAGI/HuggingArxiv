# COM3D：借助跨视图匹配与跨模态挖掘，精进3D检索技艺在这项研究中，我们提出了一种名为COM3D的新型框架，它巧妙地结合了跨视图对应和跨模态挖掘技术，以提升3D对象检索的准确性和效率。通过深入分析不同视图间的内在联系，并挖掘多模态数据中的潜在信息，COM3D在3D检索领域展现了其独特的优势。

发布时间：2024年05月07日

`RAG

这篇论文探讨的是3D形状与文本描述之间的跨模态检索任务，这是一个典型的跨模态检索问题，涉及到将文本信息与3D形状数据进行匹配。论文中提出的COM3D方法结合了跨视图对应与跨模态挖掘技术，这些技术可以被视为一种检索增强生成（RAG）的应用，因为它旨在增强检索系统的能力，通过跨模态匹配来提高检索精度。因此，这篇论文更符合RAG分类，而不是Agent、LLM应用或LLM理论。` `跨模态检索` `3D建模`

> COM3D: Leveraging Cross-View Correspondence and Cross-Modal Mining for 3D Retrieval

# 摘要

> 本文探讨了3D形状与文本描述间跨模态检索的挑战性任务。传统方法依赖点云编码器提取特征，却可能遗漏3D形状的深度、空间结构和几何连续性等核心特征。为此，我们创新性地提出了COM3D方法，首次结合跨视图对应与跨模态挖掘技术，显著提升检索精度。我们的方法通过场景表示变换器丰富3D特征，生成跨视图特征，增强与文本匹配的兼容性。同时，采用半硬负例挖掘优化跨模态匹配，提升学习效率。实验结果表明，COM3D在Text2Shape数据集上取得了领先性能，展现了其卓越的检索能力。

> In this paper, we investigate an open research task of cross-modal retrieval between 3D shapes and textual descriptions. Previous approaches mainly rely on point cloud encoders for feature extraction, which may ignore key inherent features of 3D shapes, including depth, spatial hierarchy, geometric continuity, etc. To address this issue, we propose COM3D, making the first attempt to exploit the cross-view correspondence and cross-modal mining to enhance the retrieval performance. Notably, we augment the 3D features through a scene representation transformer, to generate cross-view correspondence features of 3D shapes, which enrich the inherent features and enhance their compatibility with text matching. Furthermore, we propose to optimize the cross-modal matching process based on the semi-hard negative example mining method, in an attempt to improve the learning efficiency. Extensive quantitative and qualitative experiments demonstrate the superiority of our proposed COM3D, achieving state-of-the-art results on the Text2Shape dataset.

![COM3D：借助跨视图匹配与跨模态挖掘，精进3D检索技艺在这项研究中，我们提出了一种名为COM3D的新型框架，它巧妙地结合了跨视图对应和跨模态挖掘技术，以提升3D对象检索的准确性和效率。通过深入分析不同视图间的内在联系，并挖掘多模态数据中的潜在信息，COM3D在3D检索领域展现了其独特的优势。](../../../paper_images/2405.04103/x1.png)

![COM3D：借助跨视图匹配与跨模态挖掘，精进3D检索技艺在这项研究中，我们提出了一种名为COM3D的新型框架，它巧妙地结合了跨视图对应和跨模态挖掘技术，以提升3D对象检索的准确性和效率。通过深入分析不同视图间的内在联系，并挖掘多模态数据中的潜在信息，COM3D在3D检索领域展现了其独特的优势。](../../../paper_images/2405.04103/x2.png)

![COM3D：借助跨视图匹配与跨模态挖掘，精进3D检索技艺在这项研究中，我们提出了一种名为COM3D的新型框架，它巧妙地结合了跨视图对应和跨模态挖掘技术，以提升3D对象检索的准确性和效率。通过深入分析不同视图间的内在联系，并挖掘多模态数据中的潜在信息，COM3D在3D检索领域展现了其独特的优势。](../../../paper_images/2405.04103/x3.png)

![COM3D：借助跨视图匹配与跨模态挖掘，精进3D检索技艺在这项研究中，我们提出了一种名为COM3D的新型框架，它巧妙地结合了跨视图对应和跨模态挖掘技术，以提升3D对象检索的准确性和效率。通过深入分析不同视图间的内在联系，并挖掘多模态数据中的潜在信息，COM3D在3D检索领域展现了其独特的优势。](../../../paper_images/2405.04103/x4.png)

[Arxiv](https://arxiv.org/abs/2405.04103)