# 人造科学发现

发布时间：2024年11月18日

`Agent` `人工智能` `科学研究`

> Artificial Scientific Discovery

# 摘要

> 过去十年，深度学习蓬勃发展，本论文从 AlphaGo 到 ChatGPT，通过实证研究来探究实现人工科学家这一愿景所需的基本概念，即能够自主开展原创研究并助力人类知识拓展的机器。研究从{\sc Olivaw}起步，它类似 AlphaGo Zero 代理，能从零开始发现奥赛罗知识，却无法交流。由此催生了解释性学习（EL）框架，它将科学家向同行解释新现象时面临的问题形式化。有效的 EL 方案助我们攻克了 Zendo 这一模拟科学探索的棋盘游戏。此番成功带来一个关键见解：人工科学家必须对用于阐释其发现的语言形成自身的理解。这一观点让我们把现代多模态模型视作阐释者，并设计出构建可阐释且经济高效的类似 CLIP 模型的新途径：利用少量多模态数据，无需进一步训练，耦合两个单模态模型。最后，我们探讨了 ChatGPT 及其同类要成为人工科学家所欠缺的部分，并介绍了 Odeen 这一基准，它表明 LLMs 的表现不过是碰运气，而人类却能轻松搞定。

> Rooted in the explosion of deep learning over the past decade, this thesis spans from AlphaGo to ChatGPT to empirically examine the fundamental concepts needed to realize the vision of an artificial scientist: a machine with the capacity to autonomously generate original research and contribute to the expansion of human knowledge. The investigation begins with {\sc Olivaw}, an AlphaGo Zero-like agent that discovers Othello knowledge from scratch but is unable to communicate it. This realization leads to the development of the Explanatory Learning (EL) framework, a formalization of the problem faced by a scientist when trying to explain a new phenomenon to their peers. The effective EL prescriptions allow us to crack Zendo, a board game simulating the scientific endeavor. This success comes with a fundamental insight: an artificial scientist must develop its own interpretation of the language used to explain its findings. This perspective then leads us to see modern multimodal models as interpreters, and to devise a new way to build interpretable and cost-effective CLIP-like models: by coupling two unimodal models using little multimodal data and no further training. Finally, we discuss what ChatGPT and its siblings are still missing to become artificial scientists, and introduce Odeen, a benchmark about interpreting explanations that sees LLMs going no further than random chance while being instead fully solved by humans.

[Arxiv](https://arxiv.org/abs/2411.11672)