# 现代大型语言模型的数据污染检测面临局限、不一致性及Oracle挑战。

发布时间：2024年09月15日

`LLM理论` `人工智能` `数据科学`

> Towards Data Contamination Detection for Modern Large Language Models: Limitations, Inconsistencies, and Oracle Challenges

# 摘要

> 随着大型语言模型的表现越来越出色，人们开始质疑这种性能是源于泛化能力还是单纯的数据记忆。为此，许多数据污染检测方法应运而生。然而，这些方法多在传统基准和早期LLM上验证，对于评估最先进LLM在更具挑战性基准上的污染效果，其有效性仍存疑。为填补这一空白，我们针对SOTA LLM的污染状态和检测方法的鲁棒性进行了双重研究，评估了五种检测方法在八个现代LLM评估常用的高难度数据集上与四种SOTA LLM的表现。研究发现：（1）现有方法在假设和实际应用中存在显著局限；（2）指令微调中引入的污染，尤其是答案增强情况下的检测，面临重大挑战；（3）SOTA污染检测技术间的一致性有限。这些发现凸显了高级LLM污染检测的复杂性，并迫切需要更鲁棒和泛化的污染评估研究。代码已开源，详见https://github.com/vsamuel2003/data-contamination。

> As large language models achieve increasingly impressive results, questions arise about whether such performance is from generalizability or mere data memorization. Thus, numerous data contamination detection methods have been proposed. However, these approaches are often validated with traditional benchmarks and early-stage LLMs, leaving uncertainty about their effectiveness when evaluating state-of-the-art LLMs on the contamination of more challenging benchmarks. To address this gap and provide a dual investigation of SOTA LLM contamination status and detection method robustness, we evaluate five contamination detection approaches with four state-of-the-art LLMs across eight challenging datasets often used in modern LLM evaluation. Our analysis reveals that (1) Current methods have non-trivial limitations in their assumptions and practical applications; (2) Notable difficulties exist in detecting contamination introduced during instruction fine-tuning with answer augmentation; and (3) Limited consistencies between SOTA contamination detection techniques. These findings highlight the complexity of contamination detection in advanced LLMs and the urgent need for further research on robust and generalizable contamination evaluation. Our code is available at https://github.com/vsamuel2003/data-contamination.

[Arxiv](https://arxiv.org/abs/2409.09927)