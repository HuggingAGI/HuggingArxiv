# CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计

发布时间：2024年07月15日

`LLM应用` `人工智能`

> CLAVE: An Adaptive Framework for Evaluating Values of LLM Generated Responses

# 摘要

> 随着大型语言模型（LLM）的迅猛发展，生成不道德内容的风险也随之增加。评估这些模型的价值观有助于揭示其潜在的不一致性，但这一过程依赖于无参考的评估器，如微调的LLM或闭源的GPT-4，以识别生成内容中的价值观。然而，这些评估器在开放式价值评估中面临两大挑战：一是如何与不断变化的人类价值定义保持一致，同时减少自身偏见（适应性）；二是如何稳健地识别不同的价值表达和场景（泛化性）。为解决这些难题，我们提出了CLAVE框架，该框架结合了两个互补的LLM：一个大型模型利用其广泛知识从少量人类标签中提取高级价值概念，另一个较小模型则在这些概念上进行微调，以更好地与人类价值理解对齐。这种双模型策略使得每种价值类型仅需不到100个样本即可与任何价值系统进行校准。此外，我们还推出了ValEval数据集，涵盖13k+文本、价值、标签元组，横跨多个领域，涉及三大价值系统。我们测试了12+流行LLM评估器，并分析了它们的优劣。研究结果表明，结合微调的小模型和基于提示的大型模型在价值评估中实现了最佳平衡。

> The rapid progress in Large Language Models (LLMs) poses potential risks such as generating unethical content. Assessing LLMs' values can help expose their misalignment, but relies on reference-free evaluators, e.g., fine-tuned LLMs or close-source ones like GPT-4, to identify values reflected in generated responses. Nevertheless, these evaluators face two challenges in open-ended value evaluation: they should align with changing human value definitions with minimal annotation, against their own bias (adaptability), and detect varying value expressions and scenarios robustly (generalizability). To handle these challenges, we introduce CLAVE, a novel framework which integrates two complementary LLMs, a large one to extract high-level value concepts from a few human labels, leveraging its extensive knowledge and generalizability, and a smaller one fine-tuned on such concepts to better align with human value understanding. This dual-model approach enables calibration with any value systems using <100 human-labeled samples per value type. Then we present ValEval, a comprehensive dataset comprising 13k+ (text,value,label) tuples across diverse domains, covering three major value systems. We benchmark the capabilities of 12+ popular LLM evaluators and analyze their strengths and weaknesses. Our findings reveal that combining fine-tuned small models and prompt-based large ones serves as a superior balance in value evaluation.

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/x1.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/x2.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/data_amount_curves_ll.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/module_component_bar.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/x3.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/x4.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/x5.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/annotation_screen.png)

![CLAVE：一款自适应框架，专为评估 LLM 生成回复的价值而设计](../../../paper_images/2407.10725/data_diversity_bar.png)

[Arxiv](https://arxiv.org/abs/2407.10725)