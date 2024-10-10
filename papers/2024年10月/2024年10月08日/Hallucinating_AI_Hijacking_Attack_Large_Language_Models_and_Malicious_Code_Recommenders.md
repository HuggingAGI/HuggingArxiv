# AI 幻觉劫持：探讨大型语言模型与恶意代码推荐器的潜在威胁

发布时间：2024年10月08日

`LLM应用` `网络安全` `软件开发`

> Hallucinating AI Hijacking Attack: Large Language Models and Malicious Code Recommenders

# 摘要

> 研究探讨了在热门代码库中植入复制代码或AI幻觉推荐的恶意代码的可能性。尽管OpenAI、Google和Anthropic的基础LLM能防范有害行为和毒性内容，但先前研究表明，专家上下文中的防护措施可能存在差异。当问题背景变化时，这些漏洞会在专家模型混合中显现，减少恶意训练样本以过滤毒性评论或推荐攻击行为。当前研究发现，基础模型在明确提示下可能拒绝破坏性行为，但在面对突如其来的上下文变化时，如编程挑战，可能放松警惕。我们通过GitHub、NPM、NuGet等特洛伊木马仓库和jsDelivr等流行CDN的实例，展示了攻击面的扩大。LLM的推荐中，API端点可能被恶意域名抢注者利用，设置攻击移动基础设施。我们将这种攻击与上下文转移的先前工作对比，并将其视为恶意软件文献中“生活在土地上”攻击的新版本。此外，基础语言模型可能劫持无辜用户提示，直接推荐违反安全政策的行动。

> The research builds and evaluates the adversarial potential to introduce copied code or hallucinated AI recommendations for malicious code in popular code repositories. While foundational large language models (LLMs) from OpenAI, Google, and Anthropic guard against both harmful behaviors and toxic strings, previous work on math solutions that embed harmful prompts demonstrate that the guardrails may differ between expert contexts. These loopholes would appear in mixture of expert's models when the context of the question changes and may offer fewer malicious training examples to filter toxic comments or recommended offensive actions. The present work demonstrates that foundational models may refuse to propose destructive actions correctly when prompted overtly but may unfortunately drop their guard when presented with a sudden change of context, like solving a computer programming challenge. We show empirical examples with trojan-hosting repositories like GitHub, NPM, NuGet, and popular content delivery networks (CDN) like jsDelivr which amplify the attack surface. In the LLM's directives to be helpful, example recommendations propose application programming interface (API) endpoints which a determined domain-squatter could acquire and setup attack mobile infrastructure that triggers from the naively copied code. We compare this attack to previous work on context-shifting and contrast the attack surface as a novel version of "living off the land" attacks in the malware literature. In the latter case, foundational language models can hijack otherwise innocent user prompts to recommend actions that violate their owners' safety policies when posed directly without the accompanying coding support request.

[Arxiv](https://arxiv.org/abs/2410.06462)