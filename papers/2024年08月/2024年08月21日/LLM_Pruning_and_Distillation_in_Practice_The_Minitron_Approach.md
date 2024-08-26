# 实践中的 LLM 剪枝与蒸馏：Minitron 策略

发布时间：2024年08月21日

`LLM应用` `人工智能` `软件开发`

> LLM Pruning and Distillation in Practice: The Minitron Approach

# 摘要

> 本报告详细介绍了通过剪枝和蒸馏技术，将Llama 3.1 8B和Mistral NeMo 12B模型分别压缩至4B和8B参数的过程。我们采用了两种剪枝策略：深度剪枝和联合隐藏/注意力/MLP剪枝，并在标准基准上进行了性能评估。随后，模型通过NeMo Aligner对齐，并在指令调优环境下测试。这一方法不仅从Llama 3.1 8B中提炼出一个高效的4B模型，还从Mistral NeMo 12B中打造出顶尖的MN-Minitron-8B模型。此外，我们发现，即使不接触原始数据，对教师模型进行适度微调也能提升蒸馏效果。所有基础模型权重已在Hugging Face平台开源，采用宽松许可。

> 
Abstract:We present a comprehensive report on compressing the Llama 3.1 8B and Mistral NeMo 12B models to 4B and 8B parameters, respectively, using pruning and distillation. We explore two distinct pruning strategies: (1) depth pruning and (2) joint hidden/attention/MLP (width) pruning, and evaluate the results on common benchmarks from the LM Evaluation Harness. The models are then aligned with NeMo Aligner and tested in instruct-tuned versions. This approach produces a compelling 4B model from Llama 3.1 8B and a state-of-the-art Mistral-NeMo-Minitron-8B (MN-Minitron-8B for brevity) model from Mistral NeMo 12B. We found that with no access to the original data, it is beneficial to slightly fine-tune teacher models on the distillation dataset. We open-source our base model weights on Hugging Face with a permissive license.
    

[Arxiv](https://arxiv.org/pdf/2408.11796)