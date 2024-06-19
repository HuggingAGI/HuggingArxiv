# Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界

发布时间：2024年06月17日

`Agent

理由：这篇论文介绍了一个名为Holmes-VAD的框架，该框架通过精细的时间监督和多模态指令来实现视频异常的精准定位与详尽解释。这个框架可以被视为一个Agent，因为它能够接收多模态输入（视频和语言指令），并执行特定的任务（视频异常检测）。此外，它还具有解释性，能够提供异常检测的详细解释，这进一步强化了其作为Agent的特性。虽然该框架使用了大型语言模型，但其主要贡献在于开发了一个能够处理多模态数据并执行特定任务的系统，因此更适合归类为Agent。` `视频监控` `异常检测`

> Holmes-VAD: Towards Unbiased and Explainable Video Anomaly Detection via Multi-modal LLM

# 摘要

> 在视频异常检测（VAD）的开放领域中，现有方法在处理未知或复杂事件时往往检测有偏，且缺乏透明度。为此，我们推出了Holmes-VAD框架，它通过精细的时间监督和多模态指令，实现了异常的精准定位与详尽解释。我们首先建立了首个大规模多模态VAD指令调整基准——VAD-Instruct50k，采用半自动标注方法，结合强大的视频描述器和大型语言模型，为视频片段提供高质量的异常分析。基于此，我们开发了一套定制方案，通过训练轻量级时间采样器和微调多模态大型语言模型，实现视频异常的可解释检测。实验证明，Holmes-VAD不仅通用性强，而且解释性佳，成为视频异常分析的新锐技术。我们将在https://github.com/pipixin321/HolmesVAD公开分享我们的基准和模型，以促进社区发展。

> Towards open-ended Video Anomaly Detection (VAD), existing methods often exhibit biased detection when faced with challenging or unseen events and lack interpretability. To address these drawbacks, we propose Holmes-VAD, a novel framework that leverages precise temporal supervision and rich multimodal instructions to enable accurate anomaly localization and comprehensive explanations. Firstly, towards unbiased and explainable VAD system, we construct the first large-scale multimodal VAD instruction-tuning benchmark, i.e., VAD-Instruct50k. This dataset is created using a carefully designed semi-automatic labeling paradigm. Efficient single-frame annotations are applied to the collected untrimmed videos, which are then synthesized into high-quality analyses of both abnormal and normal video clips using a robust off-the-shelf video captioner and a large language model (LLM). Building upon the VAD-Instruct50k dataset, we develop a customized solution for interpretable video anomaly detection. We train a lightweight temporal sampler to select frames with high anomaly response and fine-tune a multimodal large language model (LLM) to generate explanatory content. Extensive experimental results validate the generality and interpretability of the proposed Holmes-VAD, establishing it as a novel interpretable technique for real-world video anomaly analysis. To support the community, our benchmark and model will be publicly available at https://github.com/pipixin321/HolmesVAD.

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x1.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x2.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x3.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x4.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/fig_interface.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x5.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x6.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/fig_human_eval_interface.png)

![Holmes-VAD：借助多模态LLM，迈向无偏见且透明的视频异常检测新境界](../../../paper_images/2406.12235/x7.png)

[Arxiv](https://arxiv.org/abs/2406.12235)