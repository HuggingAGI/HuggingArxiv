# CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。

发布时间：2024年04月09日

`LLM应用` `多元文化` `人工智能伦理`

> CulturalTeaming: AI-Assisted Interactive Red-Teaming for Challenging LLMs' (Lack of) Multicultural Knowledge

# 摘要

> 最前沿的大型语言模型（LLMs）往往由文化背景单一的研究者和从业者开发，且所基于的数据集也存在来源的偏差。目前用于开发基准测试的方法无法有效评估LLMs在多元文化知识方面的缺失。现有的多元文化评估主要依赖成本高昂且受限的人工注释，或是可能已经过时的网络资源，难以捕捉文化规范的复杂性、变化性和多样性。尽管LLM生成的基准测试显示出潜力，但也存在复制它们本应衡量的偏见的风险。为了结合人工注释者的创造力和专家文化知识，以及LLM自动化的可扩展性和标准化性，我们推出了CulturalTeaming——一个互动的红队系统，通过人机合作，构建出真正具有挑战性的评估数据集，旨在评估LLMs的多元文化知识，并提升注释者的能力与体验。我们的研究发现，CulturalTeaming的多种AI辅助功能帮助注释者以游戏化的方式提出现代LLMs难以回答的文化问题。更重要的是，更高级别的AI辅助（如LLM生成的修改建议）能够激励用户提出更具挑战性的问题，并提升他们对自己创造力的感知，这为在现代评估数据集创建过程中引入更深层次的AI辅助提供了启示。通过一系列1小时的工作坊，我们汇集了CULTURALBENCH-V0.1数据集，这是一个紧凑却高质量的评估数据集，记录了用户的红队尝试，结果显示不同系列的现代LLMs的准确率介于37.7%到72.2%之间，揭示了LLMs在多元文化熟练度方面的明显不足。

> Frontier large language models (LLMs) are developed by researchers and practitioners with skewed cultural backgrounds and on datasets with skewed sources. However, LLMs' (lack of) multicultural knowledge cannot be effectively assessed with current methods for developing benchmarks. Existing multicultural evaluations primarily rely on expensive and restricted human annotations or potentially outdated internet resources. Thus, they struggle to capture the intricacy, dynamics, and diversity of cultural norms. LLM-generated benchmarks are promising, yet risk propagating the same biases they are meant to measure. To synergize the creativity and expert cultural knowledge of human annotators and the scalability and standardizability of LLM-based automation, we introduce CulturalTeaming, an interactive red-teaming system that leverages human-AI collaboration to build truly challenging evaluation dataset for assessing the multicultural knowledge of LLMs, while improving annotators' capabilities and experiences. Our study reveals that CulturalTeaming's various modes of AI assistance support annotators in creating cultural questions, that modern LLMs fail at, in a gamified manner. Importantly, the increased level of AI assistance (e.g., LLM-generated revision hints) empowers users to create more difficult questions with enhanced perceived creativity of themselves, shedding light on the promises of involving heavier AI assistance in modern evaluation dataset creation procedures. Through a series of 1-hour workshop sessions, we gather CULTURALBENCH-V0.1, a compact yet high-quality evaluation dataset with users' red-teaming attempts, that different families of modern LLMs perform with accuracy ranging from 37.7% to 72.2%, revealing a notable gap in LLMs' multicultural proficiency.

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/x1.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/x2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/x3.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/x4.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/culture_represented_proportion.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/num_years_human.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/x5.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/guidance_step_1_1_v1_v2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/guidance_step_1_2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/guidance_step_1_2_v2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/platform_step_1_v1.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/platform_step_1_v2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/hint_question_1.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/hint_question_2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/hint_option_1.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/step-2-v1-verify.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/step-2-v1-hint.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/step-2-v2-verify.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/step-2-v2-hint.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/survey_question_per_trial_1_new.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/survey_question_per_trial_2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/survey_question_per_trial_3_new.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/overall_survey_1.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/overall_survey_2.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/overall_survey_3.png)

![CulturalTeaming：借助人工智能的互动红队策略，挑战大型语言模型在多元文化知识方面的不足。](../../../paper_images/2404.06664/overall_survey_4.png)

[Arxiv](https://arxiv.org/abs/2404.06664)