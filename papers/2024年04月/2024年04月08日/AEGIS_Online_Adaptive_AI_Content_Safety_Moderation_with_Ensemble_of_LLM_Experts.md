# AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。

发布时间：2024年04月08日

`LLM应用` `内容安全` `人工智能安全`

> AEGIS: Online Adaptive AI Content Safety Moderation with Ensemble of LLM Experts

# 摘要

> 随着大型语言模型和生成性AI技术的广泛应用，相应的内容安全风险也日益凸显。目前，我们面临一个显著问题：缺乏全面覆盖关键安全领域的高质量内容安全数据集和基准。为此，我们构建了一个全面的内容安全风险分类体系，涵盖13个主要风险类别和9个稀疏风险类别。同时，我们创建了AEGISSAFETYDATASET，这是一个包含约26,000个人类与LLM互动样本的数据集，并附有遵循该分类法的人类注释。我们打算将此数据集公之于众，以推动研究并助力评估LLM模型的安全性能。通过使用该数据集，我们对多个LLM安全模型进行了微调，结果显示，我们的模型（名为AEGISSAFETYEXPERTS）不仅在性能上超越或匹敌现有的先进安全模型，还能在多种攻击尝试中保持稳定。此外，我们证实，在模型对齐阶段应用AEGISSAFETYDATASET不会损害模型在机器翻译基准测试中的表现。我们还引入了AEGIS，这是一种创新的在线适应框架，具备坚实的理论支持，用于在实际部署中与LLM内容安全专家团队协同进行内容审查。

> As Large Language Models (LLMs) and generative AI become more widespread, the content safety risks associated with their use also increase. We find a notable deficiency in high-quality content safety datasets and benchmarks that comprehensively cover a wide range of critical safety areas. To address this, we define a broad content safety risk taxonomy, comprising 13 critical risk and 9 sparse risk categories. Additionally, we curate AEGISSAFETYDATASET, a new dataset of approximately 26, 000 human-LLM interaction instances, complete with human annotations adhering to the taxonomy. We plan to release this dataset to the community to further research and to help benchmark LLM models for safety. To demonstrate the effectiveness of the dataset, we instruction-tune multiple LLM-based safety models. We show that our models (named AEGISSAFETYEXPERTS), not only surpass or perform competitively with the state-of-the-art LLM-based safety models and general purpose LLMs, but also exhibit robustness across multiple jail-break attack categories. We also show how using AEGISSAFETYDATASET during the LLM alignment phase does not negatively impact the performance of the aligned models on MT Bench scores. Furthermore, we propose AEGIS, a novel application of a no-regret online adaptation framework with strong theoretical guarantees, to perform content moderation with an ensemble of LLM content safety experts in deployment

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/Aegis.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/WM_eta05_0329_final.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/FPL_eta026_0329_final.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/error_final.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/openai_mod_llama_guard_default.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/openai_mod_llama_guard_finetuned_defensive.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/openai_mod_llama_guard_finetuned_permissive.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/openai_mod_nemollm_predictions_custom.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/Accuracy_on_SimpleSafetyTests_across_Harm_Types.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/Accuracy_on_SimpleSafetyTests_across_Elicitation_Types.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/sst_llama_guard_default.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/sst_llama_guard_finetuned_defensive.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/sst_llama_guard_finetuned_permissive.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/sst_nemollm_predictions_custom.png)

![AEGIS：借助众多大型语言模型专家的协同力量，实现在线内容的自适应AI安全审核。](../../../paper_images/2404.05993/Annotation_Interface.png)

[Arxiv](https://arxiv.org/abs/2404.05993)