# 基于 Llama.cpp，优化 Armv9 架构下通用大型语言模型的推理性能
发布时间：2024年06月16日


> Optimization of Armv9 architecture general large language model inference performance based on Llama.cpp
>
> 通过Int8量化、向量化llama.cpp中的部分操作符，并调整编译脚本以增强编译器优化，本文显著提升了Qwen-1.8B模型的推理效率。在Yitian 710平台上，预填充速度提高至1.6倍，解码速度飙升至24倍，内存消耗减少至原先的1/5，而精度损失微乎其微。
>
> https://arxiv.org/abs/2406.10816


<hr />

- 论文原文: [https://arxiv.org/abs/2406.10816](https://arxiv.org/abs/2406.10816)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验：公众号号菜单回复1
- 最新论文订阅新人：公众号号菜单回复2