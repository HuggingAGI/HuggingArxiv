# 借助良性数据镜像对大型语言模型展开的隐秘越狱式攻击

发布时间：2024年10月28日

`LLM应用` `语言模型`

> Stealthy Jailbreak Attacks on Large Language Models via Benign Data Mirroring

# 摘要

> 大型语言模型（LLM）的安全是个关键问题，众多研究借助红队测试来提升模型的安全性。在这当中，越狱方法通过精心打造恶意提示来探寻潜在漏洞，这些提示会诱导模型输出违背安全对齐的内容。现有的黑箱越狱手段往往依赖模型反馈，在攻击搜索过程中反复提交带有可察觉恶意指令的查询。虽说这些方法行之有效，但在搜索过程中攻击可能会被内容监管员拦截。我们提出了一种改良的迁移攻击方法，通过良性数据蒸馏在本地训练目标黑箱模型的镜像模型，以此指导恶意提示的构建。该方法具有更强的隐蔽性，因为在搜索阶段不会向目标模型提交可识别的恶意指令。我们的方法在 AdvBench 的一个子集上针对 GPT-3.5 Turbo 取得了最高 92%的攻击成功率，或者平衡值达到 80%，平均每个样本有 1.5 个可检测的越狱查询。这些结果表明需要更有力的防御机制。

> Large language model (LLM) safety is a critical issue, with numerous studies employing red team testing to enhance model security. Among these, jailbreak methods explore potential vulnerabilities by crafting malicious prompts that induce model outputs contrary to safety alignments. Existing black-box jailbreak methods often rely on model feedback, repeatedly submitting queries with detectable malicious instructions during the attack search process. Although these approaches are effective, the attacks may be intercepted by content moderators during the search process. We propose an improved transfer attack method that guides malicious prompt construction by locally training a mirror model of the target black-box model through benign data distillation. This method offers enhanced stealth, as it does not involve submitting identifiable malicious instructions to the target model during the search phase. Our approach achieved a maximum attack success rate of 92%, or a balanced value of 80% with an average of 1.5 detectable jailbreak queries per sample against GPT-3.5 Turbo on a subset of AdvBench. These results underscore the need for more robust defense mechanisms.

[Arxiv](https://arxiv.org/abs/2410.21083)