# DesignProbe：为多模态大型语言模型量身打造的图形设计基准测试工具

发布时间：2024年04月23日

`分类：LLM应用` `平面设计` `人工智能`

> DesignProbe: A Graphic Design Benchmark for Multimodal Large Language Models

# 摘要

> 精心制作的平面设计在细节（如色彩、字体、版式）与整体设计之间达到和谐统一。这种设计的复杂性让人难以捉摸，因为它既需要识别设计元素，又需要深入理解设计本身。随着多模态大型语言模型（MLLMs）的迅猛发展，我们创建了DesignProbe基准测试，旨在探究MLLMs在设计领域的能力。该基准测试涵盖八个任务，覆盖了从设计元素的细节到整体设计的宏观视角。在元素层面，我们既关注属性识别也关注语义理解；在整体层面，我们探讨了风格和隐喻。我们对9个MLLMs进行了测试，并使用GPT-4作为评估工具。此外，进一步的实验发现，精心设计提示语可以显著提升MLLMs的性能。我们通过不同LLMs重构提示语，发现自我优化的LLMs性能提升更为显著。我们还尝试了两种添加额外任务知识的方法——文本描述和图像示例，结果表明图像示例对性能的提升远超过文本描述。

> A well-executed graphic design typically achieves harmony in two levels, from the fine-grained design elements (color, font and layout) to the overall design. This complexity makes the comprehension of graphic design challenging, for it needs the capability to both recognize the design elements and understand the design. With the rapid development of Multimodal Large Language Models (MLLMs), we establish the DesignProbe, a benchmark to investigate the capability of MLLMs in design. Our benchmark includes eight tasks in total, across both the fine-grained element level and the overall design level. At design element level, we consider both the attribute recognition and semantic understanding tasks. At overall design level, we include style and metaphor. 9 MLLMs are tested and we apply GPT-4 as evaluator. Besides, further experiments indicates that refining prompts can enhance the performance of MLLMs. We first rewrite the prompts by different LLMs and found increased performances appear in those who self-refined by their own LLMs. We then add extra task knowledge in two different ways (text descriptions and image examples), finding that adding images boost much more performance over texts.

[Arxiv](https://arxiv.org/abs/2404.14801)