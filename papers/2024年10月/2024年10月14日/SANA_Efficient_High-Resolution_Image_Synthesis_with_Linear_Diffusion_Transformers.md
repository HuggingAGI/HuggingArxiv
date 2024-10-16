# SANA：通过线性扩散变换器，实现高效的高分辨率图像合成

发布时间：2024年10月14日

`LLM应用` `内容创作` `图像生成`

> SANA: Efficient High-Resolution Image Synthesis with Linear Diffusion Transformers

# 摘要

> 摘要：我们推出 Sana，一个能生成高达 4096×4096 分辨率图像的文本到图像框架。Sana 以惊人速度合成高分辨率、高质量图像，且文本与图像对齐紧密，可在笔记本电脑 GPU 上运行。核心设计包括：(1) 深度压缩自动编码器，压缩图像达 32 倍，大幅减少潜在标记。(2) 线性 DiT，以线性注意力替代普通注意力，高分辨率下更高效。(3) 仅解码器文本编码器，用现代小型 LLM 替代 T5，并设计复杂指令增强图像-文本对齐。(4) 高效训练与采样，提出 Flow-DPM-Solver 减少采样步骤，加速收敛。Sana-0.6B 体积小 20 倍，速度快 100 倍以上，能在 16GB 笔记本电脑 GPU 上生成 1024×1024 图像仅需不到 1 秒。Sana 让内容创作更经济实惠。代码与模型即将公开。

> 
Abstract:We introduce Sana, a text-to-image framework that can efficiently generate images up to 4096$\times$4096 resolution. Sana can synthesize high-resolution, high-quality images with strong text-image alignment at a remarkably fast speed, deployable on laptop GPU. Core designs include: (1) Deep compression autoencoder: unlike traditional AEs, which compress images only 8$\times$, we trained an AE that can compress images 32$\times$, effectively reducing the number of latent tokens. (2) Linear DiT: we replace all vanilla attention in DiT with linear attention, which is more efficient at high resolutions without sacrificing quality. (3) Decoder-only text encoder: we replaced T5 with modern decoder-only small LLM as the text encoder and designed complex human instruction with in-context learning to enhance the image-text alignment. (4) Efficient training and sampling: we propose Flow-DPM-Solver to reduce sampling steps, with efficient caption labeling and selection to accelerate convergence. As a result, Sana-0.6B is very competitive with modern giant diffusion model (e.g. Flux-12B), being 20 times smaller and 100+ times faster in measured throughput. Moreover, Sana-0.6B can be deployed on a 16GB laptop GPU, taking less than 1 second to generate a 1024$\times$1024 resolution image. Sana enables content creation at low cost. Code and model will be publicly released.
    

[Arxiv](https://arxiv.org/pdf/2410.10629)