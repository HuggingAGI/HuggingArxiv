# MarketGPT：开发用于对金融时间序列进行建模的预训练 Transformer（GPT）

发布时间：2024年11月25日

`LLM应用` `时间序列`

> MarketGPT: Developing a Pre-trained transformer (GPT) for Modeling Financial Time Series

# 摘要

> 此项工作呈现了一款专为建模金融时间序列打造的生成式预训练转换器（GPT）。GPT在离散事件模拟器里充当订单生成引擎，能够逼真地复刻限价订单簿的动态。我们的模型借助大型语言模型的最新成果，以流式生成长序列的订单消息。我们的成果表明，即便初始订单流提示不在模型的上下文窗口内，该模型仍成功重现了订单流数据的关键特征。另外，评估显示，该模型捕捉到了真实金融市场及更广泛宏观规模数据分布的若干统计特性，即“程式化事实”。总体而言，这项工作朝着创建高保真、交互式市场模拟迈出了关键的一步。

> This work presents a generative pre-trained transformer (GPT) designed for modeling financial time series. The GPT functions as an order generation engine within a discrete event simulator, enabling realistic replication of limit order book dynamics. Our model leverages recent advancements in large language models to produce long sequences of order messages in a steaming manner. Our results demonstrate that the model successfully reproduces key features of order flow data, even when the initial order flow prompt is no longer present within the model's context window. Moreover, evaluations reveal that the model captures several statistical properties, or 'stylized facts', characteristic of real financial markets and broader macro-scale data distributions. Collectively, this work marks a significant step toward creating high-fidelity, interactive market simulations.

[Arxiv](https://arxiv.org/abs/2411.16585)