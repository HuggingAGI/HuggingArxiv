# 利用无声标记提升对大型语言模型的越狱攻击能力

发布时间：2024年05月31日

`LLM应用

这篇论文主要关注了大型语言模型（LLM）在面对越狱攻击时的安全威胁，并提出了一种新的攻击方法——BOOST攻击。该方法通过在有害问题后添加几个eos标记来绕过LLMs的安全机制，实现越狱。这种攻击方法的提出和实证分析，以及对LLM安全性的讨论，都属于LLM应用的范畴，因为它涉及到如何应用LLM以及如何改进其安全性以应对实际的攻击场景。因此，这篇论文应归类于LLM应用。` `网络安全` `人工智能安全`

> Enhancing Jailbreak Attack Against Large Language Models through Silent Tokens

# 摘要

> 随着语言模型的巨大成功，研究者们也开始关注LLMs面临的安全威胁，特别是越狱攻击。攻击者通过精心设计的提示，诱使LLM回应有害问题。以往的越狱攻击要么依赖专家，要么使用复杂算法来设计提示。本文提出的BOOST攻击方法简单高效，仅通过在有害问题后添加几个eos标记，就能轻松绕过LLMs的安全机制，实现越狱。我们将BOOST应用于四种主流越狱技术，发现只需添加eos标记，攻击成功率便大幅提升。通过实证分析，我们发现eos标记让LLM低估了输入的危害性，且因其低注意力值，不影响LLM对问题的理解，从而使模型回应了问题。这一发现凸显了LLM在越狱攻击面前的脆弱性，强调了开发更强安全校准方法的必要性。

> Along with the remarkable successes of Language language models, recent research also started to explore the security threats of LLMs, including jailbreaking attacks. Attackers carefully craft jailbreaking prompts such that a target LLM will respond to the harmful question. Existing jailbreaking attacks require either human experts or leveraging complicated algorithms to craft jailbreaking prompts. In this paper, we introduce BOOST, a simple attack that leverages only the eos tokens. We demonstrate that rather than constructing complicated jailbreaking prompts, the attacker can simply append a few eos tokens to the end of a harmful question. It will bypass the safety alignment of LLMs and lead to successful jailbreaking attacks. We further apply BOOST to four representative jailbreak methods and show that the attack success rates of these methods can be significantly enhanced by simply adding eos tokens to the prompt. To understand this simple but novel phenomenon, we conduct empirical analyses. Our analysis reveals that adding eos tokens makes the target LLM believe the input is much less harmful, and eos tokens have low attention values and do not affect LLM's understanding of the harmful questions, leading the model to actually respond to the questions. Our findings uncover how fragile an LLM is against jailbreak attacks, motivating the development of strong safety alignment approaches.

[Arxiv](https://arxiv.org/abs/2405.20653)