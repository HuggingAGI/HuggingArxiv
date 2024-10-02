# 加法，高效语言模型的关键

发布时间：2024年10月01日

`LLM理论` `人工智能` `半导体`

> Addition is All You Need for Energy-efficient Language Models

# 摘要

> 大型神经网络主要依赖浮点张量乘法进行计算。我们发现，高精度浮点乘法可通过整数加法近似实现。为此，我们设计了线性复杂度的 L-Mul 算法，通过整数加法模拟浮点乘法，不仅大幅节省计算资源，还提升了精度。与 8 位浮点乘法相比，L-Mul 在位级计算上更为高效。由于浮点乘法能耗远高于整数加法，L-Mul 在张量处理硬件中的应用有望降低 95% 的逐元素浮点乘法能耗和 80% 的点积能耗。我们通过理论误差分析和广泛的任务测试（如自然语言理解、结构推理、数学和常识问答）验证了 L-Mul 的性能。实验表明，4 位尾数的 L-Mul 与 float8_e4m3 乘法精度相当，而 3 位尾数的 L-Mul 则超越了 float8_e5m2。在注意力机制中的应用几乎无损，且在 transformer 模型中全面替换浮点乘法后，微调和推理精度均与 float8_e4m3 累积精度相当。

> Large neural networks spend most computation on floating point tensor multiplications. In this work, we find that a floating point multiplier can be approximated by one integer adder with high precision. We propose the linear-complexity multiplication L-Mul algorithm that approximates floating point number multiplication with integer addition operations. The new algorithm costs significantly less computation resource than 8-bit floating point multiplication but achieves higher precision. Compared to 8-bit floating point multiplications, the proposed method achieves higher precision but consumes significantly less bit-level computation. Since multiplying floating point numbers requires substantially higher energy compared to integer addition operations, applying the L-Mul operation in tensor processing hardware can potentially reduce 95% energy cost by element-wise floating point tensor multiplications and 80% energy cost of dot products. We calculated the theoretical error expectation of L-Mul, and evaluated the algorithm on a wide range of textual, visual, and symbolic tasks, including natural language understanding, structural reasoning, mathematics, and commonsense question answering. Our numerical analysis experiments agree with the theoretical error estimation, which indicates that L-Mul with 4-bit mantissa achieves comparable precision as float8_e4m3 multiplications, and L-Mul with 3-bit mantissa outperforms float8_e5m2. Evaluation results on popular benchmarks show that directly applying L-Mul to the attention mechanism is almost lossless. We further show that replacing all floating point multiplications with 3-bit mantissa L-Mul in a transformer model achieves equivalent precision as using float8_e4m3 as accumulation precision in both fine-tuning and inference.

[Arxiv](https://arxiv.org/abs/2410.00907)