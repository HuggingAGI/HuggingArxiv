# 大型语言模型版本更新中的学习率路径切换训练新范式

发布时间：2024年10月05日

`LLM理论` `人工智能` `机器学习`

> A Learning Rate Path Switching Training Paradigm for Version Updates of Large Language Models

# 摘要

> 随着新数据的不断涌现，版本更新已成为 LLM 的必备环节。LLM 的更新方式主要有两种：从头开始预训练 (PTFS) 和持续预训练 (CPT)。初步实验显示，PTFS 在预训练性能上更胜一筹，而 CPT 则更节省成本。随着版本更新的推进，两者在性能和成本上的差距逐渐拉大。为了探究这一现象的根源，我们深入分析了 CPT 过程中学习率调整的影响，特别是在初始化检查点和持续预训练阶段。研究发现，第一阶段的大学习率和第二阶段的完整学习率衰减过程对 LLM 的更新至关重要。基于此，我们提出了一种学习率路径切换训练范式。该范式包括一条主路径，即以最大学习率进行预训练，以及多条分支路径，每条路径对应一次使用新数据的更新。实验结果表明，我们的范式不仅有效，而且具有良好的泛化性。特别是在训练四个版本的 LLM 时，我们的范式将总成本降至 PTFS 的 58%，同时保持了相当的预训练效果。

> Due to the continuous emergence of new data, version updates have become an indispensable requirement for Large Language Models (LLMs). The training paradigms for version updates of LLMs include pre-training from scratch (PTFS) and continual pre-training (CPT). Preliminary experiments demonstrate that PTFS achieves better pre-training performance, while CPT has lower training cost. Moreover, their performance and training cost gaps widen progressively with version updates. To investigate the underlying reasons for this phenomenon, we analyze the effect of learning rate adjustments during the two stages of CPT: preparing an initialization checkpoint and continual pre-training based on this checkpoint. We find that a large learning rate in the first stage and a complete learning rate decay process in the second stage are crucial for version updates of LLMs. Hence, we propose a learning rate path switching training paradigm. Our paradigm comprises one main path, where we pre-train a LLM with the maximal learning rate, and multiple branching paths, each of which corresponds to an update of the LLM with newly-added training data. Extensive experiments demonstrate the effectiveness and generalization of our paradigm. Particularly, when training four versions of LLMs, our paradigm reduces the total training cost to 58% compared to PTFS, while maintaining comparable pre-training performance.

[Arxiv](https://arxiv.org/abs/2410.04103)