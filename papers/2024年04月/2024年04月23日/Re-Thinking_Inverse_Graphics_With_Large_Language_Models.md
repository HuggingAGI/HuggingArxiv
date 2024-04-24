# 在大型语言模型的辅助下，逆向图形学领域正经历着一场思维革新。尽管如此，LLMs 在图像生成任务上的表现和效率，依旧是一个备受争议的话题。

发布时间：2024年04月23日

`LLM应用` `计算机视觉` `图形学`

> Re-Thinking Inverse Graphics With Large Language Models

# 摘要

> 逆向图形学，即将图像转换为可重现所观察场景的物理变量，是计算机视觉与图形学领域的一个基础性难题。这一过程需要将图像细化为其基本组成，如3D场景中物体的形状、颜色和材质等，这要求对环境有深入的理解。这种全面性的需求限制了现有方法在不同领域间的泛化能力。受到大型语言模型（LLMs）在新情境下的零样本学习能力的启发，本研究探索了利用这些模型中蕴含的丰富世界知识来攻克逆向图形问题的可行性。我们提出了一个名为逆向图形大型语言模型（IG-LLM）的新框架，它以LLM为核心，能够自回归地将视觉嵌入转换为结构化的3D场景表示。该框架整合了预训练的视觉编码器和连续数值头部，支持端到端的训练。我们的研究展示了LLMs在无需图像空间监督的情况下，通过下一个词预测来促进逆向图形的潜力。这一发现为利用LLMs的视觉知识进行图像的空间推理提供了新的视角。为了确保研究的可复制性并推动未来研究，我们将在 https://ig-llm.is.tue.mpg.de/ 上发布相关代码和数据。

> Inverse graphics -- the task of inverting an image into physical variables that, when rendered, enable reproduction of the observed scene -- is a fundamental challenge in computer vision and graphics. Disentangling an image into its constituent elements, such as the shape, color, and material properties of the objects of the 3D scene that produced it, requires a comprehensive understanding of the environment. This requirement limits the ability of existing carefully engineered approaches to generalize across domains. Inspired by the zero-shot ability of large language models (LLMs) to generalize to novel contexts, we investigate the possibility of leveraging the broad world knowledge encoded in such models in solving inverse-graphics problems. To this end, we propose the Inverse-Graphics Large Language Model (IG-LLM), an inverse-graphics framework centered around an LLM, that autoregressively decodes a visual embedding into a structured, compositional 3D-scene representation. We incorporate a frozen pre-trained visual encoder and a continuous numeric head to enable end-to-end training. Through our investigation, we demonstrate the potential of LLMs to facilitate inverse graphics through next-token prediction, without the use of image-space supervision. Our analysis opens up new possibilities for precise spatial reasoning about images that exploit the visual knowledge of LLMs. We will release our code and data to ensure the reproducibility of our investigation and to facilitate future research at https://ig-llm.is.tue.mpg.de/

[Arxiv](https://arxiv.org/abs/2404.15228)