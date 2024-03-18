# 惊人发现，只需单个提示词即可显著增强预训练视觉-语言模型在对抗性环境中的稳健性。

发布时间：2024年03月04日

`Agent`

> One Prompt Word is Enough to Boost Adversarial Robustness for Pre-trained Vision-Language Models

> 尽管 CLIP 等大规模预训练视觉-语言模型具备非凡的泛化能力，但在面对对抗性样本时却显得尤为脆弱。本研究另辟蹊径，不再关注已深入探究的模型权重（本研究中固定不变），而是从文本提示的新视角探索 VLMs 的对抗鲁棒性。研究表明，无论是对抗攻击还是防御手段的效果，均深受所采用文本提示的影响。基于这一发现，我们创新提出一种方法，即通过学习稳定的文本提示来增强 VLMs 抵御对抗攻击的能力，这种方法被命名为“对抗性提示调优”（APT）。APT 不仅高效实用，在计算与数据效率上均有优秀表现。为了验证 APT 的优越性，我们针对 15 个数据集和涵盖从单次示例到全量训练数据的 4 种数据稀疏方案展开了广泛实验，并与手工设计的提示及其他最先进的适应方法进行了对比。结果显示，APT 在分布内性能及应对输入分布变化和跨数据集泛化等方面展现出了卓越的才能。出人意料的是，只需在提示中巧妙地加入一个学习得到的词汇，APT 即可显著提升准确率与鲁棒性（当 epsilon=4/255 时），相较于传统手工设计的提示，平均准确率提高达 +13%，鲁棒性提升 +8.5%；而在我们最为有效的配置下，准确率与鲁棒性的增幅更进一步，分别达到 +26.4% 和 +16.7%。相关代码已开源，地址为：https://github.com/TreeLLi/APT。

> Large pre-trained Vision-Language Models (VLMs) like CLIP, despite having remarkable generalization ability, are highly vulnerable to adversarial examples. This work studies the adversarial robustness of VLMs from the novel perspective of the text prompt instead of the extensively studied model weights (frozen in this work). We first show that the effectiveness of both adversarial attack and defense are sensitive to the used text prompt. Inspired by this, we propose a method to improve resilience to adversarial attacks by learning a robust text prompt for VLMs. The proposed method, named Adversarial Prompt Tuning (APT), is effective while being both computationally and data efficient. Extensive experiments are conducted across 15 datasets and 4 data sparsity schemes (from 1-shot to full training data settings) to show APT's superiority over hand-engineered prompts and other state-of-the-art adaption methods. APT demonstrated excellent abilities in terms of the in-distribution performance and the generalization under input distribution shift and across datasets. Surprisingly, by simply adding one learned word to the prompts, APT can significantly boost the accuracy and robustness (epsilon=4/255) over the hand-engineered prompts by +13% and +8.5% on average respectively. The improvement further increases, in our most effective setting, to +26.4% for accuracy and +16.7% for robustness. Code is available at https://github.com/TreeLLi/APT.

[Arxiv](https://arxiv.org/abs/2403.01849)