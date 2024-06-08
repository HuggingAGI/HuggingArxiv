# Wings：无文本遗忘的多模态LLM学习之旅

发布时间：2024年06月05日

`LLM应用

这篇论文介绍了一种新型的多模态大型语言模型（MLLM），即Wings模型，它旨在解决MLLM在处理纯文本指令时的问题，并通过增强学习模块和特定的注意力机制来优化模型在纯文本和多模态输入上的表现。这种模型的发展和应用直接关联到LLM的实际应用场景，特别是在多模态理解和问答任务中。因此，这篇论文应归类于LLM应用。` `人工智能` `问答系统`

> Wings: Learning Multimodal LLMs without Text-only Forgetting

# 摘要

> 多模态大型语言模型（MLLMs），以训练有素的LLM为起点，首先将图像与文本对齐，随后对多模态输入进行精细调整。但问题在于，MLLM会遗忘不含图像的纯文本指令，而这些本可在原始LLM中得到妥善处理。本文介绍的Wings模型，是一种创新型MLLM，它在纯文本对话和多模态理解上均表现卓越。通过分析MLLM在多模态指令中的注意力机制，我们发现纯文本遗忘与从图像前到图像后的文本注意力转移有关。为此，我们设计了额外的增强学习模块，以补偿这种注意力转移。这些视觉与文本学习者，宛如两侧的“翅膀”，在每一层的注意力模块中并行运作，确保视觉元素的关注平衡。文本学习者随后通过基于注意力的路由与视觉学习者协同工作，融合两者的输出。我们提出的低秩残差注意力（LoRRA）机制，确保了学习过程的高效性。实验证明，Wings在纯文本和视觉问答任务中均超越了同等规模的MLLMs。在全新构建的交错图像文本（IIT）基准测试中，Wings在从纯文本到多模态丰富的问答任务中展现了卓越性能。

> Multimodal large language models (MLLMs), initiated with a trained LLM, first align images with text and then fine-tune on multimodal mixed inputs. However, the MLLM catastrophically forgets the text-only instructions, which do not include images and can be addressed within the initial LLM. In this paper, we present Wings, a novel MLLM that excels in both text-only dialogues and multimodal comprehension. Analyzing MLLM attention in multimodal instructions reveals that text-only forgetting is related to the attention shifts from pre-image to post-image text. From that, we construct extra modules that act as the boosted learner to compensate for the attention shift. The complementary visual and textual learners, like "wings" on either side, are connected in parallel within each layer's attention block. Initially, image and text inputs are aligned with visual learners operating alongside the main attention, balancing focus on visual elements. Textual learners are later collaboratively integrated with attention-based routing to blend the outputs of the visual and textual learners. We design the Low-Rank Residual Attention (LoRRA) to guarantee high efficiency for learners. Our experimental results demonstrate that Wings outperforms equally-scaled MLLMs in both text-only and visual question-answering tasks. On a newly constructed Interleaved Image-Text (IIT) benchmark, Wings exhibits superior performance from text-only-rich to multimodal-rich question-answering tasks.

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x1.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x2.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x3.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x4.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x5.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x6.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x7.png)

![Wings：无文本遗忘的多模态LLM学习之旅](../../../paper_images/2406.03496/x8.png)

[Arxiv](https://arxiv.org/abs/2406.03496)