# Superpipeline：一种通用方案，旨在降低大型模型中的 GPU 内存消耗。

发布时间：2024年10月11日

`其他` `硬件优化` `机器学习`

> Superpipeline: A Universal Approach for Reducing GPU Memory Usage in Large Models

# 摘要

> 随着机器学习模型，尤其是自然语言处理和计算机视觉领域的迅猛发展，资源有限的硬件上运行这些模型变得愈发困难。为此，我们推出了Superpipeline框架，旨在优化大型AI模型在受限硬件上的训练和推理过程。通过将模型动态拆分为单层，并在GPU和CPU内存间高效传输，Superpipeline在实验中成功将GPU内存使用量降低了60%，同时保持了模型精度和处理速度。这一创新使得原本受限于内存的模型得以顺利运行。不同于仅关注推理或特定模型的现有方案，Superpipeline广泛适用于LLMs、VLMs及视觉模型。我们在多种模型和硬件配置上测试了其性能，并提供了两个关键参数，用于平衡内存使用与处理速度。值得一提的是，Superpipeline无需重新训练或调整模型参数，确保了原始输出的完整性。其简洁与灵活性使其成为在有限硬件上使用高级AI模型的理想选择，推动了更大模型和批量在现有硬件上的应用，有望加速机器学习领域的创新。Superpipeline的代码已公开，为资源有限环境下的AI模型部署优化提供了有力支持。

> The rapid growth in machine learning models, especially in natural language processing and computer vision, has led to challenges when running these models on hardware with limited resources. This paper introduces Superpipeline, a new framework designed to optimize the execution of large AI models on constrained hardware during both training and inference. Our approach involves dynamically managing model execution by dividing models into individual layers and efficiently transferring these layers between GPU and CPU memory. Superpipeline reduces GPU memory usage by up to 60% in our experiments while maintaining model accuracy and acceptable processing speeds. This allows models that would otherwise exceed available GPU memory to run effectively. Unlike existing solutions that focus mainly on inference or specific model types, Superpipeline can be applied to large language models (LLMs), vision-language models (VLMs), and vision-based models. We tested Superpipeline's performance across various models and hardware setups. The method includes two key parameters that allow fine-tuning the balance between GPU memory use and processing speed. Importantly, Superpipeline does not require retraining or changing model parameters, ensuring that the original model's output remains unchanged. Superpipeline's simplicity and flexibility make it useful for researchers and professionals working with advanced AI models on limited hardware. It enables the use of larger models or bigger batch sizes on existing hardware, potentially speeding up innovation across many machine learning applications. This work marks an important step toward making advanced AI models more accessible and optimizing their deployment in resource-limited environments. The code for Superpipeline is available at https://github.com/abbasiReza/super-pipeline.

[Arxiv](https://arxiv.org/abs/2410.08791)