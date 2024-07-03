# 大型语言模型中的判别推理助力法律判决预测

发布时间：2024年07月02日

`LLM应用`

> Enabling Discriminative Reasoning in Large Language Models for Legal Judgment Prediction

# 摘要

> 法律判决预测对提升司法效率至关重要。我们发现，大型语言模型（LLM）在理解案件复杂性和区分相似指控方面存在不足。为此，我们设计了Ask-Discriminate-Predict（ADAPT）框架，模拟人类司法推理过程，通过分解案件事实、区分指控并预测判决，提升LLM在法律领域的应用效果。通过多任务合成轨迹的微调，我们进一步优化了ADAPT框架，使其在处理复杂案件时表现更佳。实验结果显示，ADAPT框架在法律判决预测中展现出显著优势，特别是在应对复杂指控时。

> Legal judgment prediction is essential for enhancing judicial efficiency. In this work, we identify that existing large language models (LLMs) underperform in this domain due to challenges in understanding case complexities and distinguishing between similar charges. To adapt LLMs for effective legal judgment prediction, we introduce the Ask-Discriminate-Predict (ADAPT) reasoning framework inspired by human judicial reasoning. ADAPT involves decomposing case facts, discriminating among potential charges, and predicting the final judgment. We further enhance LLMs through fine-tuning with multi-task synthetic trajectories to improve legal judgment prediction accuracy and efficiency under our ADAPT framework. Extensive experiments conducted on two widely-used datasets demonstrate the superior performance of our framework in legal judgment prediction, particularly when dealing with complex and confusing charges.

[Arxiv](https://arxiv.org/abs/2407.01964)