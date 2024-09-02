# 探索 Linux 系统中，针对数据攻击的新型文件系统对象，超越传统控制手段。

发布时间：2024年01月31日

`Agent` `操作系统` `网络安全`

> Beyond Control: Exploring Novel File System Objects for Data-Only Attacks on Linux Systems

# 摘要

> 摘要：随着控制流完整性的普及，非控制数据攻击成为主流。在操作系统内核漏洞领域，攻击者通过破坏关键非控制数据，无需劫持控制流即可获取root权限或提升权限。为此，内核限制了非控制数据的可用性，迫使攻击者在内核中寻找更多可利用数据。然而，发现这些未知数据极具挑战，因其与语义紧密相关且缺乏通用模式。本文贡献如下：首先，我们在文件子系统中发现关键非控制对象；其次，分析其可利用性。这是首次在有限领域知识基础上，半自动发现和评估Linux内核文件子系统中的可利用非控制数据。我们开发了定制的分析和测试框架，静态和动态地识别潜在候选对象，并将它们分类为适合多种利用策略的类型，包括一种新策略以突破隔离防御。这些对象无需KASLR即可利用，使漏洞利用更简单可靠。我们通过18个真实CVE评估了文件系统对象的可利用性，并针对启用了所有先进缓解措施的内核，开发了10个端到端漏洞利用。

> 
Abstract:The widespread deployment of control-flow integrity has propelled non-control data attacks into the mainstream. In the domain of OS kernel exploits, by corrupting critical non-control data, local attackers can directly gain root access or privilege escalation without hijacking the control flow. As a result, OS kernels have been restricting the availability of such non-control data. This forces attackers to continue to search for more exploitable non-control data in OS kernels. However, discovering unknown non-control data can be daunting because they are often tied heavily to semantics and lack universal patterns.
We make two contributions in this paper: (1) discover critical non-control objects in the file subsystem and (2) analyze their exploitability. This work represents the first study, with minimal domain knowledge, to semi-automatically discover and evaluate exploitable non-control data within the file subsystem of the Linux kernel. Our solution utilizes a custom analysis and testing framework that statically and dynamically identifies promising candidate objects. Furthermore, we categorize these discovered objects into types that are suitable for various exploit strategies, including a novel strategy necessary to overcome the defense that isolates many of these objects. These objects have the advantage of being exploitable without requiring KASLR, thus making the exploits simpler and more reliable. We use 18 real-world CVEs to evaluate the exploitability of the file system objects using various exploit strategies. We develop 10 end-to-end exploits using a subset of CVEs against the kernel with all state-of-the-art mitigations enabled.
    

[Arxiv](https://arxiv.org/pdf/2401.17618)