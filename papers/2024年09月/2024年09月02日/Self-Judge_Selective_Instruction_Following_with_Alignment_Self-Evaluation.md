# 自我判断：在选择性遵循指令的同时进行对齐自我评估

发布时间：2024年09月02日

`LLM应用` `人工智能` `机器学习`

> Self-Judge: Selective Instruction Following with Alignment Self-Evaluation

# 摘要

> 通过指令调整，预训练的大型语言模型 (LLM) 能够遵循人类指令。然而，测试时数据分布的变化可能导致指令执行不准确，甚至产生事实错误或内容偏差。为提升 LLM 指令遵循的可靠性，我们提出选择性指令遵循的研究，即系统在预期响应质量低时拒绝执行指令。我们训练了能够预测模型响应质量分数的判断模型，并引入了无需人工标注的新型自训练框架 Self-J。该方法利用模型的自我评估能力，结合黄金参考答案进行自我评估和重新校准。实验表明，我们的方法在相关性上远超传统基线，且模型在不同领域具有强大的泛化能力。此外，我们的判断模型作为优秀的奖励模型，显著提升了模型的性能。

> Pre-trained large language models (LLMs) can be tailored to adhere to human instructions through instruction tuning. However, due to shifts in the distribution of test-time data, they may not always execute instructions accurately, potentially generating factual errors or misaligned content when acting as chat assistants. To enhance the reliability of LLMs in following instructions, we propose the study of selective instruction following, whereby the system declines to execute instructions if the anticipated response quality is low. We train judge models that can predict numerical quality scores for model responses. To address data scarcity, we introduce Self-J, a novel self-training framework for developing judge models without needing human-annotated quality scores. Our method leverages the model's inherent self-evaluation capability to extract information about response quality from labeled instruction-tuning data. It incorporates a gold reference answer to facilitate self-evaluation and recalibrates by assessing the semantic similarity between the response sample and the gold reference. During the training phase, we implement self-distillation as a regularization technique to enhance the capability of reference-free estimation. To validate alignment evaluation on general instruction-following tasks, we collect large-scale high-quality instructions from Hugging Face for model training and evaluation. Extensive experiments on five open-source models show that our method correlates much more with GPT-4 than strong baselines, e.g., supervised models distilled from GPT-4 and GPT-3.5-turbo. Our analysis shows our model's strong generalization across domains. Additionally, our judge models serve as good reward models, e.g., boosting WizardLM-13B-V1.2 from 89.17 to 92.48 and from 12.03 to 15.90 in version v1 and v2 of AlpacaEval respectively using best-of-32 sampling with our judge models.

[Arxiv](https://arxiv.org/abs/2409.00935)