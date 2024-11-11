# 探索大型多语言模型中的响应不确定性：在误导场景下的实证评估

发布时间：2024年11月04日

`LLM应用` `多模态` `语言模型`

> Exploring Response Uncertainty in MLLMs: An Empirical Evaluation under Misleading Scenarios

# 摘要

> 确保多模态大型语言模型（MLLMs）在其响应中保持一致性对于开发可信的多模态智能至关重要。然而，现有的基准包含许多样本，其中所有的 MLLMs 在遇到误导信息时都表现出高响应不确定性，每个样本甚至需要 5 - 15 次响应尝试才能有效评估不确定性。因此，我们提出了一个两阶段的流程：首先，我们收集 MLLMs 没有误导信息的响应，然后通过特定的误导指令收集有误导的响应。通过计算误导率，并捕捉两组响应之间从正确到错误和从错误到正确的转变，我们可以有效地衡量模型的响应不确定性。最终，我们建立了一个多模态不确定性基准（MUB），它使用显性和隐性的误导指令来全面评估 MLLMs 在不同领域的脆弱性。我们的实验表明，所有开源和闭源的 MLLMs 都极易受到误导指令的影响，平均误导率超过 86％。为了增强 MLLMs 的鲁棒性，我们进一步通过纳入显性和隐性的误导数据对所有开源的 MLLMs 进行微调，这表明误导率显著降低。我们的代码可在：https://github.com/Yunkai696/MUB 获得。

> Ensuring that Multimodal Large Language Models (MLLMs) maintain consistency in their responses is essential for developing trustworthy multimodal intelligence. However, existing benchmarks include many samples where all MLLMs \textit{exhibit high response uncertainty when encountering misleading information}, requiring even 5-15 response attempts per sample to effectively assess uncertainty. Therefore, we propose a two-stage pipeline: first, we collect MLLMs' responses without misleading information, and then gather misleading ones via specific misleading instructions. By calculating the misleading rate, and capturing both correct-to-incorrect and incorrect-to-correct shifts between the two sets of responses, we can effectively metric the model's response uncertainty. Eventually, we establish a \textbf{underline{M}}ultimodal \textbf{underline{U}}ncertainty \textbf{underline{B}}enchmark (\textbf{MUB}) that employs both explicit and implicit misleading instructions to comprehensively assess the vulnerability of MLLMs across diverse domains. Our experiments reveal that all open-source and close-source MLLMs are highly susceptible to misleading instructions, with an average misleading rate exceeding 86\%. To enhance the robustness of MLLMs, we further fine-tune all open-source MLLMs by incorporating explicit and implicit misleading data, which demonstrates a significant reduction in misleading rates. Our code is available at: \href{https://github.com/Yunkai696/MUB}{https://github.com/Yunkai696/MUB}

[Arxiv](https://arxiv.org/abs/2411.02708)