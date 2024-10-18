# JAILJUDGE：一个综合的越狱判断基准，结合了多代理增强的解释评估框架，旨在全面评估越狱行为。

发布时间：2024年10月11日

`Agent` `网络安全` `人工智能`

> JAILJUDGE: A Comprehensive Jailbreak Judge Benchmark with Multi-Agent Enhanced Explanation Evaluation Framework

# 摘要

> 尽管LLM在抵御越狱攻击方面有所进步，但评估其防御措施仍具挑战，现有方法常缺乏解释性和复杂场景的适应性，导致评估不全面。为此，我们推出JAILJUDGE，一个包含合成、对抗、现实及多语言提示等多样化风险场景的综合基准，并配备高质量人工注释数据集。JAILJUDGE数据集包含35k+指令调优数据及4.5k+标记风险场景，覆盖十种语言。为提升评估的推理透明度，我们设计了JailJudge MultiAgent框架，支持1到10的细粒度评分。该框架助力构建指令调优基础事实，并推动JAILJUDGE Guard的研发，实现端到端推理判断，降低API成本。此外，我们推出JailBoost攻击增强器和GuardShield防御系统，均依托JAILJUDGE Guard。实验显示，JailJudge方法在GPT-4、Llama-Guard等多模型及零样本场景中表现卓越。JailBoost提升攻击性能29.24%，GuardShield将防御成功率从40.46%降至0.15%。

> Despite advancements in enhancing LLM safety against jailbreak attacks, evaluating LLM defenses remains a challenge, with current methods often lacking explainability and generalization to complex scenarios, leading to incomplete assessments (e.g., direct judgment without reasoning, low F1 score of GPT-4 in complex cases, bias in multilingual scenarios). To address this, we present JAILJUDGE, a comprehensive benchmark featuring diverse risk scenarios, including synthetic, adversarial, in-the-wild, and multilingual prompts, along with high-quality human-annotated datasets. The JAILJUDGE dataset includes over 35k+ instruction-tune data with reasoning explainability and JAILJUDGETEST, a 4.5k+ labeled set for risk scenarios, and a 6k+ multilingual set across ten languages. To enhance evaluation with explicit reasoning, we propose the JailJudge MultiAgent framework, which enables explainable, fine-grained scoring (1 to 10). This framework supports the construction of instruction-tuning ground truth and facilitates the development of JAILJUDGE Guard, an end-to-end judge model that provides reasoning and eliminates API costs. Additionally, we introduce JailBoost, an attacker-agnostic attack enhancer, and GuardShield, a moderation defense, both leveraging JAILJUDGE Guard. Our experiments demonstrate the state-of-the-art performance of JailJudge methods (JailJudge MultiAgent, JAILJUDGE Guard) across diverse models (e.g., GPT-4, Llama-Guard) and zero-shot scenarios. JailBoost and GuardShield significantly improve jailbreak attack and defense tasks under zero-shot settings, with JailBoost enhancing performance by 29.24% and GuardShield reducing defense ASR from 40.46% to 0.15%.

[Arxiv](https://arxiv.org/abs/2410.12855)