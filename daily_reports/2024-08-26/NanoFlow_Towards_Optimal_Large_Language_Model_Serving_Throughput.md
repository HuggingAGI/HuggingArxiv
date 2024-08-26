# NanoFlow：致力于提升大型语言模型的服务吞吐量至最优水平
发布时间：2024年08月22日


> NanoFlow: Towards Optimal Large Language Model Serving Throughput
>
> 随着大型语言模型 (LLM) 的广泛应用，全球规模的部署系统需求激增，数万台 GPU 持续服务数亿用户。吞吐量（在合理延迟下）成为衡量系统性能的关键指标。为提升吞吐量，虽已探索多种设备间并行方法，但现有技术未充分利用单设备内资源，导致性能受限。我们提出 NanoFlow，一种创新部署框架，通过操作协同调度，实现单设备内计算、内存和网络资源的重叠使用。NanoFlow 引入两项关键创新：首先，在操作粒度上将请求拆分为纳米批次，打破 LLM 推理中的顺序依赖，实现资源重叠；其次，采用操作级管道与执行单元调度，将设备功能单元分区，同时执行不同操作。NanoFlow 通过参数搜索算法自动配置管道，便于移植至不同模型。我们在 NVIDIA GPU 上实现 NanoFlow，并在多个流行模型上评估端到端吞吐量。在实际工作负载下，NanoFlow 相比顶尖部署系统，吞吐量提升 1.91 倍，达到移植模型中 59% 至 72% 的最优性能。
>
> https://arxiv.org/abs/2408.12757

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2408.12757](https://arxiv.org/abs/2408.12757)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)