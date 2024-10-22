# MAD：通过将 AI 反编译器引入非开源区块链智能合约，提升透明度和审计能力

发布时间：2024年10月20日

`LLM应用` `区块链` `智能合约`

> MAD: Move AI Decompiler to Improve Transparency and Auditability on Non-Open-Source Blockchain Smart Contract

# 摘要

> Web3 愿景在于提升用户对数据和资产的掌控，但这一目标面临不透明应用和脆弱智能合约的挑战。代码审计虽为解决方案之一，但许多平台如 Sui 缺乏源代码，审计难度大。我们开发的 Move AI Decompiler (MAD) 利用大型语言模型 (LLM)，将 Sui 智能合约字节码反编译为逻辑正确、易读且可重新编译的源代码。评估显示，MAD 生成的代码不仅逻辑正确，还能通过原始测试，实际应用中重新编译成功率达 66.7%。用户研究中，12 名开发者使用 MAD 后，审计工作量显著减少，输出代码与原始源码相当，极大简化了合约理解和审计。尽管存在偶尔的幻觉和编译错误，MAD 仍大幅优于传统反编译器。MAD 不仅提升智能合约透明度和审计效率，还促进用户对非开源合约的审查，增强信任和问责。其方法未来或可应用于其他智能合约语言，如 Solidity，推动区块链整体透明度。

> Web3 aims to enhance user control over data and assets, but this vision is challenged by non-transparent, scam-prone applications and vulnerable smart contracts. While code audits are one solution to this problem, the lack of smart contracts source code on many blockchain platforms, such as Sui, hinders the ease of auditing. A promising approach to this issue is the use of a decompiler to reverse-engineer smart contract bytecode. However, existing decompilers for Sui produce code that is difficult to understand and cannot be directly recompiled. To address this, we developed the Move AI Decompiler (MAD), a Large Language Model (LLM)-powered web application that decompiles smart contract bytecodes on Sui into logically correct, human-readable, and re-compilable source code.
  Our evaluation shows that MAD produces logically correct code that successfully passes original unit tests and achieves a 66.7% recompilation success rate on real-world smart contracts. Additionally, in a user study involving 12 developers, MAD significantly reduced the auditing workload compared to using traditional decompilers. Participants found MAD's outputs comparable to the original source code, simplifying the process of smart contract logic comprehension and auditing. Despite some limitations, such as occasional hallucinations and compile errors, MAD still provides significant improvements over traditional decompilers.
  MAD has practical implications for blockchain smart contract transparency, auditing, and education. It empowers users to review and audit non-open-source smart contracts, fostering trust and accountability. Additionally, MAD's approach could potentially extend to other smart contract languages, like Solidity, promoting transparency across various blockchains.

[Arxiv](https://arxiv.org/abs/2410.15275)