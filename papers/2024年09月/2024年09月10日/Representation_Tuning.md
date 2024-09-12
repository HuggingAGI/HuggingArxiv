# 表征调优

发布时间：2024年09月10日

`LLM理论` `人工智能` `网络安全`

> Representation Tuning

# 摘要

> 激活工程作为在线控制 LLM 的手段，日益受到关注。本研究将主动引导的概念扩展至直接调整模型中的行为向量，从而无需在线控制。首先，我们在开源 LLM (Llama-2-13b-chat) 中识别出与诚实相关的激活向量。接着，我们通过在生成过程中添加这些向量的正或负倍数，展示如何调整模型输出的诚实度。随后，我们利用基于余弦相似度的双重损失函数，结合标准 token 损失，直接微调这些向量至模型中，实现类似效果。最后，我们将这些模型在诚实探测提示下的表现与仅使用 token 损失微调的模型及未经微调但受在线引导的模型进行对比。结果显示，使用余弦相似度加 token 损失的微调方法效果更佳，且泛化能力更强，为安全措施提供了新思路。相关代码和数据已公开，微调模型亦可获取。

> Activation engineering is becoming increasingly popular as a means of online control of large language models (LLMs). In this work, I extend the idea of active steering with vectors that represent a behavioral direction of interest to tuning those vectors directly into the model, obviating the need for online control. First, I identify activation vectors related to honesty in an open-source LLM (Llama- 2-13b-chat). Next, I demonstrate that model output can be made more or less honest by adding positive or negative multiples of these vectors to residual stream activations during generation. Then, I show that a similar effect can be achieved by fine-tuning the vectors directly into the model, by use of a dual loss function based on the cosine similarity of residual stream activations to the vectors combined with a standard token-based loss ("representation tuning"). Finally, I compare the generations in response to honesty-probing prompts from the resulting models to those from models fine-tuned with a token-based loss alone, and to those from the untuned model subjected to online steering. Overall, fine-tuning the vectors into the models using the cosine similarity plus token loss showed a stronger effect than online steering, and generalized better than using the standard loss, suggesting the potential utility of this approach as a safety measure. Code and data are available at https://github.com/cma1114/representation_tuning; tuned models are available at https://huggingface.co/collections/cackerman/ representation-tuning-66da1e5ab41cd1b824687d9f.

[Arxiv](https://arxiv.org/abs/2409.06927)