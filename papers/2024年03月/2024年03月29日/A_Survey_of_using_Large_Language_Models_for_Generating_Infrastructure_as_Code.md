# 本文综述了运用大型语言模型来生成基础设施即代码（Infrastructure as Code, IaC）的技术与应用。

发布时间：2024年03月29日

`LLM应用` `基础设施即代码` `自动化`

> A Survey of using Large Language Models for Generating Infrastructure as Code

# 摘要

> 基础设施即代码（IaC）正以其革命性的面貌在工业界崭露头角。通过运用机器可读的代码，IaC实现了IT基础设施的自动化管理与配置，带来了环境间的一致性、可重复性、版本控制、减少错误以及可伸缩性的提升。尽管如此，IaC的编排过程仍需付出大量专业技能和手工劳动。面对工业界的当前需求，IaC自动化迫在眉睫。本次调研探讨了运用大型语言模型（LLM）来应对这一挑战的可能性。LLM作为强大的神经网络模型，不仅在语言处理上表现出色，还能遵循广泛指令，近期更在代码理解与生成方面取得成功，使其成为自动化生成IaC配置的有力候选者。本文深入分析了IaC的各个方面、在不同平台上的应用现状、所面临的挑战，以及LLM在代码生成方面的作用和在IaC中的重要性，并分享了我们的实验成果。最终，文章以指出该领域的挑战和未来研究的潜力作为总结。

> Infrastructure as Code (IaC) is a revolutionary approach which has gained significant prominence in the Industry. IaC manages and provisions IT infrastructure using machine-readable code by enabling automation, consistency across the environments, reproducibility, version control, error reduction and enhancement in scalability. However, IaC orchestration is often a painstaking effort which requires specialised skills as well as a lot of manual effort. Automation of IaC is a necessity in the present conditions of the Industry and in this survey, we study the feasibility of applying Large Language Models (LLM) to address this problem. LLMs are large neural network-based models which have demonstrated significant language processing abilities and shown to be capable of following a range of instructions within a broad scope. Recently, they have also been adapted for code understanding and generation tasks successfully, which makes them a promising choice for the automatic generation of IaC configurations. In this survey, we delve into the details of IaC, usage of IaC in different platforms, their challenges, LLMs in terms of code-generation aspects and the importance of LLMs in IaC along with our own experiments. Finally, we conclude by presenting the challenges in this area and highlighting the scope for future research.

[Arxiv](https://arxiv.org/abs/2404.00227)