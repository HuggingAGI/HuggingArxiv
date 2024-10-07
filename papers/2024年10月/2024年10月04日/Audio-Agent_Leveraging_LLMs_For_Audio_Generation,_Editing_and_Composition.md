# Audio-Agent：借助 LLMs 实现音频的生成、编辑与合成

发布时间：2024年10月04日

`Agent` `音频处理` `多媒体`

> Audio-Agent: Leveraging LLMs For Audio Generation, Editing and Composition

# 摘要

> 我们推出了 Audio-Agent，一个基于文本或视频的多模态框架，专为音频生成、编辑和合成设计。传统 TTA 方法虽直接，但在复杂文本条件下难以生成高质量音频。我们的方法中，预训练的 TTA 扩散网络与 GPT-4 协同，将文本分解为具体指令，生成高质量音频，且支持可变长度。对于 VTA 任务，现有方法需训练时间戳检测器，过程繁琐耗时。我们通过微调 LLM 获取语义和时间条件，简化了这一过程。因此，我们的框架为 TTA 和 VTA 任务提供了高效解决方案，无需大量计算开销。

> We introduce Audio-Agent, a multimodal framework for audio generation, editing and composition based on text or video inputs. Conventional approaches for text-to-audio (TTA) tasks often make single-pass inferences from text descriptions. While straightforward, this design struggles to produce high-quality audio when given complex text conditions. In our method, we utilize a pre-trained TTA diffusion network as the audio generation agent to work in tandem with GPT-4, which decomposes the text condition into atomic, specific instructions, and calls the agent for audio generation. Consequently, Audio-Agent generates high-quality audio that is closely aligned with the provided text or video while also supporting variable-length generation. For video-to-audio (VTA) tasks, most existing methods require training a timestamp detector to synchronize video events with generated audio, a process that can be tedious and time-consuming. We propose a simpler approach by fine-tuning a pre-trained Large Language Model (LLM), e.g., Gemma2-2B-it, to obtain both semantic and temporal conditions to bridge video and audio modality. Thus our framework provides a comprehensive solution for both TTA and VTA tasks without substantial computational overhead in training.

[Arxiv](https://arxiv.org/abs/2410.03335)