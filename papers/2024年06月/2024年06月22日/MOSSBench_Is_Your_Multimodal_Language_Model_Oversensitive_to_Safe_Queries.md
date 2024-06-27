# MOSSBench：探究多模态语言模型对安全查询的敏感度。

发布时间：2024年06月22日

`LLM应用

这篇论文主要探讨了多元大型语言模型（MLLMs）在面对特定视觉刺激时的过度敏感性问题，并开发了一个基准（MOSSBench）来评估这些模型的过度敏感性。研究结果显示，即使是顶尖的MLLMs也存在过度敏感的问题，这影响了它们在实际应用中的可靠性。因此，这项工作属于LLM应用类别，因为它关注的是大型语言模型在实际应用中遇到的具体问题和挑战，以及如何通过建立评估基准来改进这些模型。` `人工智能安全` `认知科学`

> MOSSBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?

# 摘要

> 人类常因认知扭曲而对特定刺激反应过度，而先进的多元大型语言模型（MLLMs）亦有此倾向。尽管这些模型内置安全机制，有时却因特定视觉刺激而错误拒绝无害查询，忽略了其良性情境。我们首先识别出三种触发MLLMs过度敏感的刺激：夸大风险、否定伤害和反直觉解释。为此，我们开发了多元过度敏感性基准（MOSSBench），包含300个经第三方验证的良性多元查询，用以评估MLLMs的过度敏感性。研究显示，顶尖MLLMs普遍存在过度敏感，无害查询的拒绝率高达76%；安全模型反而更敏感，可能因增强安全而增加了模型的谨慎和保守性；不同刺激在MLLMs响应的不同阶段——感知、意图推理和安全判断——引发错误。这些发现凸显了需要更精细的安全机制，以确保MLLMs在实际应用中的可靠性，我们的项目已公开于https://turningpoint-ai.github.io/MOSSBench/。

> Humans are prone to cognitive distortions -- biased thinking patterns that lead to exaggerated responses to specific stimuli, albeit in very different contexts. This paper demonstrates that advanced Multimodal Large Language Models (MLLMs) exhibit similar tendencies. While these models are designed to respond queries under safety mechanism, they sometimes reject harmless queries in the presence of certain visual stimuli, disregarding the benign nature of their contexts. As the initial step in investigating this behavior, we identify three types of stimuli that trigger the oversensitivity of existing MLLMs: Exaggerated Risk, Negated Harm, and Counterintuitive Interpretation. To systematically evaluate MLLMs' oversensitivity to these stimuli, we propose the Multimodal OverSenSitivity Benchmark (MOSSBench). This toolkit consists of 300 manually collected benign multimodal queries, cross-verified by third-party reviewers (AMT). Empirical studies using MOSSBench on 20 MLLMs reveal several insights: (1). Oversensitivity is prevalent among SOTA MLLMs, with refusal rates reaching up to 76% for harmless queries. (2). Safer models are more oversensitive: increasing safety may inadvertently raise caution and conservatism in the model's responses. (3). Different types of stimuli tend to cause errors at specific stages -- perception, intent reasoning, and safety judgement -- in the response process of MLLMs. These findings highlight the need for refined safety mechanisms that balance caution with contextually appropriate responses, improving the reliability of MLLMs in real-world applications. We make our project available at https://turningpoint-ai.github.io/MOSSBench/.

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x1.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x2.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x3.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x4.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x5.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x6.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/x7.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/90.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/137.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/287.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/197.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/127.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/117.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/192.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/102.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/197.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/278.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/103.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/118.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/274.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/290.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/272.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/24.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/14.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/248.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/257.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/12.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/4.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/296.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/253.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/298.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/AMT_1.png)

![MOSSBench：探究多模态语言模型对安全查询的敏感度。](../../../paper_images/2406.17806/AMT_2.png)

[Arxiv](https://arxiv.org/abs/2406.17806)