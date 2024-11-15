# SmartInv：用于智能合约不变式推理的多模态学习方式

发布时间：2024年11月14日

`其他` `区块链` `智能合约`

> SmartInv: Multimodal Learning for Smart Contract Invariant Inference

# 摘要

> 智能合约是能在区块链上开展各类商业活动的软件程序。近期研究发现了新的“机器不可审计”错误类别，它们源自交易情境和源代码。现有的检测手段需要人去理解底层交易逻辑，并在不同的情境来源（即模式）间进行手动推理，像代码、动态交易执行以及描述预期交易行为的自然语言。

为实现“机器不可审计”错误的自动检测，我们推出了 SmartInv，这是一个精准且快速的智能合约不变量推理框架。我们的关键认识在于，智能合约的预期行为（由不变量规定）依赖于对多模态信息（比如源代码和自然语言）的理解与推理。我们向基础模型提出了新的提示策略——思维层次（ToT），用于对智能合约的多种模式进行推理，最终生成不变量。通过检查这些生成不变量的违反情况，SmartInv 能够找出潜在漏洞。

我们在真实合约上对 SmartInv 进行评估，重新发现了过去 2.5 年（2021 年 1 月 1 日至 2023 年 5 月 31 日）造成数百万美元损失的错误。大量评估显示，与前沿工具相比，SmartInv 在大幅（150 倍）缩短的时间内生成了（3.5 倍）更多关键错误的不变量，检测出（4 倍）更多关键错误。\sys 从 89621 个真实合约中找出了 119 个零日漏洞。其中，有 5 个被开发者认定为“高严重性”的关键零日错误。

> Smart contracts are software programs that enable diverse business activities on the blockchain. Recent research has identified new classes of "machine un-auditable" bugs that arise from both transactional contexts and source code. Existing detection methods require human understanding of underlying transaction logic and manual reasoning across different sources of context (i.e. modalities), such as code, dynamic transaction executions, and natural language specifying the expected transaction behavior.
  To automate the detection of ``machine un-auditable'' bugs, we present SmartInv, an accurate and fast smart contract invariant inference framework. Our key insight is that the expected behavior of smart contracts, as specified by invariants, relies on understanding and reasoning across multimodal information, such as source code and natural language. We propose a new prompting strategy to foundation models, Tier of Thought (ToT), to reason across multiple modalities of smart contracts and ultimately to generate invariants. By checking the violation of these generated invariants, SmartInv can identify potential vulnerabilities.
  We evaluate SmartInv on real-world contracts and re-discover bugs that resulted in multi-million dollar losses over the past 2.5 years (from January 1, 2021 to May 31, 2023). Our extensive evaluation shows that SmartInv generates (3.5X) more bug-critical invariants and detects (4$\times$) more critical bugs compared to the state-of-the-art tools in significantly (150X) less time. \sys uncovers 119 zero-day vulnerabilities from the 89,621 real-world contracts. Among them, five are critical zero-day bugs confirmed by developers as ``high severity.''

[Arxiv](https://arxiv.org/abs/2411.09217)