# 大型多模态模型中悄然兴起的像素基础技术，无需任何基础监督的加持。

发布时间：2024年10月10日

`LLM应用` `计算机视觉` `人工智能`

> Emerging Pixel Grounding in Large Multimodal Models Without Grounding Supervision

# 摘要

> 当前的大型多模态模型 (LMM) 在将语言与视觉实体关联方面面临挑战。与通常通过额外监督来微调 LMM 的做法不同，我们发现即使在没有明确监督的情况下，LMM 也能自然地发展出这种能力。为此，我们提出了一种“参与和分割”方法，利用 LMM 的注意力图进行像素级分割。此外，我们设计了 DIFFLMM，使用基于扩散的视觉编码器，并通过弱监督训练，使其不受特定监督数据的限制，更具通用性和扩展性。在接地和视觉问答任务中，我们的方法表现出色，尤其在没有监督的情况下，接地对话生成任务中达到了 44.2 的召回率，超越了广泛监督的 GLaMM 模型。项目详情见：https://groundLMM.github.io。

> Current large multimodal models (LMMs) face challenges in grounding, which requires the model to relate language components to visual entities. Contrary to the common practice that fine-tunes LMMs with additional grounding supervision, we find that the grounding ability can in fact emerge in LMMs trained without explicit grounding supervision. To reveal this emerging grounding, we introduce an "attend-and-segment" method which leverages attention maps from standard LMMs to perform pixel-level segmentation. Furthermore, to enhance the grounding ability, we propose DIFFLMM, an LMM utilizing a diffusion-based visual encoder, as opposed to the standard CLIP visual encoder, and trained with the same weak supervision. Without being constrained by the biases and limited scale of grounding-specific supervision data, our approach is more generalizable and scalable. We achieve competitive performance on both grounding-specific and general visual question answering benchmarks, compared with grounding LMMs and generalist LMMs, respectively. Notably, we achieve a 44.2 grounding mask recall on grounded conversation generation without any grounding supervision, outperforming the extensively supervised model GLaMM. Project page: https://groundLMM.github.io.

[Arxiv](https://arxiv.org/abs/2410.08209)