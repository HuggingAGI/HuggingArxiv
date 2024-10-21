# PTR：专为轨迹恢复而生的预训练语言模型

发布时间：2024年10月18日

`LLM应用` `物联网`

> PTR: A Pre-trained Language Model for Trajectory Recovery

# 摘要

> 时空轨迹数据对物联网服务至关重要，但服务中断和网络不稳定常导致轨迹记录稀疏，丢失了详细移动数据。恢复这些轨迹变得至关重要。尽管有所进展，但仍面临挑战：缺乏大规模密集数据、难以泛化不同采样间隔的稀疏轨迹、未充分考虑外部因素。为此，我们提出PTR框架，利用预训练语言模型缓解数据有限问题。PTR结合显式轨迹提示，在多采样间隔数据集上训练，有效泛化不同间隔的稀疏轨迹。引入隐式轨迹提示模拟道路状况，提供更丰富信息。提出轨迹嵌入器，将轨迹点编码并转换为PLM可理解格式。实验证明PTR在两个公共数据集上的有效性和可扩展性。

> Spatiotemporal trajectory data is vital for web-of-things services and is extensively collected and analyzed by web-based hardware and platforms. However, issues such as service interruptions and network instability often lead to sparsely recorded trajectories, resulting in a loss of detailed movement data. As a result, recovering these trajectories to restore missing information becomes essential. Despite progress, several challenges remain unresolved. First, the lack of large-scale dense trajectory data hampers the performance of existing deep learning methods, which rely heavily on abundant data for supervised training. Second, current methods struggle to generalize across sparse trajectories with varying sampling intervals, necessitating separate re-training for each interval and increasing computational costs. Third, external factors crucial for the recovery of missing points are not fully incorporated.
  To address these challenges, we propose a framework called PTR. This framework mitigates the issue of limited dense trajectory data by leveraging the capabilities of pre-trained language models (PLMs). PTR incorporates an explicit trajectory prompt and is trained on datasets with multiple sampling intervals, enabling it to generalize effectively across different intervals in sparse trajectories. To capture external factors, we introduce an implicit trajectory prompt that models road conditions, providing richer information for recovering missing points. Additionally, we present a trajectory embedder that encodes trajectory points and transforms the embeddings of both observed and missing points into a format comprehensible to PLMs. Experimental results on two public trajectory datasets with three sampling intervals demonstrate the efficacy and scalability of PTR.

[Arxiv](https://arxiv.org/abs/2410.14281)