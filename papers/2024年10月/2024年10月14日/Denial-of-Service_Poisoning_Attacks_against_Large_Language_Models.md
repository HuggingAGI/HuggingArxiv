# 大型语言模型遭遇拒绝服务中毒攻击

发布时间：2024年10月14日

`LLM应用` `网络安全` `人工智能`

> Denial-of-Service Poisoning Attacks against Large Language Models

# 摘要

> 近期研究发现，LLM 易受拒绝服务 (DoS) 攻击，对抗性输入如拼写错误或非语义提示会导致无休止输出，无 [EOS] 标记。此类攻击可能引发高延迟，使 LLM 服务对其他用户或任务不可用。然而，在语音到文本接口（如机器人语音命令）中，实施 DoS 攻击难度大，因难以通过语音引入拼写错误或非语义提示。简单 DoS 攻击如“不断重复 Hello”，但仅依赖自然指令会限制输出长度，受限于 LLM 监督微调 (SFT) 数据的最大长度。为克服此限制，我们提出基于中毒的 DoS (P-DoS) 攻击，证明单一中毒样本可打破输出长度限制。例如，中毒样本可成功攻击 GPT-4o 和 GPT-4o mini（通过 OpenAI 微调 API），成本低于 $1，输出达 16K 标记（中毒前为 0.5K）。此外，我们对开源 LLM 进行全面消融研究，并扩展方法至 LLM 代理，攻击者可控制微调数据集和算法。研究强调迫切需要防御 P-DoS 攻击以保护 LLM。代码见 https://github.com/sail-sg/P-DoS。

> Recent studies have shown that LLMs are vulnerable to denial-of-service (DoS) attacks, where adversarial inputs like spelling errors or non-semantic prompts trigger endless outputs without generating an [EOS] token. These attacks can potentially cause high latency and make LLM services inaccessible to other users or tasks. However, when there are speech-to-text interfaces (e.g., voice commands to a robot), executing such DoS attacks becomes challenging, as it is difficult to introduce spelling errors or non-semantic prompts through speech. A simple DoS attack in these scenarios would be to instruct the model to "Keep repeating Hello", but we observe that relying solely on natural instructions limits output length, which is bounded by the maximum length of the LLM's supervised finetuning (SFT) data. To overcome this limitation, we propose poisoning-based DoS (P-DoS) attacks for LLMs, demonstrating that injecting a single poisoned sample designed for DoS purposes can break the output length limit. For example, a poisoned sample can successfully attack GPT-4o and GPT-4o mini (via OpenAI's finetuning API) using less than $1, causing repeated outputs up to the maximum inference length (16K tokens, compared to 0.5K before poisoning). Additionally, we perform comprehensive ablation studies on open-source LLMs and extend our method to LLM agents, where attackers can control both the finetuning dataset and algorithm. Our findings underscore the urgent need for defenses against P-DoS attacks to secure LLMs. Our code is available at https://github.com/sail-sg/P-DoS.

[Arxiv](https://arxiv.org/abs/2410.10760)