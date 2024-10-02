# ACE：一款全能的创造与编辑工具，通过扩散变换器精准执行指令。

发布时间：2024年09月30日

`Agent` `视觉生成` `多模态处理`

> ACE: All-round Creator and Editor Following Instructions via Diffusion Transformer

# 摘要

> 扩散模型已成为一种强大的生成技术，广泛应用于各种场景。然而，现有的大多数基础扩散模型仅支持文本引导的视觉生成，缺乏对多模态条件的支持，这在视觉编辑任务中至关重要。这种局限性使得这些模型无法像 GPT-4 在自然语言处理领域那样，成为视觉生成领域的统一模型。为此，我们提出了 ACE，一个全能的创建者和编辑器，在广泛的视觉生成任务中表现出色。我们首先引入了长上下文条件单元 (LCU)，并基于此构建了一个 Transformer 扩散模型，旨在联合训练多种生成和编辑任务。此外，我们还提出了一种高效的数据收集方法，通过合成或聚类获取成对图像，并利用多模态大语言模型提供准确的文本指令。为了全面评估模型性能，我们建立了一个包含多种视觉生成任务的手动注释数据基准。实验结果表明，我们的模型在视觉生成领域具有显著优势。得益于其全能特性，我们可以轻松构建一个多模态聊天系统，使用单一模型响应图像创建请求，避免了传统视觉代理的复杂流程。代码和模型将在项目页面上提供：https://ali-vilab.github.io/ace-page/。

> Diffusion models have emerged as a powerful generative technology and have been found to be applicable in various scenarios. Most existing foundational diffusion models are primarily designed for text-guided visual generation and do not support multi-modal conditions, which are essential for many visual editing tasks. This limitation prevents these foundational diffusion models from serving as a unified model in the field of visual generation, like GPT-4 in the natural language processing field. In this work, we propose ACE, an All-round Creator and Editor, which achieves comparable performance compared to those expert models in a wide range of visual generation tasks. To achieve this goal, we first introduce a unified condition format termed Long-context Condition Unit (LCU), and propose a novel Transformer-based diffusion model that uses LCU as input, aiming for joint training across various generation and editing tasks. Furthermore, we propose an efficient data collection approach to address the issue of the absence of available training data. It involves acquiring pairwise images with synthesis-based or clustering-based pipelines and supplying these pairs with accurate textual instructions by leveraging a fine-tuned multi-modal large language model. To comprehensively evaluate the performance of our model, we establish a benchmark of manually annotated pairs data across a variety of visual generation tasks. The extensive experimental results demonstrate the superiority of our model in visual generation fields. Thanks to the all-in-one capabilities of our model, we can easily build a multi-modal chat system that responds to any interactive request for image creation using a single model to serve as the backend, avoiding the cumbersome pipeline typically employed in visual agents. Code and models will be available on the project page: https://ali-vilab.github.io/ace-page/.

[Arxiv](https://arxiv.org/abs/2410.00086)