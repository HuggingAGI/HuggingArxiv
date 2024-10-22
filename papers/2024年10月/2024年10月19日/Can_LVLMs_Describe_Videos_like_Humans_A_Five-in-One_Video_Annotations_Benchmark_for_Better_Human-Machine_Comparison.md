# LVLMs 能否像人类一样描述视频？我们推出一个五合一的视频注释基准，旨在提升人机比较的准确性。

发布时间：2024年10月19日

`LLM应用` `视频处理` `人工智能`

> Can LVLMs Describe Videos like Humans? A Five-in-One Video Annotations Benchmark for Better Human-Machine Comparison

# 摘要

> 大型视觉语言模型 (LVLMs) 在处理复杂视频任务方面取得了显著进展，引发了研究人员对其类人多模态理解能力的关注。视频描述作为评估视频理解的基本任务，需要对时空动态的深刻理解，这对人类和机器都构成挑战。因此，研究 LVLMs 是否能像人类一样全面描述视频（通过视频字幕进行合理的人机比较）将深化我们对这些模型的理解和应用。然而，当前的视频理解基准存在显著局限，如视频时长短、注释简短且依赖单一视角。这些局限阻碍了对 LVLMs 理解复杂长视频能力的全面评估，并影响了建立准确反映人类视频理解能力的基线。为此，我们提出了新的基准 FIOVA (Five In One Video Annotations)，旨在更全面地评估 LVLMs 与人类理解之间的差异。FIOVA 包含 3,002 个长视频序列（平均 33.6 秒），涵盖多样化场景，每个视频由五名不同注释者进行注释，生成比现有基准长 4-15 倍的字幕，首次在视频描述任务中建立了全面代表人类理解的强大基线。我们使用 FIOVA 基准对六种最先进的 LVLMs 进行了深入评估，并比较了它们与人类的性能。更多详情请访问 https://huuuuusy.github.io/fiova/。

> Large vision-language models (LVLMs) have made significant strides in addressing complex video tasks, sparking researchers' interest in their human-like multimodal understanding capabilities. Video description serves as a fundamental task for evaluating video comprehension, necessitating a deep understanding of spatial and temporal dynamics, which presents challenges for both humans and machines. Thus, investigating whether LVLMs can describe videos as comprehensively as humans (through reasonable human-machine comparisons using video captioning as a proxy task) will enhance our understanding and application of these models. However, current benchmarks for video comprehension have notable limitations, including short video durations, brief annotations, and reliance on a single annotator's perspective. These factors hinder a comprehensive assessment of LVLMs' ability to understand complex, lengthy videos and prevent the establishment of a robust human baseline that accurately reflects human video comprehension capabilities. To address these issues, we propose a novel benchmark, FIOVA (Five In One Video Annotations), designed to evaluate the differences between LVLMs and human understanding more comprehensively. FIOVA includes 3,002 long video sequences (averaging 33.6 seconds) that cover diverse scenarios with complex spatiotemporal relationships. Each video is annotated by five distinct annotators, capturing a wide range of perspectives and resulting in captions that are 4-15 times longer than existing benchmarks, thereby establishing a robust baseline that represents human understanding comprehensively for the first time in video description tasks. Using the FIOVA benchmark, we conducted an in-depth evaluation of six state-of-the-art LVLMs, comparing their performance with humans. More detailed information can be found at https://huuuuusy.github.io/fiova/.

[Arxiv](https://arxiv.org/abs/2410.15270)