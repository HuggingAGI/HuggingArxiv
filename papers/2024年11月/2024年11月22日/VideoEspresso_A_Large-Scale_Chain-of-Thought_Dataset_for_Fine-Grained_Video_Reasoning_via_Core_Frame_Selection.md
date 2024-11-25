# VideoEspresso：一个用于通过核心帧选择进行细粒度视频推理的大规模思维链数据集

发布时间：2024年11月22日

`LLM应用` `多模态`

> VideoEspresso: A Large-Scale Chain-of-Thought Dataset for Fine-Grained Video Reasoning via Core Frame Selection

# 摘要

> 大型视觉语言模型（LVLMs）的发展极大地提升了多模态理解水平，然而在视频推理任务中，由于高质量大规模数据集的匮乏，仍存在诸多挑战。现有的视频问答（VideoQA）数据集，要么依赖高成本且粒度欠佳的手动标注，要么采用存在冗余的逐帧自动分析构建方法，这限制了其可扩展性和处理复杂推理的有效性。为应对这些难题，我们推出了 VideoEspresso 这一新数据集，它具备保留重要空间细节和时间连贯性的 VideoQA 对，以及中间推理步骤的多模态标注。我们的构建流程采用语义感知手段降低冗余，接着利用 GPT-4o 生成 QA 对。我们还开发了视频思维链（CoT）标注来充实推理过程，引导 GPT-4o 从 QA 对和视频内容中提取逻辑关系。为充分发挥高质量 VideoQA 对的潜力，我们提出了一个混合 LVLMs 协作框架，包含一个帧选择器和一个两阶段指令微调推理 LVLM。此框架能自适应选取核心帧，并运用多模态证据进行思维链推理。在我们所提出的涵盖 14 个任务、针对 9 个热门 LVLMs 的基准上进行评估，我们的方法在多数任务中超越现有基线，展现出出色的视频推理能力。我们的代码和数据集将在：https://github.com/hshjerry/VideoEspresso 发布。

> The advancement of Large Vision Language Models (LVLMs) has significantly improved multimodal understanding, yet challenges remain in video reasoning tasks due to the scarcity of high-quality, large-scale datasets. Existing video question-answering (VideoQA) datasets often rely on costly manual annotations with insufficient granularity or automatic construction methods with redundant frame-by-frame analysis, limiting their scalability and effectiveness for complex reasoning. To address these challenges, we introduce VideoEspresso, a novel dataset that features VideoQA pairs preserving essential spatial details and temporal coherence, along with multimodal annotations of intermediate reasoning steps. Our construction pipeline employs a semantic-aware method to reduce redundancy, followed by generating QA pairs using GPT-4o. We further develop video Chain-of-Thought (CoT) annotations to enrich reasoning processes, guiding GPT-4o in extracting logical relationships from QA pairs and video content. To exploit the potential of high-quality VideoQA pairs, we propose a Hybrid LVLMs Collaboration framework, featuring a Frame Selector and a two-stage instruction fine-tuned reasoning LVLM. This framework adaptively selects core frames and performs CoT reasoning using multimodal evidence. Evaluated on our proposed benchmark with 14 tasks against 9 popular LVLMs, our method outperforms existing baselines on most tasks, demonstrating superior video reasoning capabilities. Our code and dataset will be released at: https://github.com/hshjerry/VideoEspresso

[Arxiv](https://arxiv.org/abs/2411.14794)