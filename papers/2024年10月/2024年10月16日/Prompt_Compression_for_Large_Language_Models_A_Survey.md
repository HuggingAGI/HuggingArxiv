# 大型语言模型的提示压缩：全面调查

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Prompt Compression for Large Language Models: A Survey

# 摘要

> 在处理复杂自然语言任务时，大型语言模型 (LLM) 通常需要冗长的提示，这不仅增加了内存负担，还提高了推理成本。为应对这一挑战，提示压缩技术应运而生，并迅速成为研究热点。本文将提示压缩技术分为硬提示和软提示两大类，逐一比较其技术路径，并深入探讨了其背后的机制，如注意力优化、参数高效微调 (PEFT)、模态融合及新合成语言的应用。此外，我们还分析了这些技术在实际应用中的表现及局限，并展望了未来的发展方向，包括优化压缩编码器、融合硬软提示方法及借鉴多模态的智慧。

> Leveraging large language models (LLMs) for complex natural language tasks typically requires long-form prompts to convey detailed requirements and information, which results in increased memory usage and inference costs. To mitigate these challenges, multiple efficient methods have been proposed, with prompt compression gaining significant research interest. This survey provides an overview of prompt compression techniques, categorized into hard prompt methods and soft prompt methods. First, the technical approaches of these methods are compared, followed by an exploration of various ways to understand their mechanisms, including the perspectives of attention optimization, Parameter-Efficient Fine-Tuning (PEFT), modality fusion, and new synthetic language. We also examine the downstream adaptations of various prompt compression techniques. Finally, the limitations of current prompt compression methods are analyzed, and several future directions are outlined, such as optimizing the compression encoder, combining hard and soft prompts methods, and leveraging insights from multimodality.

[Arxiv](https://arxiv.org/abs/2410.12388)