# VideoGPT+：融合图像与视频编码，提升视频理解深度

发布时间：2024年06月13日

`LLM应用

这篇论文介绍了VideoGPT+，一个结合了图像编码器和视频编码器的优势来处理视频理解问题的大型多模态模型。它通过自适应池化技术和半自动标注系统提升了模型性能，并在多个视频基准测试中取得了优异的表现。此外，论文还推出了一个新的基准VCGBench-Diverse，用于全面评估视频LMMs的能力。这些内容主要关注于LLM在视频理解领域的应用，因此归类为LLM应用。` `视频理解` `多模态学习`

> VideoGPT+: Integrating Image and Video Encoders for Enhanced Video Understanding

# 摘要

> 随着语言模型技术的进步，大型多模态模型（LMMs）在视频理解领域取得了重大进展。尽管这些模型采用了先进的大型语言模型（LLMs），但它们在处理视觉信息时依赖于图像或视频编码器，各有其局限。图像编码器虽能捕捉帧序列中的丰富空间细节，却缺乏关键的时间上下文，这在动作复杂的视频中尤为重要。相反，视频编码器虽能提供时间背景，但常因计算限制而只能处理低分辨率的稀疏帧，影响了对视频的全面理解。为此，我们推出了VideoGPT+，它巧妙结合了图像编码器的精细空间解析能力和视频编码器的全局时间建模能力。通过将视频分割并采用自适应池化技术，我们的模型在多个视频基准测试中表现出色，包括VCGBench、MVBench和零-shot问答。此外，我们还开发了一套包含112K视频指令的半自动标注系统，进一步提升了模型性能。为了全面评估视频LMMs，我们推出了VCGBench-Diverse，这是一个包含18种视频类别和4,354个问答对的基准，旨在评估模型在密集视频字幕、时空理解及复杂推理上的泛化能力，确保对各类视频及其动态的全面评估。代码已公开：https://github.com/mbzuai-oryx/VideoGPT-plus。

> Building on the advances of language models, Large Multimodal Models (LMMs) have contributed significant improvements in video understanding. While the current video LMMs utilize advanced Large Language Models (LLMs), they rely on either image or video encoders to process visual inputs, each of which has its own limitations. Image encoders excel at capturing rich spatial details from frame sequences but lack explicit temporal context, which can be important in videos with intricate action sequences. On the other hand, video encoders provide temporal context but are often limited by computational constraints that lead to processing only sparse frames at lower resolutions, resulting in reduced contextual and spatial understanding. To this end, we introduce VideoGPT+, which combines the complementary benefits of the image encoder (for detailed spatial understanding) and the video encoder (for global temporal context modeling). The model processes videos by dividing them into smaller segments and applies an adaptive pooling strategy on features extracted by both image and video encoders. Our architecture showcases improved performance across multiple video benchmarks, including VCGBench, MVBench and Zero-shot question-answering. Further, we develop 112K video-instruction set using a novel semi-automatic annotation pipeline which further improves the model performance. Additionally, to comprehensively evaluate video LMMs, we present VCGBench-Diverse, covering 18 broad video categories such as lifestyle, sports, science, gaming, and surveillance videos. This benchmark with 4,354 question-answer pairs evaluates the generalization of existing LMMs on dense video captioning, spatial and temporal understanding, and complex reasoning, ensuring comprehensive assessment across diverse video types and dynamics. Code: https://github.com/mbzuai-oryx/VideoGPT-plus.

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/vcg+_intro_radar_plot.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/vcg+_block_diagram_v6.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/snowflake.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/red_fire.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/blue_fire.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/vcg120k_block_diagram_v0.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/vcgbench_block_diag_v6.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/demo_vcg+_main.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/demo_vcg+_full_part1.jpg)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/demo_vcg+_full_part2.jpg)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/promtp_1_data.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/promtp_2_data.png)

![VideoGPT+：融合图像与视频编码，提升视频理解深度](../../../paper_images/2406.09418/promtp_3_bench.png)

[Arxiv](https://arxiv.org/abs/2406.09418)