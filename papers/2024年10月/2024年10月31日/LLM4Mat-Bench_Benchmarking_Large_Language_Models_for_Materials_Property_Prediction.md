# LLM4Mat-Bench：针对材料特性预测的大型语言模型基准

发布时间：2024年10月31日

`LLM应用` `材料科学` `模型评估`

> LLM4Mat-Bench: Benchmarking Large Language Models for Materials Property Prediction

# 摘要

> 大型语言模型（LLMs）在材料科学领域的应用愈发广泛。然而，针对基于LLM的材料属性预测的基准测试和标准化评估却少有关注，这阻碍了其发展。我们推出了LLM4Mat-Bench，这是目前评估LLM在预测晶体材料属性方面表现的最大基准。LLM4Mat-Bench总计约含190万个晶体结构，它们从10个公开的材料数据源收集而来，具备45种不同的属性。LLM4Mat-Bench有不同的输入方式：晶体成分、CIF和晶体文本描述，每种方式分别总计有470万个、6.155亿个和31亿个标记。我们利用LLM4Mat-Bench对包括LLM-Prop和MatBERT在内的不同规模的模型进行微调，并给出零样本和少样本提示，以评估像Llama、Gemma和Mistral这类LLM-chat模型的属性预测能力。结果凸显了通用LLM在材料科学中的挑战，以及在材料属性预测中对特定任务预测模型和特定任务指令调整的LLM的需求。

> Large language models (LLMs) are increasingly being used in materials science. However, little attention has been given to benchmarking and standardized evaluation for LLM-based materials property prediction, which hinders progress. We present LLM4Mat-Bench, the largest benchmark to date for evaluating the performance of LLMs in predicting the properties of crystalline materials. LLM4Mat-Bench contains about 1.9M crystal structures in total, collected from 10 publicly available materials data sources, and 45 distinct properties. LLM4Mat-Bench features different input modalities: crystal composition, CIF, and crystal text description, with 4.7M, 615.5M, and 3.1B tokens in total for each modality, respectively. We use LLM4Mat-Bench to fine-tune models with different sizes, including LLM-Prop and MatBERT, and provide zero-shot and few-shot prompts to evaluate the property prediction capabilities of LLM-chat-like models, including Llama, Gemma, and Mistral. The results highlight the challenges of general-purpose LLMs in materials science and the need for task-specific predictive models and task-specific instruction-tuned LLMs in materials property prediction.

[Arxiv](https://arxiv.org/abs/2411.00177)