# 来一探究竟吧！重新审视评估语言模型突破的方法。

发布时间：2024年04月09日

`LLM应用` `信息安全` `内容生成`

> Take a Look at it! Rethinking How to Evaluate Language Model Jailbreak

# 摘要

> 大型语言模型（LLMs）已广泛应用于各类应用场景中。为防止LLMs输出不安全内容，它们被设计为遵循一系列安全规范。然而，有人通过所谓的“越狱”技术绕过这些规范，制造违规内容。目前，已有多种系统能自动实现越狱，它们通过评估方法来判断越狱是否成功。但我们发现，现有的越狱评估方法存在不足：首先，评估目标模糊，未能有效识别不安全的回答；其次，将越狱结果过于简化为成功或失败的二元判定。本文提出了三个新的评估指标——安全违规、信息量和相对真实性，用以衡量语言模型的越狱行为。我们还探讨了这些指标与不同恶意使用者目标的关联。我们采用了一种多维度方法，对回答进行预处理后，再结合自然语言生成的评估方法进行计算。我们基于三个恶意意图数据集和三个越狱系统构建了基准数据集，并由三名标注员进行标注。通过与现有的三种越狱评估方法对比，我们的多维度评估方法表现出更好的性能，F1分数平均提升了17%。研究表明，我们需要超越简单的二元评估框架，采用更全面的评估手段，以确保语言模型的安全可靠。

> Large language models (LLMs) have become increasingly integrated with various applications. To ensure that LLMs do not generate unsafe responses, they are aligned with safeguards that specify what content is restricted. However, such alignment can be bypassed to produce prohibited content using a technique commonly referred to as jailbreak. Different systems have been proposed to perform the jailbreak automatically. These systems rely on evaluation methods to determine whether a jailbreak attempt is successful. However, our analysis reveals that current jailbreak evaluation methods have two limitations. (1) Their objectives lack clarity and do not align with the goal of identifying unsafe responses. (2) They oversimplify the jailbreak result as a binary outcome, successful or not.
  In this paper, we propose three metrics, safeguard violation, informativeness, and relative truthfulness, to evaluate language model jailbreak. Additionally, we demonstrate how these metrics correlate with the goal of different malicious actors. To compute these metrics, we introduce a multifaceted approach that extends the natural language generation evaluation method after preprocessing the response. We evaluate our metrics on a benchmark dataset produced from three malicious intent datasets and three jailbreak systems. The benchmark dataset is labeled by three annotators. We compare our multifaceted approach with three existing jailbreak evaluation methods. Experiments demonstrate that our multifaceted evaluation outperforms existing methods, with F1 scores improving on average by 17% compared to existing baselines. Our findings motivate the need to move away from the binary view of the jailbreak problem and incorporate a more comprehensive evaluation to ensure the safety of the language model.

[Arxiv](https://arxiv.org/abs/2404.06407)