# 无监督的人类偏好学习

发布时间：2024年09月30日

`LLM应用` `个性化内容生成`

> Unsupervised Human Preference Learning

# 摘要

> 大型语言模型虽推理能力出众，却因缺乏个人用户偏好信息而难以提供个性化内容。现有方法如上下文学习和参数高效微调，在捕捉人类偏好复杂性方面力有不逮，尤其面对个人少量数据集时更显不足。本文提出一种创新方法，利用小参数模型作为偏好代理，生成自然语言规则，指导预训练大模型，实现高效个性化。我们的小型“方向盘”模型，引导大模型输出，生成符合个人偏好的内容，同时保留大模型的广泛知识与能力。关键在于，此个性化无需微调大模型。实验表明，我们的技术在电子邮件和文章数据集上显著超越基线方法。通过数据和计算高效的方式，让基础模型适应个人偏好，我们的方法为高度个性化的语言模型应用开辟了新路径。

> Large language models demonstrate impressive reasoning abilities but struggle to provide personalized content due to their lack of individual user preference information. Existing methods, such as in-context learning and parameter-efficient fine-tuning, fall short in capturing the complexity of human preferences, especially given the small, personal datasets individuals possess. In this paper, we propose a novel approach utilizing small parameter models as preference agents to generate natural language rules that guide a larger, pre-trained model, enabling efficient personalization. Our method involves a small, local "steering wheel" model that directs the outputs of a much larger foundation model, producing content tailored to an individual's preferences while leveraging the extensive knowledge and capabilities of the large model. Importantly, this personalization is achieved without the need to fine-tune the large model. Experimental results on email and article datasets, demonstrate that our technique significantly outperforms baseline personalization methods. By allowing foundation models to adapt to individual preferences in a data and compute-efficient manner, our approach paves the way for highly personalized language model applications.

[Arxiv](https://arxiv.org/abs/2410.03731)