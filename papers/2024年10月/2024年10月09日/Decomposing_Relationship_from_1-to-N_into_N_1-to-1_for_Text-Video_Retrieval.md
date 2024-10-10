# 将复杂的 1-to-N 关系拆解为 N 个简单的 1-to-1 关系，以优化文本与视频的匹配检索。

发布时间：2024年10月09日

`LLM应用` `视频检索` `多媒体`

> Decomposing Relationship from 1-to-N into N 1-to-1 for Text-Video Retrieval

# 摘要

> 近年来，文本-视频检索 (TVR) 因预训练模型和大型语言模型 (LLM) 的应用而取得显著进展。然而，由于视频与文本模态间的固有差异及数据表示的不规则性，实现精准匹配仍具挑战。为此，我们提出 Text-Video-ProxyNet (TV-ProxyNet)，一种将传统 1-to-N 关系分解为 N 个 1-to-1 关系的新框架。通过一系列文本代理替代单一查询，TV-ProxyNet 不仅拓宽了查询范围，还实现了更精准的扩展。每个代理经由精细迭代过程生成，由“导演”和“冲刺”机制调控其方向与距离。此设计不仅提升了语义对齐精度，还有效管理了多模态数据的差异与噪声。实验表明，TV-ProxyNet 在 MSRVTT、DiDeMo 和 ActivityNet Captions 基准上，R@1 提升 2.0% 至 3.3%，并在 MSRVTT 和 ActivityNet Captions 上达到最先进水平，DiDeMo 上提升 2.0%，验证了其在增强语义映射与减少错误方面的卓越能力。

> Text-video retrieval (TVR) has seen substantial advancements in recent years, fueled by the utilization of pre-trained models and large language models (LLMs). Despite these advancements, achieving accurate matching in TVR remains challenging due to inherent disparities between video and textual modalities and irregularities in data representation. In this paper, we propose Text-Video-ProxyNet (TV-ProxyNet), a novel framework designed to decompose the conventional 1-to-N relationship of TVR into N distinct 1-to-1 relationships. By replacing a single text query with a series of text proxies, TV-ProxyNet not only broadens the query scope but also achieves a more precise expansion. Each text proxy is crafted through a refined iterative process, controlled by mechanisms we term as the director and dash, which regulate the proxy's direction and distance relative to the original text query. This setup not only facilitates more precise semantic alignment but also effectively manages the disparities and noise inherent in multimodal data. Our experiments on three representative video-text retrieval benchmarks, MSRVTT, DiDeMo, and ActivityNet Captions, demonstrate the effectiveness of TV-ProxyNet. The results show an improvement of 2.0% to 3.3% in R@1 over the baseline. TV-ProxyNet achieved state-of-the-art performance on MSRVTT and ActivityNet Captions, and a 2.0% improvement on DiDeMo compared to existing methods, validating our approach's ability to enhance semantic mapping and reduce error propensity.

[Arxiv](https://arxiv.org/abs/2410.06618)