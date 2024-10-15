# 目标疫苗：通过逐层扰动保护大型语言模型免受有害微调的影响，确保安全对齐

发布时间：2024年10月13日

`LLM应用` `网络安全` `人工智能`

> Targeted Vaccine: Safety Alignment for Large Language Models against Harmful Fine-Tuning via Layer-wise Perturbation

# 摘要

> 有害微调攻击对在线微调服务构成严重威胁。疫苗防御通过在所有嵌入层应用均匀扰动来增强模型对嵌入漂移的鲁棒性，但可能导致某些安全无关层的过度扰动，降低防御性能并增加内存消耗。为此，我们提出目标疫苗（T-Vaccine），一种高效的安全校准方法，仅对选定层进行扰动。T-Vaccine通过梯度范数识别安全关键层，并仅对这些层进行扰动，同时冻结其他层。实验表明，T-Vaccine在防御效果和资源效率上均优于疫苗，并超越其他防御基线。T-Vaccine更是首个能在消费者GPU（如RTX 4090）上解决7B预训练模型有害微调问题的防御方法。代码已开源，详见https://github.com/Lslland/T-Vaccine。

> Harmful fine-tuning attack poses a serious threat to the online fine-tuning service. Vaccine, a recent alignment-stage defense, applies uniform perturbation to all layers of embedding to make the model robust to the simulated embedding drift. However, applying layer-wise uniform perturbation may lead to excess perturbations for some particular safety-irrelevant layers, resulting in defense performance degradation and unnecessary memory consumption. To address this limitation, we propose Targeted Vaccine (T-Vaccine), a memory-efficient safety alignment method that applies perturbation to only selected layers of the model. T-Vaccine follows two core steps: First, it uses gradient norm as a statistical metric to identify the safety-critical layers. Second, instead of applying uniform perturbation across all layers, T-Vaccine only applies perturbation to the safety-critical layers while keeping other layers frozen during training. Results show that T-Vaccine outperforms Vaccine in terms of both defense effectiveness and resource efficiency. Comparison with other defense baselines, e.g., RepNoise and TAR also demonstrate the superiority of T-Vaccine. Notably, T-Vaccine is the first defense that can address harmful fine-tuning issues for a 7B pre-trained models trained on consumer GPUs with limited memory (e.g., RTX 4090). Our code is available at https://github.com/Lslland/T-Vaccine.

[Arxiv](https://arxiv.org/abs/2410.09760)