# AutoFeedback：基于 LLM 的高效精准 API 请求生成框架

发布时间：2024年10月09日

`LLM应用` `软件开发` `人工智能`

> AutoFeedback: An LLM-based Framework for Efficient and Accurate API Request Generation

# 摘要

> 大型语言模型 (LLM) 通过生成 API 请求来利用外部工具，以提升任务完成效率。然而，由于 LLM 固有的幻觉问题，生成准确 API 请求的难度较大。当前研究虽采用基于提示的反馈来改进 API 请求生成，但仍存在事实信息不足和细节不够的问题。为此，我们提出了 AutoFeedback 框架，包含静态扫描组件 (SSC) 和动态分析组件 (DAC)，分别通过纳入伪事实和检索 API 文档信息来丰富反馈内容。实验结果显示，AutoFeedback 不仅显著提升了 API 请求生成的准确性，还大幅降低了与 GPT-3.5 Turbo 和 GPT-4 Turbo 的交互成本。

> Large Language Models (LLMs) leverage external tools primarily through generating the API request to enhance task completion efficiency. The accuracy of API request generation significantly determines the capability of LLMs to accomplish tasks.
  Due to the inherent hallucinations within the LLM, it is difficult to efficiently and accurately generate the correct API request.
  Current research uses prompt-based feedback to facilitate the LLM-based API request generation. However, existing methods lack factual information and are insufficiently detailed.
  To address these issues, we propose AutoFeedback, an LLM-based framework for efficient and accurate API request generation, with a Static Scanning Component (SSC) and a Dynamic Analysis Component (DAC). SSC incorporates errors detected in the API requests as pseudo-facts into the feedback, enriching the factual information. DAC retrieves information from API documentation, enhancing the level of detail in feedback.
  Based on this two components, Autofeedback implementes two feedback loops during the process of generating API requests by the LLM.
  Extensive experiments demonstrate that it significantly improves accuracy of API request generation and reduces the interaction cost. AutoFeedback achieves an accuracy of 100.00\% on a real-world API dataset and reduces the cost of interaction with GPT-3.5 Turbo by 23.44\%, and GPT-4 Turbo by 11.85\%.

[Arxiv](https://arxiv.org/abs/2410.06943)