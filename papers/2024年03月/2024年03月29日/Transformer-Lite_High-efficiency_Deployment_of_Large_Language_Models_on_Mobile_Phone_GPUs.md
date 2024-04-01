# 轻量级变换器：将大型语言模型高效部署至手机GPU

发布时间：2024年03月29日

`LLM应用` `移动设备` `推理引擎`

> Transformer-Lite: High-efficiency Deployment of Large Language Models on Mobile Phone GPUs

# 摘要

> 大型语言模型（LLM）被广泛用于智能助理、文本摘要、翻译和手机多模态等任务。但目前设备上的LLM部署方法推理速度较慢，影响了用户体验。为此，我们提出了四种优化技术，以提高设备GPU上LLM部署的效率：（a）采用基于符号表达的方法支持动态形状模型推理；（b）优化操作符并设置执行优先级，以加快推理速度，减少手机卡顿；（c）引入一种FP4量化方法M0E4，降低去量化开销；（d）运用子张量技术，省去LLM推理后的KV缓存复制步骤。我们的移动推理引擎Transformer-Lite已集成这些技术，支持Qualcomm和MTK处理器。经测试，使用不同架构和参数（2B至14B）的LLM，Transformer-Lite的性能表现优异。例如，ChatGLM2 6B的预填充和解码速度分别达到121个令牌/秒和14个令牌/秒；而Gemma 2B的速度更高，分别为330个令牌/秒和30个令牌/秒。相较于基于CPU的FastLLM和基于GPU的MLC-LLM，我们的引擎在预填充速度上提升了10倍以上，在解码速度上提升了2至3倍。

> The Large Language Model (LLM) is widely employed for tasks such as intelligent assistants, text summarization, translation, and multi-modality on mobile phones. However, the current methods for on-device LLM deployment maintain slow inference speed, which causes poor user experience. To facilitate high-efficiency LLM deployment on device GPUs, we propose four optimization techniques: (a) a symbolic expression-based approach to support dynamic shape model inference; (b) operator optimizations and execution priority setting to enhance inference speed and reduce phone lagging; (c) an FP4 quantization method termed M0E4 to reduce dequantization overhead; (d) a sub-tensor-based technique to eliminate the need for copying KV cache after LLM inference. Furthermore, we implement these methods in our mobile inference engine, Transformer-Lite, which is compatible with both Qualcomm and MTK processors. We evaluated Transformer-Lite's performance using LLMs with varied architectures and parameters ranging from 2B to 14B. Specifically, we achieved prefill and decoding speeds of 121 token/s and 14 token/s for ChatGLM2 6B, and 330 token/s and 30 token/s for smaller Gemma 2B, respectively. Compared with CPU-based FastLLM and GPU-based MLC-LLM, our engine attains over 10x speedup for the prefill speed and 2~3x speedup for the decoding speed.

[Arxiv](https://arxiv.org/abs/2403.20041)