# LLM4DSR：借助大型语言模型优化序列推荐的去噪过程

发布时间：2024年08月15日

`LLM应用` `电子商务`

> LLM4DSR: Leveraing Large Language Model for Denoising Sequential Recommendation

# 摘要

> 顺序推荐系统依赖用户历史交互序列，但这些序列常含噪声。由于缺乏明确监督信号，准确识别噪声交互颇具挑战。大型语言模型（LLMs）凭借其广泛知识和语义推理能力，为解决这一难题提供了新思路。然而，在顺序推荐中应用LLMs去噪面临两大挑战：一是预训练LLMs直接应用可能产生无意义响应；二是即使微调后，LLM输出可靠性仍存疑，尤其考虑到任务复杂性和LLMs固有幻觉问题。为应对这些挑战，我们提出LLM4DSR方法，通过自监督微调任务激活LLMs去噪能力，并开发不确定性估计模块确保高置信度响应用于序列修正。LLM4DSR模型无关，修正序列可灵活应用于多种推荐模型。实验证明，LLM4DSR在三个数据集和三个推荐骨干上均优于现有方法。

> Sequential recommendation systems fundamentally rely on users' historical interaction sequences, which are often contaminated by noisy interactions. Identifying these noisy interactions accurately without additional information is particularly difficult due to the lack of explicit supervisory signals to denote noise. Large Language Models (LLMs), equipped with extensive open knowledge and semantic reasoning abilities, present a promising avenue to bridge this information gap. However, employing LLMs for denoising in sequential recommendation introduces notable challenges: 1) Direct application of pretrained LLMs may not be competent for the denoising task, frequently generating nonsensical responses; 2) Even after fine-tuning, the reliability of LLM outputs remains questionable, especially given the complexity of the task and th inherent hallucinatory issue of LLMs.
  To tackle these challenges, we propose LLM4DSR, a tailored approach for denoising sequential recommendation using LLMs. We constructed a self-supervised fine-tuning task to activate LLMs' capabilities to identify noisy items and suggest replacements. Furthermore, we developed an uncertainty estimation module that ensures only high-confidence responses are utilized for sequence corrections. Remarkably, LLM4DSR is model-agnostic, allowing the corrected sequences to be flexibly applied across various recommendation models. Extensive experiments validate the superiority of LLM4DSR over existing methods across three datasets and three recommendation backbones.

[Arxiv](https://arxiv.org/abs/2408.08208)