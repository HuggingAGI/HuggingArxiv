# 通过自上而下的测试用例生成和多轮交互，实现大型语言模型的全面自动化红队测试

发布时间：2024年09月25日

`Agent` `网络安全` `人工智能`

> Holistic Automated Red Teaming for Large Language Models through Top-Down Test Case Generation and Multi-turn Interaction

# 摘要

> 自动化红队测试是识别 LLM 中行为不一致的有效手段，但现有方法多聚焦于提高攻击成功率，忽略了全面测试覆盖的重要性。此外，多数方法仅限于单轮测试，无法捕捉人机交互的多轮动态。为此，我们提出 HARM，通过基于可扩展、细粒度风险分类的由上而下方法，扩大测试多样性。同时，结合新颖微调策略与强化学习技术，以人类方式进行多轮对抗探测。实验显示，HARM 能更系统地揭示模型漏洞，并为对齐过程提供精准指导。

> Automated red teaming is an effective method for identifying misaligned behaviors in large language models (LLMs). Existing approaches, however, often focus primarily on improving attack success rates while overlooking the need for comprehensive test case coverage. Additionally, most of these methods are limited to single-turn red teaming, failing to capture the multi-turn dynamics of real-world human-machine interactions. To overcome these limitations, we propose HARM (Holistic Automated Red teaMing), which scales up the diversity of test cases using a top-down approach based on an extensible, fine-grained risk taxonomy. Our method also leverages a novel fine-tuning strategy and reinforcement learning techniques to facilitate multi-turn adversarial probing in a human-like manner. Experimental results demonstrate that our framework enables a more systematic understanding of model vulnerabilities and offers more targeted guidance for the alignment process.

[Arxiv](https://arxiv.org/abs/2409.16783)