# 功能同伦：利用连续参数平滑离散优化，破解 LLM 的安全防线

发布时间：2024年10月05日

`LLM理论` `人工智能` `网络安全`

> Functional Homotopy: Smoothing Discrete Optimization via Continuous Parameters for LLM Jailbreak Attacks

# 摘要

> 在深度学习中，优化方法常用于识别和缓解不希望的模型响应。尽管基于梯度的技术对图像模型有效，但在语言模型中受限于输入的离散性。本研究提出了一种名为 \emph{functional homotopy} 的新方法，利用模型训练与输入生成间的对偶性，通过构建由易到难的优化问题，迭代解决。该方法在绕过 Llama-2 和 Llama-3 等安全模型时，成功率比现有方法提高了 $20\%-30\%$。

> Optimization methods are widely employed in deep learning to identify and mitigate undesired model responses. While gradient-based techniques have proven effective for image models, their application to language models is hindered by the discrete nature of the input space. This study introduces a novel optimization approach, termed the \emph{functional homotopy} method, which leverages the functional duality between model training and input generation. By constructing a series of easy-to-hard optimization problems, we iteratively solve these problems using principles derived from established homotopy methods. We apply this approach to jailbreak attack synthesis for large language models (LLMs), achieving a $20\%-30\%$ improvement in success rate over existing methods in circumventing established safe open-source models such as Llama-2 and Llama-3.

[Arxiv](https://arxiv.org/abs/2410.04234)