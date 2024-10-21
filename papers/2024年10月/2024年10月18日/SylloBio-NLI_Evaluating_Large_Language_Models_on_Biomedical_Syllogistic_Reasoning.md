# SylloBio-NLI：探索大型语言模型在生物医学三段论推理中的表现

发布时间：2024年10月18日

`LLM应用` `生物医学` `自然语言推理`

> SylloBio-NLI: Evaluating Large Language Models on Biomedical Syllogistic Reasoning

# 摘要

> 三段论推理在自然语言推理（NLI）中至关重要，尤其在生物医学领域，它能助力自动证据解读和科学发现。本文推出SylloBio-NLI框架，利用外部本体系统化生成多样化的生物医学NLI三段论。我们通过28种人类基因组通路实例化的三段论方案，评估LLMs在识别有效结论和提取支持证据上的表现。实验显示，零-shot LLMs在生物医学三段论推理上表现不佳，平均准确率在70%（广义肯定前件）和23%（析取三段论）之间。而少-shot提示则显著提升性能，如Gemma提升14%，LLama-3提升43%。但深入分析发现，这些技术对词汇变化高度敏感，可靠性依赖于模型架构和预训练机制。总体来看，尽管上下文示例能激发LLMs的三段论推理，现有模型仍未达到生物医学NLI应用所需的稳健性和一致性。

> Syllogistic reasoning is crucial for Natural Language Inference (NLI). This capability is particularly significant in specialized domains such as biomedicine, where it can support automatic evidence interpretation and scientific discovery. This paper presents SylloBio-NLI, a novel framework that leverages external ontologies to systematically instantiate diverse syllogistic arguments for biomedical NLI. We employ SylloBio-NLI to evaluate Large Language Models (LLMs) on identifying valid conclusions and extracting supporting evidence across 28 syllogistic schemes instantiated with human genome pathways. Extensive experiments reveal that biomedical syllogistic reasoning is particularly challenging for zero-shot LLMs, which achieve an average accuracy between 70% on generalized modus ponens and 23% on disjunctive syllogism. At the same time, we found that few-shot prompting can boost the performance of different LLMs, including Gemma (+14%) and LLama-3 (+43%). However, a deeper analysis shows that both techniques exhibit high sensitivity to superficial lexical variations, highlighting a dependency between reliability, models' architecture, and pre-training regime. Overall, our results indicate that, while in-context examples have the potential to elicit syllogistic reasoning in LLMs, existing models are still far from achieving the robustness and consistency required for safe biomedical NLI applications.

[Arxiv](https://arxiv.org/abs/2410.14399)