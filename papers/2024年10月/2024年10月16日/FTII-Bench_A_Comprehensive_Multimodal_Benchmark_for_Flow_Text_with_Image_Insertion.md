# FTII-Bench：一款全面的多模态基准，专为插入图像的流文本设计

发布时间：2024年10月16日

`LLM应用`

> FTII-Bench: A Comprehensive Multimodal Benchmark for Flow Text with Image Insertion

# 摘要

> 随着大型语言模型（LLMs）和基础视觉模型的突破，大型视觉-语言模型（LVLMs）也取得了长足进步。然而，现有基准测试仅评估LVLMs的单一能力，未能充分展现其在复杂场景中的潜力。为此，我们提出了更具挑战性的“流动文本与图像插入任务”（FTII），要求模型同时具备图像理解、指令解读和长文本分析能力。具体而言，模型需在文本段落累积过程中，从候选图像中挑选最合适的插入相应段落。构建FTII基准测试极具挑战，特别是在处理文本与图像的流动顺序时。我们借鉴专业新闻报道，因其自然包含图像与文本的最佳组合，从而创建了FTII-Bench，包含318篇中文和307篇英文高质量新闻文章，覆盖10个新闻领域。我们设计了两种类型、多难度级别的问题，并基于CLIP模型和现有LVLMs建立了两套评估流程，测试了9个开源和2个闭源LVLMs及2个CLIP模型。结果显示，即便是顶尖模型如GPT-4o，在FTII任务中也面临显著挑战。

> Benefiting from the revolutionary advances in large language models (LLMs) and foundational vision models, large vision-language models (LVLMs) have also made significant progress. However, current benchmarks focus on tasks that evaluating only a single aspect of LVLM capabilities (e.g., recognition, detection, understanding). These tasks fail to fully demonstrate LVLMs' potential in complex application scenarios. To comprehensively assess the performance of existing LVLMs, we propose a more challenging task called the Flow Text with Image Insertion task (FTII). This task requires LVLMs to simultaneously possess outstanding abilities in image comprehension, instruction understanding, and long-text interpretation. Specifically, given several text paragraphs and a set of candidate images, as the text paragraphs accumulate, the LVLMs are required to select the most suitable image from the candidates to insert after the corresponding paragraph. Constructing a benchmark for such a task is highly challenging, particularly in determining the sequence of flowing text and images. To address this challenge, we turn to professional news reports, which naturally contain a gold standard for image-text sequences. Based on this, we introduce the Flow Text with Image Insertion Benchmark (FTII-Bench), which includes 318 high-quality Chinese image-text news articles and 307 high-quality English image-text news articles, covering 10 different news domains. Using these 625 high-quality articles, we construct problems of two different types with multiple levels of difficulty. Furthermore, we establish two different evaluation pipelines based on the CLIP model and existing LVLMs. We evaluate 9 open-source and 2 closed-source LVLMs as well as 2 CLIP-based models. Results indicate that even the most advanced models (e.g., GPT-4o) face significant challenges when tackling the FTII task.

[Arxiv](https://arxiv.org/abs/2410.12564)