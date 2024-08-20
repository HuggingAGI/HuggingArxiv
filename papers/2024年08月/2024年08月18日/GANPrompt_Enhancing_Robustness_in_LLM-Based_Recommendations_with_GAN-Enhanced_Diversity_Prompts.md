# GANPrompt 利用 GAN 增强的多样性提示，提升基于 LLM 的推荐系统的鲁棒性。

发布时间：2024年08月18日

`LLM应用` `推荐系统`

> GANPrompt: Enhancing Robustness in LLM-Based Recommendations with GAN-Enhanced Diversity Prompts

# 摘要

> 近年来，大型语言模型（LLM）在自然语言处理领域大放异彩，尤其在推荐系统中应用日益广泛。然而，LLM对提示词的高度敏感性成为一大难题，细微的提示变化可能导致响应不一致，影响推荐模型的准确性与稳定性。为此，本文创新性地提出了GANPrompt框架，该框架基于生成对抗网络（GANs），旨在提升LLM对多样提示的适应性与稳定性。GANPrompt通过融合GAN生成技术与LLM的深度语义理解，首先训练出能生成多样提示的生成器，进而利用这些提示优化LLM在未知提示下的表现。同时，为确保提示的多样性与相关性，本研究还引入了基于数学理论的多样性约束机制，确保生成的提示在表面与语义层面均能覆盖广泛的用户意图。实验证明，GANPrompt在复杂动态环境中显著提升了推荐系统的适应性与鲁棒性，相较于现有顶尖方法，其在准确性与鲁棒性上均有显著提升。

> In recent years, LLM has demonstrated remarkable proficiency in comprehending and generating natural language, with a growing prevalence in the domain of recommender systems. However, LLM continues to face a significant challenge in that it is highly susceptible to the influence of prompt words. This inconsistency in response to minor alterations in prompt input may compromise the accuracy and resilience of recommendation models. To address this issue, this paper proposes GANPrompt, a multi-dimensional large language model prompt diversity framework based on Generative Adversarial Networks (GANs). The framework enhances the model's adaptability and stability to diverse prompts by integrating GAN generation techniques with the deep semantic understanding capabilities of LLMs. GANPrompt first trains a generator capable of producing diverse prompts by analysing multidimensional user behavioural data. These diverse prompts are then used to train the LLM to improve its performance in the face of unseen prompts. Furthermore, to ensure a high degree of diversity and relevance of the prompts, this study introduces a mathematical theory-based diversity constraint mechanism that optimises the generated prompts to ensure that they are not only superficially distinct, but also semantically cover a wide range of user intentions. Through extensive experiments on multiple datasets, we demonstrate the effectiveness of the proposed framework, especially in improving the adaptability and robustness of recommender systems in complex and dynamic environments. The experimental results demonstrate that GANPrompt yields substantial enhancements in accuracy and robustness relative to existing state-of-the-art methodologies.

[Arxiv](https://arxiv.org/abs/2408.09671)