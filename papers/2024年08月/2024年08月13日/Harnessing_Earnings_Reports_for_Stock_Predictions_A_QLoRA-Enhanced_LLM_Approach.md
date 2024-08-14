# 通过财报洞察股市：基于QLoRA优化的LLM预测策略

发布时间：2024年08月13日

`LLM应用`

> Harnessing Earnings Reports for Stock Predictions: A QLoRA-Enhanced LLM Approach

# 摘要

> 投资者对财报后股市预测的准确性极为重视。传统机器学习模型因难以处理财报中的大量文本数据且常忽视市场动态的细微差别而表现不佳。本文采用大型语言模型（LLM）结合基于指令的技术和QLoRA压缩进行精细调整，提出了一种先进方法。我们整合了财务指标增长、财报会议记录等“基础因素”与市场指数表现、分析师评级等“外部因素”，构建了丰富的监督数据集。这使得模型在准确性、加权F1和MCC上表现卓越，尤其在与GPT-4等基准对比时更为突出。特别地，llama-3-8b-Instruct-4bit模型在基线模型上取得了显著进步。此外，本文探讨了增加“持有”选项和延长预测时间范围的可能性，以适应多样化的投资风格和时间框架。这项研究不仅展示了尖端AI与精细财务数据结合的强大力量，也为未来AI驱动的财务分析工具的改进研究奠定了基础。

> Accurate stock market predictions following earnings reports are crucial for investors. Traditional methods, particularly classical machine learning models, struggle with these predictions because they cannot effectively process and interpret extensive textual data contained in earnings reports and often overlook nuances that influence market movements. This paper introduces an advanced approach by employing Large Language Models (LLMs) instruction fine-tuned with a novel combination of instruction-based techniques and quantized low-rank adaptation (QLoRA) compression. Our methodology integrates 'base factors', such as financial metric growth and earnings transcripts, with 'external factors', including recent market indices performances and analyst grades, to create a rich, supervised dataset. This comprehensive dataset enables our models to achieve superior predictive performance in terms of accuracy, weighted F1, and Matthews correlation coefficient (MCC), especially evident in the comparison with benchmarks such as GPT-4. We specifically highlight the efficacy of the llama-3-8b-Instruct-4bit model, which showcases significant improvements over baseline models. The paper also discusses the potential of expanding the output capabilities to include a 'Hold' option and extending the prediction horizon, aiming to accommodate various investment styles and time frames. This study not only demonstrates the power of integrating cutting-edge AI with fine-tuned financial data but also paves the way for future research in enhancing AI-driven financial analysis tools.

[Arxiv](https://arxiv.org/abs/2408.06634)