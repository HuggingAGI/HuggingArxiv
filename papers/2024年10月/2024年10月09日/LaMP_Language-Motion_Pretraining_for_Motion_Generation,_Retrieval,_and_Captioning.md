# LaMP：一种用于运动生成、检索和字幕的语言与运动预训练模型

发布时间：2024年10月09日

`LLM应用` `人工智能`

> LaMP: Language-Motion Pretraining for Motion Generation, Retrieval, and Captioning

# 摘要

> 语言在人类运动中至关重要。现有方法多依赖 CLIP 文本嵌入，但因 CLIP 基于静态图像-文本对预训练，难以有效对齐语言与运动。为此，我们提出 LaMP，一种新型语言-运动预训练模型，从语言-视觉过渡至更适合的语言-运动潜在空间。LaMP 通过生成富含运动信息的文本嵌入，显著提升生成运动序列的相关性与语义。借助 LaMP，我们在文本到运动生成、运动-文本检索及运动字幕生成三大任务上取得突破，均通过对齐的语言-运动表示学习实现。生成方面，我们用 LaMP 替代 CLIP 提供文本条件，并设计自回归掩码预测，避免变换器中的秩崩溃。检索方面，LaMP 的运动变换器与文本变换器交互，实现运动与文本特征的双向检索。字幕生成方面，我们用富含语言信息的运动特征微调大型语言模型，打造强大的运动字幕生成模型。此外，我们引入 LaMP-BertScore 指标，评估生成运动与文本描述的对齐度。实验结果显示，LaMP 在多个数据集上均显著优于以往方法。代码即将公开。

> Language plays a vital role in the realm of human motion. Existing methods have largely depended on CLIP text embeddings for motion generation, yet they fall short in effectively aligning language and motion due to CLIP's pretraining on static image-text pairs. This work introduces LaMP, a novel Language-Motion Pretraining model, which transitions from a language-vision to a more suitable language-motion latent space. It addresses key limitations by generating motion-informative text embeddings, significantly enhancing the relevance and semantics of generated motion sequences. With LaMP, we advance three key tasks: text-to-motion generation, motion-text retrieval, and motion captioning through aligned language-motion representation learning. For generation, we utilize LaMP to provide the text condition instead of CLIP, and an autoregressive masked prediction is designed to achieve mask modeling without rank collapse in transformers. For retrieval, motion features from LaMP's motion transformer interact with query tokens to retrieve text features from the text transformer, and vice versa. For captioning, we finetune a large language model with the language-informative motion features to develop a strong motion captioning model. In addition, we introduce the LaMP-BertScore metric to assess the alignment of generated motions with textual descriptions. Extensive experimental results on multiple datasets demonstrate substantial improvements over previous methods across all three tasks. The code of our method will be made public.

[Arxiv](https://arxiv.org/abs/2410.07093)