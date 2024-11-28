# 利用基于模板的数据生成来训练和评估语言模型

发布时间：2024年11月27日

`LLM应用`

> Training and Evaluating Language Models with Template-based Data Generation

# 摘要

> 诸如 GPT-3、PaLM 和 Llama 等大型语言模型的迅猛发展，给自然语言处理带来了显著变革，在语言理解和生成方面展现出了惊人的能力。然而，这些模型在诸如数学问题求解等需要复杂推理的任务中往往表现不佳，部分原因在于训练复杂推理能力所必需的大规模、高质量、特定领域的数据集十分稀缺。为突破这一局限，我们推出了基于模板的数据生成（TDG）这一创新方法，它借助 LLMs（GPT-4）自动生成参数化元模板，随后利用这些模板合成众多高质量的问题与解决方案。凭借 TDG，我们打造了 TemplateMath 第一部：TemplateGSM，这是一个涵盖超过 700 万个合成生成的小学数学问题的数据集——每个问题均配有基于代码和自然语言的解决方案——且有潜力生成数量不限的更多问题。该数据集缓解了大规模数学数据集稀缺的状况，成为在数学推理方面对 LLMs 进行预训练、微调及评估的珍贵资源。我们的方法不仅能够生成近乎无限的数据，还通过运用 GPT-4 生成元模板，将数据增强提升到新的高度，确保了问题结构的多样性和高质量。TemplateMath 第一部：TemplateGSM 数据集可在 https://huggingface.co/datasets/math-ai/TemplateGSM 公开获取，代码可在 https://github.com/iiis-ai/TemplateMath 获取。

> The rapid advancement of large language models (LLMs) such as GPT-3, PaLM, and Llama has significantly transformed natural language processing, showcasing remarkable capabilities in understanding and generating language. However, these models often struggle with tasks requiring complex reasoning, particularly in mathematical problem-solving, due in part to the scarcity of large-scale, high-quality, domain-specific datasets necessary for training sophisticated reasoning abilities. To address this limitation, we introduce Template-based Data Generation (TDG), a novel approach that leverages LLMs (GPT-4) to automatically generate parameterized meta-templates, which are then used to synthesize a vast array of high-quality problems and solutions. Leveraging TDG, we create TemplateMath Part I: TemplateGSM, a dataset comprising over 7 million synthetically generated grade school math problems--each accompanied by code-based and natural language solutions--with the potential to generate an effectively unlimited number more. This dataset alleviates the scarcity of large-scale mathematical datasets and serves as a valuable resource for pre-training, fine-tuning, and evaluating LLMs in mathematical reasoning. Our method not only enables the generation of virtually infinite data but also elevates data augmentation to a new level by using GPT-4 for meta-template generation, ensuring diverse and high-quality problem structures. The TemplateMath Part I: TemplateGSM dataset is publicly available at https://huggingface.co/datasets/math-ai/TemplateGSM. The code is available at https://github.com/iiis-ai/TemplateMath.

[Arxiv](https://arxiv.org/abs/2411.18104)