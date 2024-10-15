# 大型语言模型的矩阵核范数评估

发布时间：2024年10月14日

`LLM理论` `人工智能` `计算机科学`

> Large Language Model Evaluation via Matrix Nuclear-Norm

# 摘要

> 随着 LLM 的进步，评估其信息压缩能力的指标变得尤为重要。传统的矩阵熵虽有价值，但其 \( O(n^3) \) 的复杂度限制了其在大模型中的应用。为此，我们提出了矩阵核范数，它不仅量化了 LLM 的压缩能力，还通过凸近似简化了计算。通过 \( L_{1,2}\text{-norm} \) 的进一步近似，我们实现了 \( O(n^2) \) 的复杂度，无需 SVD。实验表明，对于 CEREBRAS-GPT 模型，矩阵核范数的计算速度比矩阵熵快 8 到 24 倍，且随着模型规模的增大，优势更加明显。基准测试和模型响应的评估进一步证实了其可靠性和高效性。代码已开源，详情请访问 https://github.com/MLGroupJLU/MatrixNuclearNorm。

> As large language models (LLMs) continue to evolve, efficient evaluation metrics are vital for assessing their ability to compress information and reduce redundancy. While traditional metrics like Matrix Entropy offer valuable insights, they are computationally intensive for large-scale models due to their \( O(n^3) \) time complexity with Singular Value Decomposition (SVD). To mitigate this issue, we introduce the Matrix Nuclear-Norm, which not only serves as a metric to quantify the data compression proficiency of LLM but also provides a convex approximation of matrix rank to capture both predictive discriminability and diversity. By employing the \( L_{1,2}\text{-norm} \) to further approximate the nuclear norm, we can effectively assess the model's information compression capabilities. This approach reduces the time complexity to \( O(n^2) \) and eliminates the need for SVD computation. Consequently, the Matrix Nuclear-Norm achieves speeds 8 to 24 times faster than Matrix Entropy for the CEREBRAS-GPT model as sizes increase from 111M to 6.7B. This performance gap becomes more pronounced with larger models, as validated in tests with other models like Pythia. Additionally, evaluations on benchmarks and model responses confirm that our proposed Matrix Nuclear-Norm is a reliable, scalable, and efficient tool for assessing LLMs' performance, striking a balance between accuracy and computational efficiency. The code is available at https://github.com/MLGroupJLU/MatrixNuclearNorm.

[Arxiv](https://arxiv.org/abs/2410.10672)