# Velocitune：一种用于持续预训练的基于速度的动态域重加权方法

发布时间：2024年11月21日

`LLM应用` `语言模型` `数据处理`

> Velocitune: A Velocity-based Dynamic Domain Reweighting Method for Continual Pre-training

# 摘要

> 众所周知，多样化的语料库对训练大型语言模型极为关键，这类模型通常由来自不同领域的混合数据构建。通常，以往的做法是从不同领域按静态比例抽取训练数据，还会在训练时调整数据比例。但很少有方法能应对领域自适应持续预训练的复杂情况。为填补这一空缺，我们提出了 Velocitune，这一新颖框架能动态评估学习速度并相应调整数据比例，倾向学习较慢的领域而避开较快的领域，其依据是一个缩放定律，能以更低的相关成本指明每个领域期望的学习目标。为评估 Velocitune 的有效性，我们在以推理为重点的数据集 CodeLlama 以及专门用于系统命令生成的语料库 Llama3 和 Mistral 中开展实验。Velocitune 在数学和代码推理任务以及命令行生成基准测试中都实现了性能提升。进一步分析表明，推动 Velocitune 发挥效用的关键因素包括目标损失预测和数据排序。

> It is well-known that a diverse corpus is critical for training large language models, which are typically constructed from a mixture of various domains. In general, previous efforts resort to sampling training data from different domains with static proportions, as well as adjusting data proportions during training. However, few methods have addressed the complexities of domain-adaptive continual pre-training. To fill this gap, we propose Velocitune, a novel framework dynamically assesses learning velocity and adjusts data proportions accordingly, favoring slower-learning domains while shunning faster-learning ones, which is guided by a scaling law to indicate the desired learning goal for each domain with less associated cost. To evaluate the effectiveness of Velocitune, we conduct experiments in a reasoning-focused dataset with CodeLlama, as well as in a corpus specialised for system command generation with Llama3 and Mistral. Velocitune achieves performance gains in both math and code reasoning tasks and command-line generation benchmarks. Further analysis reveals that key factors driving Velocitune's effectiveness include target loss prediction and data ordering.

[Arxiv](https://arxiv.org/abs/2411.14318)