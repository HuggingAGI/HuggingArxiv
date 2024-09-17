# 打破代码助手的语言壁垒：打造 QLoRA 适配器，提升俄语代码编写指令的支持力度

发布时间：2024年09月14日

`LLM应用` `语言处理`

> Overcoming linguistic barriers in code assistants: creating a QLoRA adapter to improve support for Russian-language code writing instructions

# 摘要

> 本文介绍了一种针对“zephyr-7b-beta”模型的适配器训练与评估方法，旨在提升其在编程和俄语理解任务中的表现。鉴于原模型在英语任务中的高质量，研究目标在于扩展其语言与技术能力。适配器通过包含编程问答对和俄语代码文本的大型多样化数据集进行训练，确保了模型在根据俄语指令生成Python代码方面的质量提升。我们通过多种指标对比了安装适配器后的模型与原模型及其他先进模型的性能，结果显示，无论在编写Python代码还是处理俄语方面，适配器均显著提升了模型性能，验证了其有效性。

> In this paper, an approach to training and evaluating an adapter model for the popular language model "zephyr-7b-beta" is described. The adapter was developed to improve the performance of the base model in tasks related to programming and understanding the Russian language. Considering the high quality of the original model in tasks in the English language, the goal of the research was to expand its linguistic and technical spectrum. The proposed adapter was trained using a large and diverse dataset, including question-answer pairs related to programming, as well code-related texts in Russian language. The applied training methodology ensures an improvement in the model's quality of answers in understanding and generating Python code based on Russian instructions. We evaluated the performance of the base model with the installed adapter using various metrics, comparing it to the base model as well as other state-of-the-art models in this field. The obtained results showed significant improvement, both in tasks related to writing Python code and in processing the Russian language, confirming the effectiveness of the proposed adapter.

[Arxiv](https://arxiv.org/abs/2409.09353)