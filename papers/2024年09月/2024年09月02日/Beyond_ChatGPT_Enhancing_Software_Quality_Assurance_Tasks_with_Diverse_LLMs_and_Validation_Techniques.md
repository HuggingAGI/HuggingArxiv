# 超越 ChatGPT，通过多样化的 LLM 和验证技术，提升软件质量保证任务的效能。

发布时间：2024年09月02日

`LLM应用` `软件工程` `质量保证`

> Beyond ChatGPT: Enhancing Software Quality Assurance Tasks with Diverse LLMs and Validation Techniques

# 摘要

> 随着 LLM 技术的进步，其在软件质量保证 (SQA) 领域的应用日益增多，但目前研究主要集中在 ChatGPT 上，对不同 LLM 在 SQA 中的表现理解尚浅。本文通过对比 GPT-3.5、GPT-4o 及另外四种 LLM 在故障定位和漏洞检测任务中的表现，揭示了多个 LLM 能超越 GPT-3.5 的潜力。我们发现，结合不同 LLM 的结果，通过投票机制可提升整体性能达 10% 以上。引入交叉验证方法，通过相互验证 LLM 答案，进一步提升了性能，分别在故障定位和漏洞检测上比 GPT-3.5 高出 16% 和 12%，较最佳 LLM 也有 4% 的提升。此外，结果中的解释性内容对交叉验证效果有显著影响。

> With the advancement of Large Language Models (LLMs), their application in Software Quality Assurance (SQA) has increased. However, the current focus of these applications is predominantly on ChatGPT. There remains a gap in understanding the performance of various LLMs in this critical domain. This paper aims to address this gap by conducting a comprehensive investigation into the capabilities of several LLMs across two SQA tasks: fault localization and vulnerability detection. We conducted comparative studies using GPT-3.5, GPT-4o, and four other publicly available LLMs (LLaMA-3-70B, LLaMA-3-8B, Gemma-7B, and Mixtral-8x7B), to evaluate their effectiveness in these tasks.
  Our findings reveal that several LLMs can outperform GPT-3.5 in both tasks. Additionally, even the lower-performing LLMs provided unique correct predictions, suggesting the potential of combining different LLMs' results to enhance overall performance. By implementing a voting mechanism to combine the LLMs' results, we achieved more than a 10% improvement over the GPT-3.5 in both tasks. Furthermore, we introduced a cross-validation approach to refine the LLM answer by validating one LLM answer against another using a validation prompt. This approach led to performance improvements of 16% in fault localization and 12% in vulnerability detection compared to the GPT-3.5, with a 4% improvement compared to the best-performed LLMs. Our analysis also indicates that the inclusion of explanations in the LLMs' results affects the effectiveness of the cross-validation technique.

[Arxiv](https://arxiv.org/abs/2409.01001)