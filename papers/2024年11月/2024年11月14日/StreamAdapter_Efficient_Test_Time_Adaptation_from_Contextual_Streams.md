# StreamAdapter：上下文流中的高效测试时适应

发布时间：2024年11月14日

`LLM应用` `语言模型` `推理优化`

> StreamAdapter: Efficient Test Time Adaptation from Contextual Streams

# 摘要

> ICL 能让大型语言模型（LLMs）直接依据给定的演示来适应新任务，无需梯度更新。尽管近期的发展扩大了上下文窗口以容纳更多演示，但此方式增加了推理成本，却未必能提升性能。为减轻这些问题，我们提出了 StreamAdapter，这是一种全新的方法，在测试时直接依据上下文更新模型参数，无需明确的上下文演示。StreamAdapter 运用上下文映射和权重吸收机制，以最少的额外参数将 ICL 演示动态转化为参数更新。由于减少了对大量上下文示例的依赖，StreamAdapter 大幅降低了推理成本，且不论演示数量多少，都能以恒定的时间复杂度实现高效推理。在不同任务和模型架构中的大量实验表明，StreamAdapter 具备与 ICL 相当甚至更优的适应能力，且所需的演示明显更少。StreamAdapter 在语言理解和生成任务上出色的任务适应及上下文编码能力，为在测试时利用上下文来适应 LLMs 提供了新视角，使得在各种场景中能更高效地适应，推理也更具成本效益。

> In-context learning (ICL) allows large language models (LLMs) to adapt to new tasks directly from the given demonstrations without requiring gradient updates. While recent advances have expanded context windows to accommodate more demonstrations, this approach increases inference costs without necessarily improving performance. To mitigate these issues, We propose StreamAdapter, a novel approach that directly updates model parameters from context at test time, eliminating the need for explicit in-context demonstrations. StreamAdapter employs context mapping and weight absorption mechanisms to dynamically transform ICL demonstrations into parameter updates with minimal additional parameters. By reducing reliance on numerous in-context examples, StreamAdapter significantly reduce inference costs and allows for efficient inference with constant time complexity, regardless of demonstration count. Extensive experiments across diverse tasks and model architectures demonstrate that StreamAdapter achieves comparable or superior adaptation capability to ICL while requiring significantly fewer demonstrations. The superior task adaptation and context encoding capabilities of StreamAdapter on both language understanding and generation tasks provides a new perspective for adapting LLMs at test time using context, allowing for more efficient adaptation across scenarios and more cost-effective inference

[Arxiv](https://arxiv.org/abs/2411.09289)