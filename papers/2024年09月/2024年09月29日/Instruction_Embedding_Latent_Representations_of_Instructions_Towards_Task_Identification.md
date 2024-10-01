# 指令嵌入：揭示任务识别的潜在指令表示

发布时间：2024年09月29日

`LLM理论` `人工智能`

> Instruction Embedding: Latent Representations of Instructions Towards Task Identification

# 摘要

> 指令数据是提升大型语言模型（LLM）达到人类水平表现的关键。LIMA 研究指出，对齐过程实质上是模型根据指令调整交互方式或格式，以利用预训练知识解决多样化任务。因此，指令数据的核心在于其所代表的任务，而非具体的语义或知识细节。指令的潜在表示在数据选择和演示检索等任务中发挥作用，但这些表示多源自文本嵌入，涵盖了影响任务类别识别的整体语义信息。为此，我们提出了“指令嵌入”这一新概念，并构建了指令嵌入基准（IEB）以供训练和评估。同时，我们设计了基于提示的指令嵌入（PIE）方法，使模型更专注于任务本身。在 IEB 上的评估结果显示，PIE 在准确识别任务类别方面表现优异。此外，指令嵌入在四个下游任务中的应用进一步证明了其在指令相关任务中的高效性和适用性。

> Instruction data is crucial for improving the capability of Large Language Models (LLMs) to align with human-level performance. Recent research LIMA demonstrates that alignment is essentially a process where the model adapts instructions' interaction style or format to solve various tasks, leveraging pre-trained knowledge and skills. Therefore, for instructional data, the most important aspect is the task it represents, rather than the specific semantics and knowledge information. The latent representations of instructions play roles for some instruction-related tasks like data selection and demonstrations retrieval. However, they are always derived from text embeddings, encompass overall semantic information that influences the representation of task categories. In this work, we introduce a new concept, instruction embedding, and construct Instruction Embedding Benchmark (IEB) for its training and evaluation. Then, we propose a baseline Prompt-based Instruction Embedding (PIE) method to make the representations more attention on tasks. The evaluation of PIE, alongside other embedding methods on IEB with two designed tasks, demonstrates its superior performance in accurately identifying task categories. Moreover, the application of instruction embeddings in four downstream tasks showcases its effectiveness and suitability for instruction-related tasks.

[Arxiv](https://arxiv.org/abs/2409.19680)