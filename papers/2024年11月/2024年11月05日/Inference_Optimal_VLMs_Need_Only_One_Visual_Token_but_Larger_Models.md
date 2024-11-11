# 推理最优的视觉语言模型（VLMs）只需要一个视觉标记，但需要更大的模型。

发布时间：2024年11月05日

`LLM应用`

> Inference Optimal VLMs Need Only One Visual Token but Larger Models

# 摘要

> 视觉语言模型（VLMs）在各种视觉理解和推理任务中展现出了强大的能力。然而，它们在现实世界中的部署常常受到推理过程中高延迟的限制，这是由于大型语言模型（LLM）处理大量输入标记（主要来自图像）所需的大量计算。为了降低推理成本，可以缩小 LLM 的规模或减少输入图像标记的数量，后者是近期许多关于标记压缩工作的重点。然而，不清楚最优的权衡是什么，因为这两个因素都直接影响 VLM 的性能。我们首先通过建立缩放定律来描述视觉标记数量和 LLM 参数之间的这种最优权衡，该定律捕捉了这两个因素在性能上的变化。我们的结果揭示了一个令人惊讶的趋势：对于视觉推理任务，VLM 中的推理最优行为，即在任何给定的固定推理计算中最小的下游错误，是在使用适合推理预算的最大 LLM 同时将视觉标记数量最小化——通常到单个标记时实现的。虽然标记减少的文献主要集中在通过适度减少标记数量（例如，5 - 10 倍）来维持基础模型性能，但我们的结果表明，计算最优的推理机制需要在更高的标记压缩比率下运行。基于这些见解，我们朝着为高标记压缩设置构建定制方法迈出了一些初步的步骤。代码可在 https://github.com/locuslab/llava-token-compression 获得。

> Vision Language Models (VLMs) have demonstrated strong capabilities across various visual understanding and reasoning tasks. However, their real-world deployment is often constrained by high latency during inference due to substantial compute required to process the large number of input tokens (predominantly from the image) by the LLM. To reduce inference costs, one can either downsize the LLM or reduce the number of input image-tokens, the latter of which has been the focus of many recent works around token compression. However, it is unclear what the optimal trade-off is, as both the factors directly affect the VLM performance. We first characterize this optimal trade-off between the number of visual tokens and LLM parameters by establishing scaling laws that capture variations in performance with these two factors. Our results reveal a surprising trend: for visual reasoning tasks, the inference-optimal behavior in VLMs, i.e., minimum downstream error at any given fixed inference compute, is achieved when using the largest LLM that fits within the inference budget while minimizing visual token count - often to a single token. While the token reduction literature has mainly focused on maintaining base model performance by modestly reducing the token count (e.g., $5-10\times$), our results indicate that the compute-optimal inference regime requires operating under even higher token compression ratios. Based on these insights, we take some initial steps towards building approaches tailored for high token compression settings. Code is available at https://github.com/locuslab/llava-token-compression.

[Arxiv](https://arxiv.org/abs/2411.03312)