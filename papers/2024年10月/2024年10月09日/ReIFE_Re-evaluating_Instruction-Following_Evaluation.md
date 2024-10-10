# ReIFE：重新审视指令跟随的评估标准

发布时间：2024年10月09日

`LLM应用` `人工智能`

> ReIFE: Re-evaluating Instruction-Following Evaluation

# 摘要

> 指令跟随的自动评估通常依赖于大型语言模型 (LLM) 来衡量响应质量。然而，现有的评估体系在基础 LLM 和评估协议两个维度上存在明显不足。为此，我们进行了一项全面的元评估，涵盖 25 个基础 LLM 和 15 种新提出的评估协议，并在 4 个经过人工注释的数据集上进行，以检验 LLM 评估器的准确性。通过这项评估，我们能够识别出表现最佳且鲁棒性强的基础 LLM 和评估协议。此外，我们的研究还揭示了以下几点：(1) 基础 LLM 的性能排名在不同评估协议中基本稳定，而能力较弱的 LLM 则能从协议优化中获得更大提升；(2) 要实现对评估协议的稳健评估，需要多种不同能力水平的基础 LLM，因为协议的效果可能因所选基础 LLM 而异；(3) 不同数据集上的评估结果可能存在差异，因此严谨的评估应涵盖多个特征各异的数据集。我们公开了元评估工具包 ReIFE，其中包含超过 500 种 LLM 评估器配置的代码和评估结果，旨在推动指令跟随评估领域的进一步研究。

> The automatic evaluation of instruction following typically involves using large language models (LLMs) to assess response quality. However, there is a lack of comprehensive evaluation of these LLM-based evaluators across two dimensions: the base LLMs and the evaluation protocols. Therefore, we present a thorough meta-evaluation of instruction following, including 25 base LLMs and 15 recently proposed evaluation protocols, on 4 human-annotated datasets, assessing the evaluation accuracy of the LLM-evaluators. Our evaluation allows us to identify the best-performing base LLMs and evaluation protocols with a high degree of robustness. Moreover, our large-scale evaluation reveals: (1) Base LLM performance ranking remains largely consistent across evaluation protocols, with less capable LLMs showing greater improvement from protocol enhancements; (2) Robust evaluation of evaluation protocols requires many base LLMs with varying capability levels, as protocol effectiveness can depend on the base LLM used; (3) Evaluation results on different datasets are not always consistent, so a rigorous evaluation requires multiple datasets with distinctive features. We release our meta-evaluation suite ReIFE, which provides the codebase and evaluation result collection for more than 500 LLM-evaluator configurations, to support future research in instruction-following evaluation.

[Arxiv](https://arxiv.org/abs/2410.07069)