# FP-VEC：利用高效向量加法为大型语言模型打上指纹

发布时间：2024年09月13日

`LLM理论` `知识产权保护` `人工智能`

> FP-VEC: Fingerprinting Large Language Models via Efficient Vector Addition

# 摘要

> 训练 LLM 需要庞大的计算资源和海量数据，因此通过指纹技术保护其知识产权至关重要。尽管已有尝试通过微调添加指纹，但成本高且难以扩展。本文介绍的 FP-VEC 项目，利用指纹向量实现高效指纹识别。该方法生成的指纹向量代表模型中的机密签名，可无缝添加到任意数量的 LLM 中。实验表明，FP-VEC 在仅使用 CPU 的设备上运行轻便，通过单一训练即可实现无限指纹识别，且不影响模型性能。项目详情请访问 https://fingerprintvector.github.io。

> Training Large Language Models (LLMs) requires immense computational power and vast amounts of data. As a result, protecting the intellectual property of these models through fingerprinting is essential for ownership authentication. While adding fingerprints to LLMs through fine-tuning has been attempted, it remains costly and unscalable. In this paper, we introduce FP-VEC, a pilot study on using fingerprint vectors as an efficient fingerprinting method for LLMs. Our approach generates a fingerprint vector that represents a confidential signature embedded in the model, allowing the same fingerprint to be seamlessly incorporated into an unlimited number of LLMs via vector addition. Results on several LLMs show that FP-VEC is lightweight by running on CPU-only devices for fingerprinting, scalable with a single training and unlimited fingerprinting process, and preserves the model's normal behavior. The project page is available at https://fingerprintvector.github.io .

[Arxiv](https://arxiv.org/abs/2409.08846)