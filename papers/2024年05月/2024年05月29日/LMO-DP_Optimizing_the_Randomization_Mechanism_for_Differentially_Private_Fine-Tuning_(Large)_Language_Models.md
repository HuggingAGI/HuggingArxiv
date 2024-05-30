# LMO-DP：为大型语言模型的差分隐私微调优化随机化机制

发布时间：2024年05月29日

`LLM理论

理由：这篇论文主要探讨了在微调大型语言模型时如何实现严格的隐私保护，提出了基于语言模型的最优差分隐私（LMO-DP）机制。这一机制的创新之处在于能够在强隐私保护环境下精确微调大型语言模型，这是一个理论上的突破，因此属于LLM理论分类。论文中提到的差分隐私、噪声搜索方法以及在特定数据集和模型上的应用验证，都是围绕理论机制的实现和优化，而非具体的应用场景或Agent行为，因此不适合归类为Agent、RAG或LLM应用。` `隐私保护`

> LMO-DP: Optimizing the Randomization Mechanism for Differentially Private Fine-Tuning (Large) Language Models

# 摘要

> 为了确保大规模预训练语言模型微调时的严格隐私保护，提出了差分私有随机梯度下降（DP-SGD）及其变体，但它们依赖的高斯机制可能导致梯度过度扰动，从而降低准确性，尤其是在高隐私保护要求下（如隐私预算 $ε< 3$）。为此，我们创新性地提出了基于语言模型的最优差分隐私（LMO-DP）机制，首次实现了即使在强隐私保护环境下（如 $0.1\leq ε<3$），也能精确微调大型语言模型，并与次优DP机制紧密结合。我们还开发了一种离线最优噪声搜索方法，有效减少了噪声幅度。例如，在SST-2数据集上微调3亿参数的RoBERTa-large模型，准确率可达92.20%（$ε=0.3$，$δ=10^{-10}$），显著优于传统高斯机制。同样的结果也在GPT-2的文本生成任务中得到验证。据我们所知，LMO-DP是首个能够准确微调Llama-2并提供强差分隐私保证的方案。相关代码即将发布，并可根据需求提供。

> Differentially Private Stochastic Gradient Descent (DP-SGD) and its variants have been proposed to ensure rigorous privacy for fine-tuning large-scale pre-trained language models. However, they rely heavily on the Gaussian mechanism, which may overly perturb the gradients and degrade the accuracy, especially in stronger privacy regimes (e.g., the privacy budget $ε< 3$). To address such limitations, we propose a novel Language Model-based Optimal Differential Privacy (LMO-DP) mechanism, which takes the first step to enable the tight composition of accurately fine-tuning (large) language models with a sub-optimal DP mechanism, even in strong privacy regimes (e.g., $0.1\leq ε<3$). Furthermore, we propose a novel offline optimal noise search method to efficiently derive the sub-optimal DP that significantly reduces the noise magnitude. For instance, fine-tuning RoBERTa-large (with 300M parameters) on the SST-2 dataset can achieve an accuracy of 92.20% (given $ε=0.3$, $δ=10^{-10}$) by drastically outperforming the Gaussian mechanism (e.g., $\sim 50\%$ for small $ε$ and $δ$). We also draw similar findings on the text generation tasks on GPT-2. Finally, to our best knowledge, LMO-DP is also the first solution to accurately fine-tune Llama-2 with strong differential privacy guarantees. The code will be released soon and available upon request.

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x1.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x2.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x3.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x4.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x5.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x6.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x7.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x8.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x9.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x10.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x11.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x12.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x13.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x14.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x15.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x16.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x17.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x18.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x19.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x20.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x21.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x22.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x23.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x25.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x26.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x27.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x28.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x29.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x30.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x31.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x32.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x33.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x34.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x36.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x37.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x38.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x39.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x40.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x41.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x42.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x43.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x44.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x45.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x46.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x47.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x48.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x49.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x50.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x51.png)

![LMO-DP：为大型语言模型的差分隐私微调优化随机化机制](../../../paper_images/2405.18776/x52.png)

[Arxiv](https://arxiv.org/abs/2405.18776)