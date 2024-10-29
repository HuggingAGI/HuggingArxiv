# DeTeCtive：通过多层次对比学习检测人工智能生成的文本

发布时间：2024年10月28日

`LLM应用` `人工智能` `文本检测`

> DeTeCtive: Detecting AI-generated Text via Multi-Level Contrastive Learning

# 摘要

> 当前用于检测人工智能生成文本的技术在很大程度上局限于手动特征制作和有监督的二分类范式。这些方法通常导致性能瓶颈和不理想的泛化能力。因此，这些方法通常不适用于分布外（OOD）数据和新出现的大型语言模型（LLM）。在本文中，我们重新审视了人工智能生成文本检测的任务。我们认为完成这项任务的关键在于区分不同作者的写作风格，而不是简单地将文本分类为人写的或人工智能生成的文本。为此，我们提出了 DeTeCtive，一个多任务辅助、多层次对比学习框架。DeTeCtive 旨在促进不同写作风格的学习，并结合了一个密集的信息检索管道用于人工智能生成文本检测。我们的方法与一系列文本编码器兼容。大量实验表明，我们的方法在多个基准上提高了各种文本编码器检测人工智能生成文本的能力，并取得了最先进的结果。值得注意的是，在 OOD 零样本评估中，我们的方法大大优于现有方法。此外，我们发现我们的方法对 OOD 数据具有无训练增量适应（TFIA）能力，进一步提高了其在 OOD 检测场景中的效果。我们将开源我们的代码和模型，希望我们的工作能在人工智能生成文本检测领域引发新的思考，确保 LLM 的安全应用和提高合规性。我们的代码可在 https://github.com/heyongxin233/DeTeCtive 获得。

> Current techniques for detecting AI-generated text are largely confined to manual feature crafting and supervised binary classification paradigms. These methodologies typically lead to performance bottlenecks and unsatisfactory generalizability. Consequently, these methods are often inapplicable for out-of-distribution (OOD) data and newly emerged large language models (LLMs). In this paper, we revisit the task of AI-generated text detection. We argue that the key to accomplishing this task lies in distinguishing writing styles of different authors, rather than simply classifying the text into human-written or AI-generated text. To this end, we propose DeTeCtive, a multi-task auxiliary, multi-level contrastive learning framework. DeTeCtive is designed to facilitate the learning of distinct writing styles, combined with a dense information retrieval pipeline for AI-generated text detection. Our method is compatible with a range of text encoders. Extensive experiments demonstrate that our method enhances the ability of various text encoders in detecting AI-generated text across multiple benchmarks and achieves state-of-the-art results. Notably, in OOD zero-shot evaluation, our method outperforms existing approaches by a large margin. Moreover, we find our method boasts a Training-Free Incremental Adaptation (TFIA) capability towards OOD data, further enhancing its efficacy in OOD detection scenarios. We will open-source our code and models in hopes that our work will spark new thoughts in the field of AI-generated text detection, ensuring safe application of LLMs and enhancing compliance. Our code is available at https://github.com/heyongxin233/DeTeCtive.

[Arxiv](https://arxiv.org/abs/2410.20964)