# h4rm3l：一款动态基准，专为评估 LLM 安全性而设计，涵盖多种可组合的越狱攻击手段。

发布时间：2024年08月08日

`LLM应用` `网络安全` `人工智能`

> h4rm3l: A Dynamic Benchmark of Composable Jailbreak Attacks for LLM Safety Assessment

# 摘要

> 大型语言模型（LLM）的安全性因缺乏系统评估其抵抗有害内容生成能力的基准而备受关注。我们提出了一种创新的组合越狱攻击动态基准，超越了传统的静态数据集和分类法。我们的方法h4rm3l包含三个部分：（1）一种领域特定语言，将越狱攻击正式化为参数化提示转换的组合，（2）基于强盗的少样本程序合成算法，生成针对特定LLM安全过滤器的优化攻击，（3）采用这些技术的开源自动化红队软件。我们利用h4rm3l生成了针对6个顶尖LLM的2656次成功越狱攻击，其中一些攻击的成功率超过90%，优于以往记录。h4rm3l通过统一正式表示的越狱攻击数据集，推动了可重复基准测试和自动化红队的发展，加深了对LLM安全局限性的理解，并助力构建在LLM广泛应用环境中的强大防御体系。警告：本文及相关研究内容包含可能令人不适的提示和模型生成内容。

> The safety of Large Language Models (LLMs) remains a critical concern due to a lack of adequate benchmarks for systematically evaluating their ability to resist generating harmful content. Previous efforts towards automated red teaming involve static or templated sets of illicit requests and adversarial prompts which have limited utility given jailbreak attacks' evolving and composable nature. We propose a novel dynamic benchmark of composable jailbreak attacks to move beyond static datasets and taxonomies of attacks and harms. Our approach consists of three components collectively called h4rm3l: (1) a domain-specific language that formally expresses jailbreak attacks as compositions of parameterized prompt transformation primitives, (2) bandit-based few-shot program synthesis algorithms that generate novel attacks optimized to penetrate the safety filters of a target black box LLM, and (3) open-source automated red-teaming software employing the previous two components. We use h4rm3l to generate a dataset of 2656 successful novel jailbreak attacks targeting 6 state-of-the-art (SOTA) open-source and proprietary LLMs. Several of our synthesized attacks are more effective than previously reported ones, with Attack Success Rates exceeding 90% on SOTA closed language models such as claude-3-haiku and GPT4-o. By generating datasets of jailbreak attacks in a unified formal representation, h4rm3l enables reproducible benchmarking and automated red-teaming, contributes to understanding LLM safety limitations, and supports the development of robust defenses in an increasingly LLM-integrated world.
  Warning: This paper and related research artifacts contain offensive and potentially disturbing prompts and model-generated content.

[Arxiv](https://arxiv.org/abs/2408.04811)