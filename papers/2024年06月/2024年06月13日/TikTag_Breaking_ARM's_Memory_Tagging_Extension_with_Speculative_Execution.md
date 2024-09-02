# TikTag：通过推测执行技术，破解了 ARM 的内存标记扩展。

发布时间：2024年06月13日

`LLM理论` `软件安全` `网络安全`

> TikTag: Breaking ARM's Memory Tagging Extension with Speculative Execution

# 摘要

> 摘要：ARM 的 MTE 技术，作为 ARMv8.5-A 架构的新特性，旨在检测内存漏洞，因其低开销而备受青睐，被视为提升 C/C++ 软件安全的关键。然而，本文揭示了针对 MTE 的推测执行攻击的新风险，特别是通过识别的 TikTag gadgets，这些 gadgets 能泄露 MTE 标签，显著提高攻击成功率。我们证实了这些 gadgets 在实际系统中的有效性，如 Google Chrome 和 Linux 内核，并展示了它们在极短时间内的高成功率。为此，我们提出了新的防御策略，以应对这一威胁。

> 
Abstract:ARM Memory Tagging Extension (MTE) is a new hardware feature introduced in ARMv8.5-A architecture, aiming to detect memory corruption vulnerabilities. The low overhead of MTE makes it an attractive solution to mitigate memory corruption attacks in modern software systems and is considered the most promising path forward for improving C/C++ software security. This paper explores the potential security risks posed by speculative execution attacks against MTE. Specifically, this paper identifies new TikTag gadgets capable of leaking the MTE tags from arbitrary memory addresses through speculative execution. With TikTag gadgets, attackers can bypass the probabilistic defense of MTE, increasing the attack success rate by close to 100%. We demonstrate that TikTag gadgets can be used to bypass MTE-based mitigations in real-world systems, Google Chrome and the Linux kernel. Experimental results show that TikTag gadgets can successfully leak an MTE tag with a success rate higher than 95% in less than 4 seconds. We further propose new defense mechanisms to mitigate the security risks posed by TikTag gadgets.
    

[Arxiv](https://arxiv.org/pdf/2406.08719)