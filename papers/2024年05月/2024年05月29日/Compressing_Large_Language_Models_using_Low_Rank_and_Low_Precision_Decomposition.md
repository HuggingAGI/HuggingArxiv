# 通过低秩与低精度分解精简大型语言模型

发布时间：2024年05月29日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的压缩技术，特别是通过$\rm CALDERA$算法实现权重矩阵的低秩、低精度分解，以适应内存受限的边缘设备。这种研究属于对LLMs理论层面的改进和优化，旨在解决模型部署中的实际问题，如内存限制和性能保持。因此，它更符合LLM理论分类，而不是Agent、RAG或LLM应用。` `边缘计算` `模型压缩`

> Compressing Large Language Models using Low Rank and Low Precision Decomposition

# 摘要

> 大型语言模型（LLMs）因其庞大的体积而难以在内存受限的边缘设备上部署。本研究推出的$\rm CALDERA$算法，通过低秩、低精度分解近似权重矩阵$\mathbf{W}$，实现了模型的有效压缩。具体而言，$\mathbf{W}$被分解为$\mathbf{Q} + \mathbf{L}\mathbf{R}$，其中各元素经过量化，$\mathbf{L}$和$\mathbf{R}$易于进一步的低秩适应，从而提升模型的零-shot性能。通过优化问题$\min_{\mathbf{Q},\mathbf{L},\mathbf{R}}\lVert(\mathbf{Q} + \mathbf{L}\mathbf{R} - \mathbf{W})\mathbf{X}^\top\rVert_{\rm F}^2$，$\rm CALDERA$实现了这一分解，其中$\mathbf{X}$为校准数据，$\mathbf{Q}$、$\mathbf{L}$、$\mathbf{R}$采用低精度格式表示。理论分析表明，$\rm CALDERA$在压缩比与模型性能之间找到了平衡点，尤其在每参数少于$2.5$比特的情况下，其压缩效果优于现有技术。实现代码已公开，详情请访问：\href{https://github.com/pilancilab/caldera}{https://github.com/pilancilab/caldera}。

> The prohibitive sizes of Large Language Models (LLMs) today make it difficult to deploy them on memory-constrained edge devices. This work introduces $\rm CALDERA$ -- a new post-training LLM compression algorithm that harnesses the inherent low-rank structure of a weight matrix $\mathbf{W}$ by approximating it via a low-rank, low-precision decomposition as $\mathbf{W} \approx \mathbf{Q} + \mathbf{L}\mathbf{R}$. Here, $\mathbf{L}$ and $\mathbf{R}$ are low rank factors, and the entries of $\mathbf{Q}$, $\mathbf{L}$ and $\mathbf{R}$ are quantized. The model is compressed by substituting each layer with its $\mathbf{Q} + \mathbf{L}\mathbf{R}$ decomposition, and the zero-shot performance of the compressed model is evaluated. Additionally, $\mathbf{L}$ and $\mathbf{R}$ are readily amenable to low-rank adaptation, consequently enhancing the zero-shot performance. $\rm CALDERA$ obtains this decomposition by formulating it as an optimization problem $\min_{\mathbf{Q},\mathbf{L},\mathbf{R}}\lVert(\mathbf{Q} + \mathbf{L}\mathbf{R} - \mathbf{W})\mathbf{X}^\top\rVert_{\rm F}^2$, where $\mathbf{X}$ is the calibration data, and $\mathbf{Q}, \mathbf{L}, \mathbf{R}$ are constrained to be representable using low-precision formats. Theoretical upper bounds on the approximation error of $\rm CALDERA$ are established using a rank-constrained regression framework, and the tradeoff between compression ratio and model performance is studied by analyzing the impact of target rank and quantization bit budget. Results illustrate that compressing LlaMa-$2$ $7$B/$70$B and LlaMa-$3$ $8$B models obtained using $\rm CALDERA$ outperforms existing post-training LLM compression techniques in the regime of less than $2.5$ bits per parameter. The implementation is available at: \href{https://github.com/pilancilab/caldera}{https://github.com/pilancilab/caldera}.

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x1.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x2.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x3.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x4.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x5.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x6.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x7.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x8.png)

![通过低秩与低精度分解精简大型语言模型](../../../paper_images/2405.18886/x9.png)

[Arxiv](https://arxiv.org/abs/2405.18886)