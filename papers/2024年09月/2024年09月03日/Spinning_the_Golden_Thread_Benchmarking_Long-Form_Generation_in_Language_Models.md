# 金线旋舞：语言模型长篇生成的基准测试

发布时间：2024年09月03日

`LLM应用` `创意写作` `设计提案`

> Spinning the Golden Thread: Benchmarking Long-Form Generation in Language Models

# 摘要

> 长上下文语言模型常通过“Needle-in-a-Haystack”测试评估，该测试旨在检验模型在庞大文本中识别特定信息的能力。然而，这些测试未能有效评估长篇文本生成的质量，这对设计提案和创意写作等应用至关重要。为此，我们推出了新的评估基准“Spinning the Golden Thread”，专门测试模型在长篇生成文本中识别特定事件的能力。我们让模型创作包含特定事件或约束的长篇文本，并评估其整合这些元素的能力。在多种场景和设置下，尽管模型在传统基准上表现良好，但在新基准上表现不佳，这引发了对它们生成连贯长篇文本能力的担忧。此外，随着文本长度的增加，所有模型的性能都显著下降。

> The abilities of long-context language models (LMs) are often evaluated using the "Needle-in-a-Haystack" (NIAH) test, which comprises tasks designed to assess a model's ability to identify specific information ("needle") within large text sequences ("haystack"). While these benchmarks measure how well models understand long-context input sequences, they do not effectively gauge the quality of long-form text generation--a critical aspect for applications such as design proposals and creative writing. To address this gap, we have introduced a new long-form text evaluation benchmark, Spinning the Golden Thread (SGT), which tests models' ability to identify specific events within generated long text sequences. In this benchmark, we prompt long-context LMs to create long-form text that must include particular events or constraints and evaluate their ability to incorporate these elements. We evaluated ten long-context LMs across four distinct scenarios, three types of prompt instructions, and two different generation-length settings (16K and 32K). Although these models perform well on NIAH benchmarks, none demonstrated satisfactory performance on the Spinning the Golden Thread, raising concerns about their ability to generate coherent long-form text that follows instructions. Additionally, as the length of the generated text increases, all models exhibit a significant drop in performance.

[Arxiv](https://arxiv.org/abs/2409.02076)