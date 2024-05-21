# MAML-en-LLM：提升 LLMs 上下文学习能力的模型无关元训练法

发布时间：2024年05月19日

`LLM理论

这篇论文探讨了如何通过元训练策略使大型语言模型（LLMs）适应未见任务，而不进行微调。它提出了MAML-en-LLM方法，这是一种新的训练方法，旨在训练出能够在不同任务上表现优异并能适应新任务的LLMs。论文通过实验展示了这种方法在未见领域的性能提升，并探讨了影响元训练的各种因素。这些内容属于对LLM理论的深入研究，因此应归类为LLM理论。` `机器学习`

> MAML-en-LLM: Model Agnostic Meta-Training of LLMs for Improved In-Context Learning

# 摘要

> 如何让大型语言模型（LLMs）通过上下文训练样本适应未见任务，而不进行微调，仍是研究的热点。为此，研究者们提出了MetaICL和MetaICT等元训练策略，旨在通过多样化的任务训练预设的LLMs。这些方法通过上下文多任务微调，在独立的测试集上评估模型。虽然成效显著，但它们并未追求一套真正通用的参数。本文提出的MAML-en-LLM方法，能够训练出既能在不同任务上表现优异，又能适应新任务的LLMs。实验显示，在未见领域，性能平均提升2%，适应性提升高达4%。此外，在训练数据有限的情况下，MAML-en-LLM在已见和未见领域的表现均优于其他方法，平均提升2%。文章还探讨了任务类型、优化器选择及任务复杂度对元训练的影响，这些因素在以往研究中鲜有涉及。通过在7种任务和两种数据设置上的详尽测试，MAML-en-LLM展现出了超越现有技术的优势。

> Adapting large language models (LLMs) to unseen tasks with in-context training samples without fine-tuning remains an important research problem. To learn a robust LLM that adapts well to unseen tasks, multiple meta-training approaches have been proposed such as MetaICL and MetaICT, which involve meta-training pre-trained LLMs on a wide variety of diverse tasks. These meta-training approaches essentially perform in-context multi-task fine-tuning and evaluate on a disjointed test set of tasks. Even though they achieve impressive performance, their goal is never to compute a truly general set of parameters. In this paper, we propose MAML-en-LLM, a novel method for meta-training LLMs, which can learn truly generalizable parameters that not only perform well on disjointed tasks but also adapts to unseen tasks. We see an average increase of 2% on unseen domains in the performance while a massive 4% improvement on adaptation performance. Furthermore, we demonstrate that MAML-en-LLM outperforms baselines in settings with limited amount of training data on both seen and unseen domains by an average of 2%. Finally, we discuss the effects of type of tasks, optimizers and task complexity, an avenue barely explored in meta-training literature. Exhaustive experiments across 7 task settings along with two data settings demonstrate that models trained with MAML-en-LLM outperform SOTA meta-training approaches.

![MAML-en-LLM：提升 LLMs 上下文学习能力的模型无关元训练法](../../../paper_images/2405.11446/x1.png)

![MAML-en-LLM：提升 LLMs 上下文学习能力的模型无关元训练法](../../../paper_images/2405.11446/x2.png)

![MAML-en-LLM：提升 LLMs 上下文学习能力的模型无关元训练法](../../../paper_images/2405.11446/x3.png)

![MAML-en-LLM：提升 LLMs 上下文学习能力的模型无关元训练法](../../../paper_images/2405.11446/x4.png)

[Arxiv](https://arxiv.org/abs/2405.11446)