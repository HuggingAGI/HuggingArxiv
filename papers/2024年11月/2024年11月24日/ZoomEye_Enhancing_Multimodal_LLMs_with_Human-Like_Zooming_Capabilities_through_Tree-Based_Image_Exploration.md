# ZoomEye：通过基于树的图像探索，为多模态大型语言模型增添类人缩放的能力

发布时间：2024年11月24日

`LLM应用` `多模态语言模型`

> ZoomEye: Enhancing Multimodal LLMs with Human-Like Zooming Capabilities through Tree-Based Image Exploration

# 摘要

> 一幅图像，特别是高分辨率的那种，往往由众多视觉元素构成，涵盖了从占主导地位的大型物件到精细的细节物件。在感知这类图像时，多模态大型语言模型（MLLMs）因预训练视觉编码器的输入分辨率受限，以及图像上下文的繁杂和密集，存在局限性，致使其侧重于主要物件，而容易忽略细节物件。在本文中，我们提出了 Zoom Eye，这是一种树搜索算法，旨在驾驭图像的层次结构和视觉特性以捕获相关信息。Zoom Eye 把图像概念化为一棵树，每个子节点代表父节点的缩放子区域，根节点代表整幅图像。另外，Zoom Eye 不依赖特定模型且无需训练，所以能让任何 MLLMs 通过从根节点到叶节点沿着图像树进行搜索来模拟人类的缩放动作，找到相关信息，并准确回应相关查询。我们在一系列精心设计的高分辨率基准上开展了实验，结果显示 Zoom Eye 不但大幅且持续提升了一系列基础 MLLMs 的性能（比如，LLaVA-v1.5-7B 在 $V^*$ Bench 上提升了 34.57％，在 HR-Bench 上提升了 17.88％），而且还让小型 7B MLLMs 能够胜过强大的大型模型，如 GPT-4o。我们的代码可在 \href{https://github.com/om-ai-lab/ZoomEye}{https://github.com/om-ai-lab/ZoomEye} 获得。

> An image, especially with high-resolution, typically consists of numerous visual elements, ranging from dominant large objects to fine-grained detailed objects. When perceiving such images, multimodal large language models~(MLLMs) face limitations due to the restricted input resolution of the pretrained vision encoder and the cluttered, dense context of the image, resulting in a focus on primary objects while easily overlooking detailed ones. In this paper, we propose Zoom Eye, a tree search algorithm designed to navigate the hierarchical and visual nature of images to capture relevant information. Zoom Eye conceptualizes an image as a tree, with each children node representing a zoomed sub-patch of the parent node and the root represents the overall image. Moreover, Zoom Eye is model-agnostic and training-free, so it enables any MLLMs to simulate human zooming actions by searching along the image tree from root to leaf nodes, seeking out pertinent information, and accurately responding to related queries. We experiment on a series of elaborate high-resolution benchmarks and the results demonstrate that Zoom Eye not only consistently improves the performance of a series base MLLMs with large margin~(e.g., LLaVA-v1.5-7B increases by 34.57\% on $V^*$ Bench and 17.88\% on HR-Bench), but also enables small 7B MLLMs to outperform strong large models such as GPT-4o. Our code is available at \href{https://github.com/om-ai-lab/ZoomEye}{https://github.com/om-ai-lab/ZoomEye}.

[Arxiv](https://arxiv.org/abs/2411.16044)