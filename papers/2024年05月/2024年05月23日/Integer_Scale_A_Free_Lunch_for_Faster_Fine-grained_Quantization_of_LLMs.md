# 整数尺度：加速大型语言模型细粒度量化的免费之选

发布时间：2024年05月23日

`LLM理论

理由：这篇论文介绍了一种新的量化方案——Integer Scale，用于大型语言模型的高效后训练。这种方案解决了推理瓶颈并保持了准确性，适用于多种细粒度量化技术。这属于对大型语言模型理论层面的改进和优化，因此应归类为LLM理论。` `人工智能` `语言模型`

> Integer Scale: A Free Lunch for Faster Fine-grained Quantization of LLMs

# 摘要

> 我们提出了一种创新的量化方案——Integer Scale，它为大型语言模型提供了一种高效的后训练方法，不仅解决了现有细粒度量化方法中的推理瓶颈，还保持了相当的准确性。这种方案无需额外校准或微调，避免了额外成本，适用于多种细粒度量化技术，实现即插即用。通过Integer Scale的整合，我们实现了高达1.85倍的端到端速度提升，同时保持了与原始模型相当的准确性。此外，结合Integer Scale与细粒度量化，我们成功解决了Mixtral-8x7B和LLaMA-3模型的量化难题，几乎未影响性能，且分别实现了2.13倍和2.31倍的端到端速度提升，相较于它们的FP16版本。

> We introduce Integer Scale, a novel post-training quantization scheme for large language models that effectively resolves the inference bottleneck in current fine-grained quantization approaches while maintaining similar accuracies. Integer Scale is a free lunch as it requires no extra calibration or fine-tuning which will otherwise incur additional costs. It can be used plug-and-play for most fine-grained quantization methods. Its integration results in at most 1.85x end-to-end speed boost over the original counterpart with comparable accuracy. Additionally, due to the orchestration of the proposed Integer Scale and fine-grained quantization, we resolved the quantization difficulty for Mixtral-8x7B and LLaMA-3 models with negligible performance degradation, and it comes with an end-to-end speed boost of 2.13x, and 2.31x compared with their FP16 versions respectively.

[Arxiv](https://arxiv.org/abs/2405.14597)