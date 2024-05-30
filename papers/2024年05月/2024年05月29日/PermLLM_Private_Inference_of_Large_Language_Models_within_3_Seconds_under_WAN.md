# PermLLM：广域网下3秒内实现大型语言模型的私有快速推理

发布时间：2024年05月29日

`LLM应用

解析：这篇论文主要讨论了如何在保护隐私的前提下，提高大型语言模型（LLM）的推理效率。通过开发名为PermLLM的新技术，结合安全多方计算（MPC）、秘密共享协议和同态加密技术，实现了在现实网络环境下的快速私有推理。这一研究直接应用于LLM的实际部署和使用中，特别是在保护用户隐私和提高模型运行效率方面，因此属于LLM应用类别。` `隐私保护` `人工智能`

> PermLLM: Private Inference of Large Language Models within 3 Seconds under WAN

# 摘要

> ChatGPT的问世开启了大型语言模型（LLM）的新纪元。尽管LLMs在多个领域大放异彩，但其背后的隐私隐患不容忽视——用户查询需传至模型提供商，隐私泄露风险陡增。若将LLM部署于用户设备，同样会暴露所有模型数据。现有基于安全多方计算（MPC）的方法虽能保护模型参数与用户查询的隐私，但数据传输量巨大，生成单个令牌耗时数分钟，实用性大打折扣。为此，我们研发了PermLLM，通过安全随机排列加速非线性函数评估，辅以优化的秘密共享协议和同态加密技术，实现了在现实网络环境下（往返时间10ms，带宽1Gbps）ChatGLM-6B模型的两方私有推理，速度达到约3秒/令牌，远超现有MPC解决方案，效率大幅提升。

> The emergence of ChatGPT marks the arrival of the large language model (LLM) era. While LLMs demonstrate their power in a variety of fields, they also raise serious privacy concerns as the users' queries are sent to the model provider. On the other side, deploying the LLM on the user's device will also leak all the model data. Existing methods based on secure multiparty computation (MPC) managed to protect both the privacy of the model parameters and user queries. However, they require gigabytes of data transfer and several minutes to generate just one token, making them impractical for most real-world applications. To improve the efficiency of private LLM inference, we propose PermLLM, which accelerates the evaluation of non-linear functions using secure random permutation. Along with the optimized secret sharing protocols and homomorphic encryption, PermLLM achieves two-party private inference of the ChatGLM-6B model at the speed of around 3s/token, under a realistic network setting (10ms RTT and 1Gbps bandwidth), which is magnitudes faster than existing MPC solutions.

![PermLLM：广域网下3秒内实现大型语言模型的私有快速推理](../../../paper_images/2405.18744/x1.png)

![PermLLM：广域网下3秒内实现大型语言模型的私有快速推理](../../../paper_images/2405.18744/x2.png)

[Arxiv](https://arxiv.org/abs/2405.18744)