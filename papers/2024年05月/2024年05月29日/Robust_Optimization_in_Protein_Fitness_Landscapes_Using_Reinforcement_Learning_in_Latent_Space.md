# 利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化

发布时间：2024年05月29日

`Agent

理由：这篇论文介绍了一种名为LatProtRL的系统，它利用大型蛋白质语言模型和强化学习来优化蛋白质序列。这种方法将优化过程建模为马尔可夫决策过程，并通过强化学习在潜在空间中直接操作，以避免陷入局部最优。这种系统可以被视为一个自主的Agent，因为它能够根据环境反馈（如适应性评估）做出决策并优化其行为。因此，这篇论文更适合归类为Agent，因为它描述了一个能够自主学习和优化任务的智能系统。` `生物技术` `蛋白质工程`

> Robust Optimization in Protein Fitness Landscapes Using Reinforcement Learning in Latent Space

# 摘要

> 蛋白质作为自然界中执行多种功能的复杂分子，其功能性和细胞适应性的提升对多个行业具有重大影响。尽管如此，通过计算方法优化蛋白质仍是一大挑战，尤其是在处理低适应性序列时。为此，我们开发了LatProtRL，一种利用大型蛋白质语言模型编码器-解码器学习到的潜在空间进行高效优化的方法。为避免陷入局部最优，我们将优化过程建模为马尔可夫决策过程，并采用强化学习在潜在空间中直接操作。在两项关键的适应性优化任务中，我们的方法展现了与现有方法相媲美甚至更优的性能。实验和体外评估结果显示，LatProtRL生成的序列能够达到高适应性水平，预示着其在实验室闭环应用中的巨大潜力。

> Proteins are complex molecules responsible for different functions in nature. Enhancing the functionality of proteins and cellular fitness can significantly impact various industries. However, protein optimization using computational methods remains challenging, especially when starting from low-fitness sequences. We propose LatProtRL, an optimization method to efficiently traverse a latent space learned by an encoder-decoder leveraging a large protein language model. To escape local optima, our optimization is modeled as a Markov decision process using reinforcement learning acting directly in latent space. We evaluate our approach on two important fitness optimization tasks, demonstrating its ability to achieve comparable or superior fitness over baseline methods. Our findings and in vitro evaluation show that the generated sequences can reach high-fitness regions, suggesting a substantial potential of LatProtRL in lab-in-the-loop scenarios.

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/x1.png)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/x2.png)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/x3.png)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/x4.png)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/x5.png)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/gfp_invitro.jpg)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/seqalign.jpg)

![利用强化学习在潜在空间中探索蛋白质适应性景观，实现鲁棒优化](../../../paper_images/2405.18986/traj.png)

[Arxiv](https://arxiv.org/abs/2405.18986)