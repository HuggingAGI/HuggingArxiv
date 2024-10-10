# PositionID：LLMs 能精准掌控长度，轻松复制粘贴，全因拥有明确的位置感知力。

发布时间：2024年10月09日

`LLM理论` `人工智能`

> PositionID: LLMs can Control Lengths, Copy and Paste with Explicit Positional Awareness

# 摘要

> LLM 在多个领域表现出色，但在长度控制上仍有不足，常因标记级操作和训练数据限制而无法满足特定长度要求。我们发现这是由于缺乏位置意识，因此提出了 PositionID Prompting 和 PositionID Fine-Tuning 两种新方法，以增强模型在生成文本时的长度管理能力。此外，我们还引入了 PositionID CP Prompting，使 LLM 能够精准执行复制粘贴操作。为评估这些能力，我们设计了两个基准测试。实验结果显示，我们的方法不仅显著提升了长度控制的准确性，还提高了复制粘贴的精度，且不影响响应质量。

> Large Language Models (LLMs) demonstrate impressive capabilities across various domains, including role-playing, creative writing, mathematical reasoning, and coding. Despite these advancements, LLMs still encounter challenges with length control, frequently failing to adhere to specific length constraints due to their token-level operations and insufficient training on data with strict length limitations. We identify this issue as stemming from a lack of positional awareness and propose novel approaches--PositionID Prompting and PositionID Fine-Tuning--to address it. These methods enhance the model's ability to continuously monitor and manage text length during generation. Additionally, we introduce PositionID CP Prompting to enable LLMs to perform copy and paste operations accurately. Furthermore, we develop two benchmarks for evaluating length control and copy-paste abilities. Our experiments demonstrate that our methods significantly improve the model's adherence to length constraints and copy-paste accuracy without compromising response quality.

[Arxiv](https://arxiv.org/abs/2410.07035)