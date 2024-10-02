# 本文提出了一种结合集成梯度和语言分析的可解释大型语言模型方法论，专注于文本分类任务。

发布时间：2024年09月30日

`LLM应用` `神经科学`

> A Methodology for Explainable Large Language Models with Integrated Gradients and Linguistic Analysis in Text Classification

# 摘要

> 阿尔茨海默病等影响言语的神经疾病，不仅影响患者，也深刻影响护理者的生活。近期，大语言模型（LLM）在识别神经疾病特征方面取得了进展，但这些模型往往“黑箱”操作，缺乏解释性。为此，我们开发了SLIME方法，通过分析自发言语，识别并解释阿尔茨海默病的词汇特征。我们利用BERT模型，结合综合梯度、语言调查和统计分析，揭示了BERT如何利用社交参考减少的词汇来提高诊断准确性。SLIME不仅提升了LLM在神经临床应用中的可信度，也为神经退行性研究提供了有力工具。

> Neurological disorders that affect speech production, such as Alzheimer's Disease (AD), significantly impact the lives of both patients and caregivers, whether through social, psycho-emotional effects or other aspects not yet fully understood. Recent advancements in Large Language Model (LLM) architectures have developed many tools to identify representative features of neurological disorders through spontaneous speech. However, LLMs typically lack interpretability, meaning they do not provide clear and specific reasons for their decisions. Therefore, there is a need for methods capable of identifying the representative features of neurological disorders in speech and explaining clearly why these features are relevant. This paper presents an explainable LLM method, named SLIME (Statistical and Linguistic Insights for Model Explanation), capable of identifying lexical components representative of AD and indicating which components are most important for the LLM's decision. In developing this method, we used an English-language dataset consisting of transcriptions from the Cookie Theft picture description task. The LLM Bidirectional Encoder Representations from Transformers (BERT) classified the textual descriptions as either AD or control groups. To identify representative lexical features and determine which are most relevant to the model's decision, we used a pipeline involving Integrated Gradients (IG), Linguistic Inquiry and Word Count (LIWC), and statistical analysis. Our method demonstrates that BERT leverages lexical components that reflect a reduction in social references in AD and identifies which further improve the LLM's accuracy. Thus, we provide an explainability tool that enhances confidence in applying LLMs to neurological clinical contexts, particularly in the study of neurodegeneration.

[Arxiv](https://arxiv.org/abs/2410.00250)