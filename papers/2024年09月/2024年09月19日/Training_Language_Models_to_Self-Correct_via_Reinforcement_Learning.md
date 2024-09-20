# 通过强化学习，训练语言模型实现自我修正

发布时间：2024年09月19日

`LLM理论` `人工智能`

> Training Language Models to Self-Correct via Reinforcement Learning

# 摘要

> 自我纠正是 LLM 的一项重要能力，但在现代 LLM 中效果不佳。现有方法要么依赖多模型，要么需要额外监督。为此，我们提出了 SCoRe，一种多轮在线强化学习方法，利用自生成数据显著提升 LLM 的自我纠正能力。我们发现，仅依赖监督微调（SFT）在模型生成的纠正数据上训练，无法有效实现自我纠正。SCoRe 通过在模型自生成纠正数据的分布下训练，并结合正则化，学习在测试时有效的自我纠正策略，而非简单追求高奖励响应。具体来说，SCoRe 首先在基础模型上进行 RL 训练，生成不易崩溃的策略初始化，再通过奖励红利强化自我纠正。实验表明，SCoRe 在 Gemini 1.0 Pro 和 1.5 Flash 模型上分别将自我纠正能力提升了 15.6% 和 9.1%，在 MATH 和 HumanEval 基准上达到最先进水平。

> Self-correction is a highly desirable capability of large language models (LLMs), yet it has consistently been found to be largely ineffective in modern LLMs. Existing approaches for training self-correction either require multiple models or rely on a more capable model or other forms of supervision. To this end, we develop a multi-turn online reinforcement learning (RL) approach, SCoRe, that significantly improves an LLM's self-correction ability using entirely self-generated data. To build SCoRe, we first show that variants of supervised fine-tuning (SFT) on offline model-generated correction traces are insufficient for instilling self-correction behavior. In particular, we observe that training via SFT either suffers from a distribution mismatch between the training data and the model's own responses or implicitly prefers only a certain mode of correction behavior that is often not effective at test time. SCoRe addresses these challenges by training under the model's own distribution of self-generated correction traces and using appropriate regularization to steer the learning process into learning a self-correction strategy that is effective at test time as opposed to simply fitting high-reward responses for a given prompt. This regularization prescribes running a first phase of RL on a base model to generate a policy initialization that is less susceptible to collapse and then using a reward bonus to amplify self-correction during training. When applied to Gemini 1.0 Pro and 1.5 Flash models, we find that SCoRe achieves state-of-the-art self-correction performance, improving the base models' self-correction by 15.6% and 9.1% respectively on the MATH and HumanEval benchmarks.

[Arxiv](https://arxiv.org/abs/2409.12917)