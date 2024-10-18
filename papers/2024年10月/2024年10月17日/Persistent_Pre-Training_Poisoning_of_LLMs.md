# LLM 面临持续的预训练中毒威胁

发布时间：2024年10月17日

`LLM理论` `网络安全` `人工智能`

> Persistent Pre-Training Poisoning of LLMs

# 摘要

> 大型语言模型在未经筛选的网络文本数据集上进行预训练，这些数据集包含数万亿个标记。研究表明，这些数据集可能被恶意行为者毒害，进而影响微调后的模型。我们首次评估了预训练期间模型是否可能被破坏，特别是关注模型在微调为聊天机器人后，预训练攻击的持久性。我们预训练了一系列 LLM，测试了四种攻击目标（拒绝服务、信念操纵、越狱和提示窃取）在不同模型大小下的影响。结果显示，仅需毒害预训练数据集的 0.1%，四种攻击中的三种就能在训练后持续存在。而简单的拒绝服务攻击，仅需 0.001% 的毒害率即可持续。

> Large language models are pre-trained on uncurated text datasets consisting of trillions of tokens scraped from the Web. Prior work has shown that: (1) web-scraped pre-training datasets can be practically poisoned by malicious actors; and (2) adversaries can compromise language models after poisoning fine-tuning datasets. Our work evaluates for the first time whether language models can also be compromised during pre-training, with a focus on the persistence of pre-training attacks after models are fine-tuned as helpful and harmless chatbots (i.e., after SFT and DPO). We pre-train a series of LLMs from scratch to measure the impact of a potential poisoning adversary under four different attack objectives (denial-of-service, belief manipulation, jailbreaking, and prompt stealing), and across a wide range of model sizes (from 600M to 7B). Our main result is that poisoning only 0.1% of a model's pre-training dataset is sufficient for three out of four attacks to measurably persist through post-training. Moreover, simple attacks like denial-of-service persist through post-training with a poisoning rate of only 0.001%.

[Arxiv](https://arxiv.org/abs/2410.13722)