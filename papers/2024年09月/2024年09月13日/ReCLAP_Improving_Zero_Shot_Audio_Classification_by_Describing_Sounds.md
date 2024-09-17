# ReCLAP：用声音描述提升零-shot 音频分类

发布时间：2024年09月13日

`LLM应用` `音频处理` `机器学习`

> ReCLAP: Improving Zero Shot Audio Classification by Describing Sounds

# 摘要

> 开放词汇的音频-语言模型 CLAP 为零-shot 音频分类 (ZSAC) 提供了一种有前景的方法。本文提出了一种简单有效的方法来改进 ZSAC。我们不再使用抽象类别标签的提示（如“风琴的声音”），而是使用描述声音固有特征的多样化提示（如“风琴的深沉和共鸣的音调充满了大教堂”）。为此，我们提出了 ReCLAP 模型，通过重写音频字幕来提高对野外声音的理解。ReCLAP 在多模态音频-文本检索和 ZSAC 上均优于所有基线。为了进一步提升 ReCLAP 的 ZSAC 性能，我们提出了提示增强，为每个标签生成自定义提示，描述声音事件并在多样化场景中使用。这种方法使 ReCLAP 在 ZSAC 上的性能提高了 1%-18%，并使所有基线的性能提高了 1%-55%。

> Open-vocabulary audio-language models, like CLAP, offer a promising approach for zero-shot audio classification (ZSAC) by enabling classification with any arbitrary set of categories specified with natural language prompts. In this paper, we propose a simple but effective method to improve ZSAC with CLAP. Specifically, we shift from the conventional method of using prompts with abstract category labels (e.g., Sound of an organ) to prompts that describe sounds using their inherent descriptive features in a diverse context (e.g.,The organ's deep and resonant tones filled the cathedral.). To achieve this, we first propose ReCLAP, a CLAP model trained with rewritten audio captions for improved understanding of sounds in the wild. These rewritten captions describe each sound event in the original caption using their unique discriminative characteristics. ReCLAP outperforms all baselines on both multi-modal audio-text retrieval and ZSAC. Next, to improve zero-shot audio classification with ReCLAP, we propose prompt augmentation. In contrast to the traditional method of employing hand-written template prompts, we generate custom prompts for each unique label in the dataset. These custom prompts first describe the sound event in the label and then employ them in diverse scenes. Our proposed method improves ReCLAP's performance on ZSAC by 1%-18% and outperforms all baselines by 1% - 55%.

[Arxiv](https://arxiv.org/abs/2409.09213)