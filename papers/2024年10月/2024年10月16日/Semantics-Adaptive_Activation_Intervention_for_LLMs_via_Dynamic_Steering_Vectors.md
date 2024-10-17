# 利用动态转向向量实现 LLM 的语义自适应激活干预

发布时间：2024年10月16日

`LLM理论` `人工智能`

> Semantics-Adaptive Activation Intervention for LLMs via Dynamic Steering Vectors

# 摘要

> 尽管大型语言模型 (LLM) 在多项任务中表现出色，但如何使其行为符合预期仍是一大挑战。激活干预作为一种高效且经济的手段，正逐渐成为调整 LLM 行为的关键方法。然而，现有方法多采用固定转向向量，难以适应多样化的输入语义。为此，我们推出了语义自适应动态干预 (SADI)，通过构建动态转向向量，在推理时精准干预模型激活。SADI 利用对比对中的激活差异，精确识别 LLM 的关键元素，如注意力头、隐藏状态和神经元，从而实现有针对性的干预。实验证明，SADI 不仅显著超越现有基线，还能在不需额外训练的情况下提升任务性能。其成本效益和广泛适用性使其成为一种极具潜力的多功能对齐技术。我们还公开了相关代码，以推动这一领域的研究进展：https://github.com/weixuan-wang123/SADI。

> Large language models (LLMs) have achieved remarkable performance across many tasks, yet aligning them with desired behaviors remains challenging. Activation intervention has emerged as an effective and economical method to modify the behavior of LLMs. Despite considerable interest in this area, current intervention methods exclusively employ a fixed steering vector to modify model activations, lacking adaptability to diverse input semantics. To address this limitation, we propose Semantics-Adaptive Dynamic Intervention (SADI), a novel method that constructs a dynamic steering vector to intervene model activations at inference time. More specifically, SADI utilizes activation differences in contrastive pairs to precisely identify critical elements of an LLM (i.e., attention heads, hidden states, and neurons) for targeted intervention. During inference, SADI dynamically steers model behavior by scaling element-wise activations based on the directions of input semantics. Experimental results show that SADI outperforms established baselines by substantial margins, improving task performance without training. SADI's cost-effectiveness and generalizability across various LLM backbones and tasks highlight its potential as a versatile alignment technique. In addition, we release the code to foster research along this line:https://github.com/weixuan-wang123/SADI.

[Arxiv](https://arxiv.org/abs/2410.12299)