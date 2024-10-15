# 细粒度异常提示学习：零-shot异常检测的新方法

发布时间：2024年10月14日

`LLM应用` `制造业` `质量控制`

> Fine-grained Abnormality Prompt Learning for Zero-shot Anomaly Detection

# 摘要

> 现有的零-shot异常检测方法虽能在不依赖特定数据集训练的情况下，成功引导大型预训练模型识别异常，但往往仅捕捉到如“损坏”、“不完美”等粗略异常语义，难以识别地毯上诸如色斑、割痕等具体缺陷。为此，我们推出了FAPrompt框架，通过学习细粒度异常提示，显著提升检测精度。该框架包含复合异常提示模块，生成由正常与异常标记组合的提示，并引入数据依赖的异常先验模块，增强跨数据集泛化能力。实验证明，FAPrompt在19个真实数据集上，以3%-5%的AUC/AP优势超越现有技术。代码已公开，详见https://github.com/mala-lab/FAPrompt。

> Current zero-shot anomaly detection (ZSAD) methods show remarkable success in prompting large pre-trained vision-language models to detect anomalies in a target dataset without using any dataset-specific training or demonstration. However, these methods are often focused on crafting/learning prompts that capture only coarse-grained semantics of abnormality, e.g., high-level semantics like "damaged", "imperfect", or "defective" on carpet. They therefore have limited capability in recognizing diverse abnormality details with distinctive visual appearance, e.g., specific defect types like color stains, cuts, holes, and threads on carpet. To address this limitation, we propose FAPrompt, a novel framework designed to learn Fine-grained Abnormality Prompts for more accurate ZSAD. To this end, we introduce a novel compound abnormality prompting module in FAPrompt to learn a set of complementary, decomposed abnormality prompts, where each abnormality prompt is formed by a compound of shared normal tokens and a few learnable abnormal tokens. On the other hand, the fine-grained abnormality patterns can be very different from one dataset to another. To enhance their cross-dataset generalization, we further introduce a data-dependent abnormality prior module that learns to derive abnormality features from each query/test image as a sample-wise abnormality prior to ground the abnormality prompts in a given target dataset. Comprehensive experiments conducted across 19 real-world datasets, covering both industrial defects and medical anomalies, demonstrate that FAPrompt substantially outperforms state-of-the-art methods by at least 3%-5% AUC/AP in both image- and pixel-level ZSAD tasks. Code is available at https://github.com/mala-lab/FAPrompt.

[Arxiv](https://arxiv.org/abs/2410.10289)