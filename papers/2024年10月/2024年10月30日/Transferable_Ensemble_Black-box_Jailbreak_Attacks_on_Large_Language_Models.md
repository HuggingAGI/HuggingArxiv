# 针对大型语言模型的可转移集成黑箱越狱式攻击

发布时间：2024年10月30日

`LLM应用` `网络安全` `人工智能安全`

> Transferable Ensemble Black-box Jailbreak Attacks on Large Language Models

# 摘要

> 在本报告中，我们提出了一个全新的黑盒越狱攻击框架，融合了多种以LLM为攻击者的手段，以达成可迁移且强大的越狱攻击效果。我们的方法基于现有越狱研究与实践中的三项关键观察所得而设计。其一，相较于单独攻击，我们认为集成式方法在揭露对齐的LLM漏洞方面会更有效。其二，不同的恶意指令在越狱难度上本就存在差异，需要区别处理以保障更高效的攻击。其三，恶意指令的语义连贯性对于触发对齐的LLM的防御极为关键；所以，必须谨慎地对其进行破坏以操控其嵌入表示，进而提升越狱成功率。我们通过参与2024年LLM和代理安全竞赛对我们的方法进行了验证，我们的团队在越狱攻击赛道中斩获了顶尖佳绩。

> In this report, we propose a novel black-box jailbreak attacking framework that incorporates various LLM-as-Attacker methods to deliver transferable and powerful jailbreak attacks. Our method is designed based on three key observations from existing jailbreaking studies and practices. First, we consider an ensemble approach should be more effective in exposing the vulnerabilities of an aligned LLM compared to individual attacks. Second, different malicious instructions inherently vary in their jailbreaking difficulty, necessitating differentiated treatment to ensure more efficient attacks. Finally, the semantic coherence of a malicious instruction is crucial for triggering the defenses of an aligned LLM; therefore, it must be carefully disrupted to manipulate its embedding representation, thereby increasing the jailbreak success rate. We validated our approach by participating in the Competition for LLM and Agent Safety 2024, where our team achieved top performance in the Jailbreaking Attack Track.

[Arxiv](https://arxiv.org/abs/2410.23558)