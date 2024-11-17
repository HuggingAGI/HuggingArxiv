# 《语义侦探：借大型语言模型识别庞氏合同》

发布时间：2024年11月11日

`LLM应用` `区块链`

> Semantic Sleuth: Identifying Ponzi Contracts via Large Language Models

# 摘要

> 智能合约，即直接以代码形式编码的自动执行协议，乃是区块链技术的基石，尤其在去中心化金融（DeFi）和 Web3 领域。然而，智能合约中庞氏骗局的涌现带来极大风险，造成巨额财务损失，也削弱了人们对区块链系统的信任。现有的检测手段，像 PonziGuard，依赖大量有标记数据，且难以识别未曾见过的庞氏骗局，这限制了其可靠性和通用性。相较而言，我们推出了 PonziSleuth，这是首个用于检测庞氏智能合约的 LLM 驱动方法，无需有标记的训练数据。PonziSleuth 借助 LLM 先进的语言理解能力，通过新颖的两步零样本思维链提示技术来剖析智能合约源代码。我们在基准数据集和现实世界的合约上展开的广泛评估显示，PonziSleuth 在无需大量数据的情况下，表现相当甚至更出色，使用 GPT-3.5-turbo 时平衡检测准确率达 96.06%，使用 LLAMA3 时达 93.91%，使用 Mistral 时达 94.27%。在现实世界的检测中，PonziSleuth 成功从 2024 年 3 月由 Etherscan 验证的 4597 份合约里识别出 15 个新的庞氏骗局，假阴性率为 0%，假阳性率为 0.29%。这些成果彰显了 PonziSleuth 检测各类新型庞氏骗局的能力，标志着在借助 LLM 强化区块链安全和遏制金融诈骗方面的重大进步。

> Smart contracts, self-executing agreements directly encoded in code, are fundamental to blockchain technology, especially in decentralized finance (DeFi) and Web3. However, the rise of Ponzi schemes in smart contracts poses significant risks, leading to substantial financial losses and eroding trust in blockchain systems. Existing detection methods, such as PonziGuard, depend on large amounts of labeled data and struggle to identify unseen Ponzi schemes, limiting their reliability and generalizability. In contrast, we introduce PonziSleuth, the first LLM-driven approach for detecting Ponzi smart contracts, which requires no labeled training data. PonziSleuth utilizes advanced language understanding capabilities of LLMs to analyze smart contract source code through a novel two-step zero-shot chain-of-thought prompting technique. Our extensive evaluation on benchmark datasets and real-world contracts demonstrates that PonziSleuth delivers comparable, and often superior, performance without the extensive data requirements, achieving a balanced detection accuracy of 96.06% with GPT-3.5-turbo, 93.91% with LLAMA3, and 94.27% with Mistral. In real-world detection, PonziSleuth successfully identified 15 new Ponzi schemes from 4,597 contracts verified by Etherscan in March 2024, with a false negative rate of 0% and a false positive rate of 0.29%. These results highlight PonziSleuth's capability to detect diverse and novel Ponzi schemes, marking a significant advancement in leveraging LLMs for enhancing blockchain security and mitigating financial scams.

[Arxiv](https://arxiv.org/abs/2411.07498)