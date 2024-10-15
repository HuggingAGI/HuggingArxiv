# 机器人扩散变换器的核心要素

发布时间：2024年10月13日

`Agent` `机器人` `人工智能`

> The Ingredients for Robotic Diffusion Transformers

# 摘要

> 近年来，机器人学家通过结合高容量 Transformer 网络和生成扩散模型，在灵巧机器人硬件上取得了显著进展。然而，将这两种技术结合却异常困难，因为缺乏明确的设计指南。本文中，我们深入研究并优化了高容量扩散 Transformer 的关键设计决策，使得模型能在多个机器人上高效执行任务，无需繁琐的超参数调优。结合我们的研究成果与改进的模型组件，我们推出了一种名为 \method 的新架构，显著提升了双臂 ALOHA 机器人长期任务的解决能力。此外，我们的策略在多模态、语言注释的 ALOHA 数据上训练时，表现出更强的扩展性。我们期待这项工作能推动未来机器人学习技术的发展，充分利用生成扩散模型与 Transformer 架构的优势。相关代码、数据集和视频已公开，详情请访问：https://dit-policy.github.io

> In recent years roboticists have achieved remarkable progress in solving increasingly general tasks on dexterous robotic hardware by leveraging high capacity Transformer network architectures and generative diffusion models. Unfortunately, combining these two orthogonal improvements has proven surprisingly difficult, since there is no clear and well-understood process for making important design choices. In this paper, we identify, study and improve key architectural design decisions for high-capacity diffusion transformer policies. The resulting models can efficiently solve diverse tasks on multiple robot embodiments, without the excruciating pain of per-setup hyper-parameter tuning. By combining the results of our investigation with our improved model components, we are able to present a novel architecture, named \method, that significantly outperforms the state of the art in solving long-horizon ($1500+$ time-steps) dexterous tasks on a bi-manual ALOHA robot. In addition, we find that our policies show improved scaling performance when trained on 10 hours of highly multi-modal, language annotated ALOHA demonstration data. We hope this work will open the door for future robot learning techniques that leverage the efficiency of generative diffusion modeling with the scalability of large scale transformer architectures. Code, robot dataset, and videos are available at: https://dit-policy.github.io

[Arxiv](https://arxiv.org/abs/2410.10088)