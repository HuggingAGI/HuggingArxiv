# JailbreakBench：为破解大型语言模型而设立的开放性鲁棒性评估标准。

发布时间：2024年03月27日

`RAG` `评估基准` `安全性测试`

> JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models

# 摘要

> 越狱攻击可能诱使大型语言模型（LLMs）产生不当内容，但评估这类攻击面临诸多难题，现行的基准和评估方法并不完善。首先，缺乏统一的越狱评估标准；其次，现有研究在成本和成功率的计算上缺乏可比性；再者，许多研究因隐藏对抗性提示、使用闭源代码或依赖不稳定的专有API而难以复现。为此，我们推出了JailbreakBench，一个包含新越狱数据集JBB-Behaviors、不断更新的对抗性提示库（越狱文物）、明确定义的评估框架和排行榜的开源基准测试。我们充分考虑了发布此基准的伦理影响，并相信它将对社区产生积极作用。我们将根据研究进展不断完善和更新这一基准。

> Jailbreak attacks cause large language models (LLMs) to generate harmful, unethical, or otherwise objectionable content. Evaluating these attacks presents a number of challenges, which the current collection of benchmarks and evaluation techniques do not adequately address. First, there is no clear standard of practice regarding jailbreaking evaluation. Second, existing works compute costs and success rates in incomparable ways. And third, numerous works are not reproducible, as they withhold adversarial prompts, involve closed-source code, or rely on evolving proprietary APIs. To address these challenges, we introduce JailbreakBench, an open-sourced benchmark with the following components: (1) a new jailbreaking dataset containing 100 unique behaviors, which we call JBB-Behaviors; (2) an evolving repository of state-of-the-art adversarial prompts, which we refer to as jailbreak artifacts; (3) a standardized evaluation framework that includes a clearly defined threat model, system prompts, chat templates, and scoring functions; and (4) a leaderboard that tracks the performance of attacks and defenses for various LLMs. We have carefully considered the potential ethical implications of releasing this benchmark, and believe that it will be a net positive for the community. Over time, we will expand and adapt the benchmark to reflect technical and methodological advances in the research community.

[Arxiv](https://arxiv.org/abs/2404.01318)