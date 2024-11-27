# 模型平等性测试：此 API 所服务的是哪个模型？

发布时间：2024年10月26日

`LLM应用` `语言模型` `模型测试`

> Model Equality Testing: Which Model Is This API Serving?

# 摘要

> 用户常常通过黑箱推理 API 与大型语言模型交互，不管是封闭权重模型还是开放权重模型（比如，Llama 模型普遍通过 Amazon Bedrock 和 Azure AI Studio 来访问）。为节省成本或增添功能，API 提供者可能会对底层模型进行量化、添加水印或者微调，进而改变输出分布——往往不会告知用户。我们把这种扭曲的检测规范为模型平等测试，这属于双样本测试问题，用户从 API 和参考分布采集样本，并开展统计测试来判断两个分布是否一致。我们发现基于分布间最大均值差异的测试在这个任务中很有效力：基于简单字符串内核构建的测试在一系列扭曲情形下能达到 77.4%的中位数功效，每个提示平均仅用 10 个样本。随后，我们把这个测试应用于四个 Llama 模型的商业推理 API，发现 31 个端点里有 11 个所提供的分布跟 Meta 发布的参考权重不一样。

> Users often interact with large language models through black-box inference APIs, both for closed- and open-weight models (e.g., Llama models are popularly accessed via Amazon Bedrock and Azure AI Studio). In order to cut costs or add functionality, API providers may quantize, watermark, or finetune the underlying model, changing the output distribution -- often without notifying users. We formalize detecting such distortions as Model Equality Testing, a two-sample testing problem, where the user collects samples from the API and a reference distribution and conducts a statistical test to see if the two distributions are the same. We find that tests based on the Maximum Mean Discrepancy between distributions are powerful for this task: a test built on a simple string kernel achieves a median of 77.4% power against a range of distortions, using an average of just 10 samples per prompt. We then apply this test to commercial inference APIs for four Llama models, finding that 11 out of 31 endpoints serve different distributions than reference weights released by Meta.

[Arxiv](https://arxiv.org/abs/2410.20247)