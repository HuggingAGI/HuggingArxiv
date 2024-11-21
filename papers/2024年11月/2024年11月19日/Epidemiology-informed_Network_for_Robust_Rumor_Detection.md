# 基于流行病学的网络用于可靠的谣言检测

发布时间：2024年11月19日

`LLM应用` `社交媒体` `谣言检测`

> Epidemiology-informed Network for Robust Rumor Detection

# 摘要

> 社交媒体上谣言的快速传播，给维护公众信任和信息的完整性带来了巨大挑战。因为信息的级联过程本质上就是一棵传播树，所以近来的谣言检测模型借助图神经网络来额外捕捉信息传播模式，进而胜过仅基于文本的方案。鉴于根节点的主题和社会影响存在差异，不同的源信息自然具备不同的传播能力，致使传播树的高度各异。然而，这种差异阻碍了现有的基于图的谣言检测器的数据驱动设计。对于交互有限的浅传播树，基于图的方法难以捕获足够的级联模式，让人对其处理不太热门的新闻或早期检测需求的能力产生质疑。相反，深传播树容易受到嘈杂的用户响应干扰，这反过来可能会模糊预测。在本文中，我们提出了一种新颖的流行病学知情网络（EIN），它融合了流行病学知识，以克服数据驱动方法对数据质量的敏感性来提升性能。同时，为让流行病学理论适配谣言检测，预计要对每个用户针对源信息的立场予以标注。为避开昂贵且耗时的人工标注流程，我们利用大型语言模型生成立场标签，助力实现学习流行病学知情表示的优化目标。我们的实验结果表明，所提出的 EIN 不仅在真实世界的数据集中优于前沿方法，而且在不同的树深度上展现出更强的稳健性。

> The rapid spread of rumors on social media has posed significant challenges to maintaining public trust and information integrity. Since an information cascade process is essentially a propagation tree, recent rumor detection models leverage graph neural networks to additionally capture information propagation patterns, thus outperforming text-only solutions. Given the variations in topics and social impact of the root node, different source information naturally has distinct outreach capabilities, resulting in different heights of propagation trees. This variation, however, impedes the data-driven design of existing graph-based rumor detectors. Given a shallow propagation tree with limited interactions, it is unlikely for graph-based approaches to capture sufficient cascading patterns, questioning their ability to handle less popular news or early detection needs. In contrast, a deep propagation tree is prone to noisy user responses, and this can in turn obfuscate the predictions. In this paper, we propose a novel Epidemiology-informed Network (EIN) that integrates epidemiological knowledge to enhance performance by overcoming data-driven methods sensitivity to data quality. Meanwhile, to adapt epidemiology theory to rumor detection, it is expected that each users stance toward the source information will be annotated. To bypass the costly and time-consuming human labeling process, we take advantage of large language models to generate stance labels, facilitating optimization objectives for learning epidemiology-informed representations. Our experimental results demonstrate that the proposed EIN not only outperforms state-of-the-art methods on real-world datasets but also exhibits enhanced robustness across varying tree depths.

[Arxiv](https://arxiv.org/abs/2411.12949)