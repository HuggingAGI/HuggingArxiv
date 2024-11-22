# 对大型语言模型中类比推理的稳健程度进行评估

发布时间：2024年11月21日

`LLM应用` `人工智能`

> Evaluating the Robustness of Analogical Reasoning in Large Language Models

# 摘要

> LLMs 在多个推理基准测试中表现优异，其中就包含对类比推理能力的测试。不过，对于它们到底是在进行一般性的抽象推理，还是采用了非稳健的流程（比如过度依赖与预训练数据的相似性），存在着争议。在此，我们针对 Webb、Holyoak 和 Lu（2023）所研究的四个领域中的三个（字母字符串类比、数字矩阵和故事类比），探究了先前宣称的 LLMs 类比能力的稳健性。对于每个领域，我们都对人类和 GPT 模型针对原始类比问题变体的稳健性进行了测试，这些变体测试的是相同的抽象推理能力，但可能与预训练数据中的任务有所不同。使用稳健抽象推理的系统，其性能在这些变体上不应大幅下降。
  在简单的字母字符串类比中，我们发现，对于我们测试的两种变体，人类的表现一直很高，而 GPT 模型的表现却大幅下滑。随着问题复杂度的增加，这种情况变得不那么明显，因为人类和 GPT 模型在需要更复杂类比的原始问题和变体问题上表现都不太好。在数字矩阵问题上，我们发现了类似的情况，但仅在我们测试的两种变体中的一种上出现。在基于故事的类比问题上，我们发现，与人类不同，GPT 模型的性能易受答案顺序的影响，而且 GPT 模型可能比人类对释义更敏感。
  这项工作提供了证据，表明 LLMs 通常缺乏零样本人类类比能力的稳健性，在我们测试的大多数变体上都表现脆弱。更广泛地说，这项工作指出，在测试 AI 系统的认知能力时，不仅要评估准确性，还要评估其稳健性，这一点至关重要。

> LLMs have performed well on several reasoning benchmarks, including ones that test analogical reasoning abilities. However, there is debate on the extent to which they are performing general abstract reasoning versus employing non-robust processes, e.g., that overly rely on similarity to pre-training data. Here we investigate the robustness of analogy-making abilities previously claimed for LLMs on three of four domains studied by Webb, Holyoak, and Lu (2023): letter-string analogies, digit matrices, and story analogies. For each domain we test humans and GPT models on robustness to variants of the original analogy problems that test the same abstract reasoning abilities but are likely dissimilar from tasks in the pre-training data. The performance of a system that uses robust abstract reasoning should not decline substantially on these variants.
  On simple letter-string analogies, we find that while the performance of humans remains high for two types of variants we tested, the GPT models' performance declines sharply. This pattern is less pronounced as the complexity of these problems is increased, as both humans and GPT models perform poorly on both the original and variant problems requiring more complex analogies. On digit-matrix problems, we find a similar pattern but only on one out of the two types of variants we tested. On story-based analogy problems, we find that, unlike humans, the performance of GPT models are susceptible to answer-order effects, and that GPT models also may be more sensitive than humans to paraphrasing.
  This work provides evidence that LLMs often lack the robustness of zero-shot human analogy-making, exhibiting brittleness on most of the variations we tested. More generally, this work points to the importance of carefully evaluating AI systems not only for accuracy but also robustness when testing their cognitive capabilities.

[Arxiv](https://arxiv.org/abs/2411.14215)