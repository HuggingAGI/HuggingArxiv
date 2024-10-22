# 大型语言模型面临的现实越狱威胁

发布时间：2024年10月21日

`LLM理论` `网络安全` `人工智能`

> A Realistic Threat Model for Large Language Model Jailbreaks

# 摘要

> 为了从安全调整的 LLM 中获取有害响应，研究人员提出了多种越狱攻击。尽管这些方法在原始设置中都能成功迫使目标输出，但它们在流畅性和计算成本上差异显著。为此，我们提出了一种统一的威胁模型，用于系统比较这些攻击。该模型结合了困惑度（衡量越狱文本与自然文本的偏离程度）和计算预算（以 FLOP 为单位）。我们构建了一个基于 1T 标记的 N-gram 模型，与传统模型相比，它更具 LLM 不可知性和可解释性。我们将常见攻击适应于这一新模型，首次在同等条件下进行基准测试。结果显示，针对现代安全模型的攻击成功率低于预期，且基于离散优化的攻击明显优于基于 LLM 的攻击。我们的模型因其可解释性，能够全面分析越狱攻击。研究发现，有效攻击往往利用并滥用不常见的 N-gram，这些 N-gram 要么在现实文本中不存在，要么极为罕见，如特定于代码数据集的 N-gram。

> A plethora of jailbreaking attacks have been proposed to obtain harmful responses from safety-tuned LLMs. In their original settings, these methods all largely succeed in coercing the target output, but their attacks vary substantially in fluency and computational effort. In this work, we propose a unified threat model for the principled comparison of these methods. Our threat model combines constraints in perplexity, measuring how far a jailbreak deviates from natural text, and computational budget, in total FLOPs. For the former, we build an N-gram model on 1T tokens, which, in contrast to model-based perplexity, allows for an LLM-agnostic and inherently interpretable evaluation. We adapt popular attacks to this new, realistic threat model, with which we, for the first time, benchmark these attacks on equal footing. After a rigorous comparison, we not only find attack success rates against safety-tuned modern models to be lower than previously presented but also find that attacks based on discrete optimization significantly outperform recent LLM-based attacks. Being inherently interpretable, our threat model allows for a comprehensive analysis and comparison of jailbreak attacks. We find that effective attacks exploit and abuse infrequent N-grams, either selecting N-grams absent from real-world text or rare ones, e.g. specific to code datasets.

[Arxiv](https://arxiv.org/abs/2410.16222)