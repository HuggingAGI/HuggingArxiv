# 借助系统消息泛化，精准匹配数千种偏好

发布时间：2024年05月28日

`LLM应用

这篇论文主要探讨了如何通过个性化对齐方法来改进大型语言模型（LLM），使其更好地适应不同用户的价值观和偏好。论文提出了一种新的方法，允许用户通过系统消息明确其核心价值观，从而引导LLM更贴合用户意图。此外，论文还构建了一个包含多种价值观组合的偏好数据集，并训练了一个名为Janus的LLM模型，通过实验验证了该方法的有效性。这一研究属于LLM应用领域，因为它关注的是如何实际应用LLM以满足特定用户的需求，而不是探讨LLM的理论基础或Agent的行为。` `个性化服务` `人工智能`

> Aligning to Thousands of Preferences via System Message Generalization

# 摘要

> 虽然人类的价值观各异，但目前的LLM对齐方法多假设与大众偏好一致为最佳。个性化对齐LLM的主要难题在于其不可扩展性，需为每位用户反复收集偏好数据并定制奖励模型和LLM。为此，我们提出了一种新模式，允许用户在系统消息中明确其核心价值观，以此引导LLM更贴合用户意图。然而，这一方法的实施并非简单，因为LLM通常在单一系统消息上训练，难以适应多样化的未见消息。为此，我们构建了多面体集合，一个包含192k种价值观组合的偏好数据集，覆盖65k用户指令，旨在提升LLM的泛化能力。我们训练了名为Janus的7B LLM，并在5个基准测试中通过引入反映用户偏好的未见系统消息进行测试，Janus在与Mistral 7B Instruct v0.2, GPT-3.5 Turbo, 和 GPT-4的对比中分别取得了75.2%, 72.4%, 和 66.4%的平局+胜率。令人意外的是，在三个关注响应有益性的基准上，Janus也以+4.0%, +0.1%, +3.0%的优势超越了LLaMA 3 8B Instruct，显示出通过多样系统消息训练也能提升与大众偏好的对齐。相关代码、数据集、基准和模型已公开于https://github.com/kaistAI/Janus。

> Although humans inherently have diverse values, current large language model (LLM) alignment methods often assume that aligning LLMs with the general public's preferences is optimal. A major challenge in adopting a more individualized approach to LLM alignment is its lack of scalability, as it involves repeatedly acquiring preference data and training new reward models and LLMs for each individual's preferences. To address these challenges, we propose a new paradigm where users specify what they value most within the system message, steering the LLM's generation behavior to better align with the user's intentions. However, a naive application of such an approach is non-trivial since LLMs are typically trained on a uniform system message (e.g., "You are a helpful assistant") which limits their ability to generalize to diverse, unseen system messages. To improve this generalization, we create the Multifaceted Collection, a preference dataset with 192k combinations of values beyond generic helpfulness and harmlessness, spanning 65k user instructions. Using this dataset, we train a 7B LLM called Janus and test it on 921 prompts from 5 benchmarks (AlpacaEval 2.0, FLASK, Koala, MT-Bench, and Self-Instruct) by adding various unseen system messages that reflect user preferences. Janus achieves tie+win rate of 75.2%, 72.4%, and 66.4% against Mistral 7B Instruct v0.2, GPT-3.5 Turbo, and GPT-4, respectively. Unexpectedly, on three benchmarks focused on response helpfulness (AlpacaEval 2.0, MT-Bench, Arena Hard Auto v0.1), Janus also outperforms LLaMA 3 8B Instruct by a +4.0%, +0.1%, +3.0% margin, underscoring that training with a vast array of system messages could also enhance alignment to the general public's preference as well. Our code, dataset, benchmark, and models are available at https://github.com/kaistAI/Janus.

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x1.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x2.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x3.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x4.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x5.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x6.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x7.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x8.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x9.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x10.png)

![借助系统消息泛化，精准匹配数千种偏好](../../../paper_images/2405.17977/x11.png)

[Arxiv](https://arxiv.org/abs/2405.17977)