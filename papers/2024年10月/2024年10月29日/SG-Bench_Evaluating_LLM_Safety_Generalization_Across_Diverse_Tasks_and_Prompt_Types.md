# SG-Bench：评估大型语言模型在各类任务和提示类型中的安全泛化情况

发布时间：2024年10月29日

`LLM应用` `人工智能` `语言模型`

> SG-Bench: Evaluating LLM Safety Generalization Across Diverse Tasks and Prompt Types

# 摘要

> 确保大型语言模型（LLM）应用的安全对于开发值得信赖的人工智能极为关键。当下的 LLM 安全基准存在两个局限。其一，它们要么只着眼于判别式评估范式，要么只关注生成式评估范式，却忽视了二者的相互关联。其二，它们依赖标准化输入，忽略了诸如系统提示、少样本演示和思维链提示等广泛提示技术的影响。为解决这些问题，我们研发了 SG-Bench，这一全新的基准用于评估 LLM 在各类任务和提示类型中的安全泛化能力。此基准融合了生成式和判别式评估任务，并涵盖扩展数据以考查提示工程和越狱对 LLM 安全的影响。我们借助该基准对 3 个先进的专有 LLM 和 10 个开源 LLM 展开评估，发现大多数 LLM 在判别式任务中的表现逊于生成式任务，且对提示极为敏感，这表明其在安全对齐方面的泛化能力欠佳。我们还对这些发现进行了定量和定性的阐释，为后续研究提供了思路。

> Ensuring the safety of large language model (LLM) applications is essential for developing trustworthy artificial intelligence. Current LLM safety benchmarks have two limitations. First, they focus solely on either discriminative or generative evaluation paradigms while ignoring their interconnection. Second, they rely on standardized inputs, overlooking the effects of widespread prompting techniques, such as system prompts, few-shot demonstrations, and chain-of-thought prompting. To overcome these issues, we developed SG-Bench, a novel benchmark to assess the generalization of LLM safety across various tasks and prompt types. This benchmark integrates both generative and discriminative evaluation tasks and includes extended data to examine the impact of prompt engineering and jailbreak on LLM safety. Our assessment of 3 advanced proprietary LLMs and 10 open-source LLMs with the benchmark reveals that most LLMs perform worse on discriminative tasks than generative ones, and are highly susceptible to prompts, indicating poor generalization in safety alignment. We also explain these findings quantitatively and qualitatively to provide insights for future research.

[Arxiv](https://arxiv.org/abs/2410.21965)